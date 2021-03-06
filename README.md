﻿# Sistema de Votação em tempo real #

Este trabalho apresenta uma implementação de um sistema de votação em tempo real em um ambiente cliente/servidor virtualizando ferramentas e tecnologias livres que foi desenvolvido como trabalho para a disciplina de Plataforma de Desenvolvimento em Software Livre e Servidores Web.

**Integrantes:**
 - Angelo Morares Machiaveli
 - Bruno Henrique dos Santos
 - Kleber Ávila da Silva


# Introdução #
Geralmente nos sistemas web, a comunicação é realizada através de requisições do cliente para o servidor, ou seja, o servidor somente envia dados para o cliente somente quando é requisitado. (BORIN, 2018). 
Porém existe uma outra forma de comunicação entre eles que é a comunicação em tempo real, em que um servidor sempre envia dados atualizados para os clientes sem precisar de requisições. (UNDERGROUND WEB DEV, 2018).
Portanto, o objetivo deste trabalho é demonstrar a comunicação em tempo real entre cliente e servidor utilizando um sistema de votação. A implementação foi realizada em um ambiente virtualizado, sendo uma máquina virtual servidor hospedando o sistema, que foi desenvolvido para este trabalho. Todas as ferramentas e tecnologias utilizadas para o desenvolvimento deste trabalho são livres.

BORIN, Juliana F. Modelo Cliente/Servidor e Introdução a Sockets. Disponível em: <http://www.ic.unicamp.br/~juliana/cursos/mc833/aula4.pdf>. Acesso em: 23 Out. 2018.

UNDERGROUND WEB DEV. Real-time com Socket.IO no Node.js. Disponível em: <https://udgwebdev.com/real-time-com-socket-io-no-nodejs/>. Acesso em: 23 Out. 2018;

# Ferramentas Utilizadas #

 - **JavaScript**
 - **Node.js**
 - **Express.js**
 - **Socket.io**
 - **Bootstrap**
 - **JQuery**
 - **Docker**
 
 # Instalação #

**1) Download do projeto** ![Download](https://github.com/myersBR/votacao-app/archive/latest.tar.gz)

**2) Descompactar arquivo**

**3) Acessar a pasta descompacta**

**4) Criação da imagem**

   - Após acessar a pasta compactada executaremos o comando **docker build -t nomeDaImagem**, onde o nomeDaImagem fica a critério para escolha
   
**4) Criação do container e execução da aplicação**

   - Para a criação do container e a execução da aplicação utilizamos o comando **docker run -p numeroDaPortaExterna:3000 -d nomeDaImagem**, onde o "nomeDaImagem é o mesmo que informamos no passo 4 e o parâmetro "numeroDaPortaExterna" é o número da porta que será utilizada para o redirecionamento para a porta 3000 da nossa aplicação.
   
**5) Acessando a aplicação**

 - Após a execução dos passos acima podemos acessar a nossa aplicação no servidor através do endereço **localhost:numerodaPortaExterna**, e nas máquinas externas (clientes) através do endereço **enderecoip:numeroDaPortaExterna**.
   

    
    
   
   


