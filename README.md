# Ferramentas para Instalação
_o melhor tutorial ein_


## Spring Tool Suite

_Instalação para o sistema operacional Ubuntu 20.04.3 LTS:_

O Spring Tool Suite é uma IDE baseada em Eclipse que dá algumas facilidades para trabalhos com o Spring no geral.
 Uma das coisas legais é que ele nos ajuda a criar projetos com Spring Boot.


**Primeiro passo**
* Abra o terminal e atualize os pacotes:
~~~
sudo apt-get update
~~~

**Segundo passo**
* É atualizar os caminhos:
~~~
sudo apt-get upgrade
~~~

**Terceiro passo**
* Se você usa a Snap store pode colocar o seguinte comando:
~~~
sudo snap refresh
~~~

**Quarto passo**

* Baixe a versão atualizada no site https://spring.io/tools;

![Spring](https://blog.kakaocdn.net/dn/pKIDm/btqzwYPTJSK/YLtOK4ob8HMnrBk1nyjZW0/img.png)


**Quinto passo**
* Descompacte o arquivo baixado, clique com o botão direito e aperte em "Abrir no Terminal";

**Sexto passo**
* Acesse a pasta sts-4.13.0.RELEASE:
~~~
cd sts-4.13.0.RELEASE
~~~

**Sétimo passo**
* Execute o programa:
~~~
sudo ./SpringToolSuite4
~~~


**PARABÉNS A VERSÃO: sts-4.13.0.RELEASE ESTÁ INSTALADA!**



## Java

Java é uma linguagem de programação e plataforma computacional lançada pela primeira vez pela Sun Microsystems em 1995.

* No terminal digite:
~~~
sudo apt-get install openjdk-11-jdk
~~~

* Verifique a versão instalada:
~~~
java -version
~~~
* Deve receber a resposta:

~~~
openjdk version "11.0.13" 2021-10-19
OpenJDK Runtime Environment (build 11.0.13+8-Ubuntu-0ubuntu1.20.04)
OpenJDK 64-Bit Server VM (build 11.0.13+8-Ubuntu-0ubuntu1.20.04, mixed mode, sharing)
~~~

## MySQL

O MySQL é um sistema open-source de gerenciamento de base de dados relacional SQL, desenvolvido e suportado pela Oracle.

* Cole no terminal o seguinte comando:
~~~
sudo apt install mysql-server
~~~
* Aperte y para selecionar yes;

* Certifique-se da versão do MySQL instalada:
~~~
mysql --version 
~~~
* Deve aparecer:
~~~
mysql  Ver 8.0.27-0ubuntu0.20.04.1 for Linux on x86_64 ((Ubuntu))
~~~

## Git

Git é um software para rastrear mudanças em qualquer conjunto de arquivos , geralmente usado para coordenar o trabalho entre programadores que desenvolvem 
código-fonte colaborativamente durante o desenvolvimento de software. Seus objetivos incluem velocidade, integridade de dados e suporte 
para fluxos de trabalho distribuídos e não lineares (milhares de ramificações paralelas executadas em diferentes sistemas).


* Execute no terminal o seguinte comando:
~~~
sudo apt install git
~~~

* Verifique a versão: 
~~~
git --version
~~~

* Observe se confere:
~~~
git version 2.25.1
~~~


## Node.js

Node.js é uma tecnologia assíncrona que trabalha em uma única thread de execução. 
Por assíncrona entenda que cada requisição ao Node.js não bloqueia o processo do mesmo, atendendo a um volume absurdamente 
grande de requisições ao mesmo tempo mesmo sendo single thread.

* No terminal digite:
~~~
sudo apt install nodejs
~~~

* Veja a versão instalada:
~~~
node -v
~~~

* Aparecerá:
~~~
v10.16.3
~~~

## Postman

O Postman é um API Client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. 
Isso é feito, permitindo aos usuários criar e salvar solicitações HTTP e HTTPs simples e complexas, bem como ler suas respostas.

* Utilize o comando:
~~~
sudo snap install postman
~~~

* Pesquise nos seus programas por "Postman"

![Postman](https://terminalroot.com.br/assets/img/dev/postman-1.jpg)

* Versão instalada foi: **9.10.0**

## HTTPie

HTTPie é um cliente HTTP de linha de comando que visa tornar a interação da CLI com os serviços da web o mais amigável possível para o ser humano. 
HTTPie é projetado para testar, depurar e, geralmente, interagir com servidores HTTP e APIs. 
Os comandos http e https permitem que você crie e envie solicitações HTTP arbitrárias. Eles usam sintaxe simples e fornecem saída formatada e colorida


* Digite o seguinte comando:
~~~
sudo snap install httpie
~~~
* Observe  a versão instalada:
~~~
http --version
~~~

* Aparecerá:
~~~
2.6.0
~~~



