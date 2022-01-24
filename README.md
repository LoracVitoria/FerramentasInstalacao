# Ferramentas para Instalação

## Spring Tool Suite

_Instalação para o sistema operacional Ubuntu 20.04.3 LTS:_


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

* Execute no terminal o seguinte comando:
~~~
sudo apt install git
~~~

* Verifique a versão: 
~~~
git --version
~~~


## Node.js

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

* Utilize o comando:
~~~
sudo snap install postman
~~~

* Pesquise nos seus programas por "Postman"

![Postman](https://terminalroot.com.br/assets/img/dev/postman-1.jpg)

## Httpie

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



