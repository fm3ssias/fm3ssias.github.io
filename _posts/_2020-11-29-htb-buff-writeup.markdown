---
title: "HackTheBox - Buff"
layout: post
date: 2020-11-29 23:20
image: /assets/images/hello_world.gif
headerImage: true
tag:
- hackthebox
- easy
- windows
category: writeups
author: fm3ssias
description: Writeup of the machine Buff from HackTheBox
---

Alvo: Windows
Conceitos técnicos: Reconhecimento, CVEs, Conexão remota reversa, Port fowarding.
Endereço IP alvo: 10.10.0.198

Começamos fazendo um mapeamento no endereço IP alvo usando a ferramenta nmap:
<img src="../assets/images/HTB/Buff/2020-11-17_22-22.png"  />

A porta 8080 está aberta, servindo uma conexão HTTP. Ao acessa-lá nos deparamos com um website que parece ser de uma academia. É importante acessar todas as páginas possiveis, entender o negócio envolvido e a tecnologia usada no website. E durante esse reconhecimento, na tela de "Contatos" há uma informação que nos informa o framework usado para a criação do website. O Gym Management Software 1.0.
<img src="../assets/images/HTB/Buff/2020-11-17_23-48.png" />

Pesquisando no google sobre esse sistema, já damos de cara com um exploit pra ele:
<img src="../assets/images/HTB/Buff/2020-11-17_23-49.png" />


Acesse o script do Exploit-db, baixe ele pra sua máquina e o execute passando o host do alvo como parâmetro. Você recebrá criada uma shell no webserver.
OBS: Talvez irá faltar algumas dependencias no pip, a "requests" e a "colorama". Instale-as e execute o exploit
<img src="../assets/images/HTB/Buff/2020-11-17_23-50.png"/>

Colocar aqui a parte de jogar o nc.exe lá.

Para conseguir uma shell onde podemos interagir melhor, iremos realizar um conexão reversa. Na máquina atacante faça o netcat escutar em alguma porta (1234 por exemplo):
<img src="../assets/images/HTB/Buff/2020-11-17_23-51.png"/>

E na máquina alvo rode o comando abaixo para fecharmos a conexão 


No final falar sobre alguns conceitos e dicas aprendidas:
- Port fowarding
- Servidor http em python e tranferencia de arquivo pelo powershell

Links úteis: 
https://www.exploit-db.com/exploits/48389
https://www.exploit-db.com/exploits/48506
https://nsworld.com.br/exploit-para-o-gym-management-system-1-0/
https://www.fuzzysecurity.com/tutorials/16.html
https://medium.com/@PenTest_duck/almost-all-the-ways-to-file-transfer-1bd6bf710d65




