---
title: "Iniciando em Bug Bounty #1"
layout: post
date: 2021-04-09 22:30
image: /assets/images/DiarioBounty/1/photo-light-3_1920x1080.png
headerImage: true
tag:
- bugBounty
- diario
category: blog
author: dedgits
description: 
---

Sobre meu background, há um tempo (7 anos) eu já venho estudando computação, fiz Ciência da Computação, já trabalhei com desenvolvimento mobile, como suporte e como analista de segurança. Mesmo olhando pra trás e vendo todo esse tempo que passou, ainda me sinto um noob, e tenho muuito que aprender ainda, principalmente na área de hacking em si. Conheço e vejo pessoas que estão na área a menos tempo que eu e estão lá na frente já, mas enfim, minha intenção não é te desmotivar, nunca devemos nos comparar com os outros, mas sim com seu eu de ontem, e perceber a sua evolução. Isso ajuda muito a longo prazo. Enfim, sempre admirei o mundo do Bug Bounty e finalmente, tendo um conhecimento que julgo ser uma boa base, decidi caçar recompensas de bugs e ver no que dá. 

Meu plano para o(s) primeiro(s) mês(es) é consumir o máximo possível de conteúdo que envolva bug bounty. Mesmo estando naquela euforia de querer começar logo, eu percebi/aprendi que paciência e consistência são palavras chaves quando se trata de bug bounty, então espero manter essa paciência e consistência a longo prazo. A ideia do plano inicial é familiarizar com os termos, as plataformas, os tipos de vulnerabilidades (OWASP Top 10), e claro, criar aquela base dahora pra quando de fato for caçar algum bug a gente tenha aonde recorrer (resumos de estudos e saber pesquisar). 

Fiz uma trilha onde eu começo me registrando nas principais **plataformas** e seguindo os guias de iniciantes que eles sugerem. A principio decidi apenas consumir o conteúdo da HackerOne e da BugCrowd, porque já é bastante coisa.

-   [HackerOne](https://hackerone.com/): 

    - [Hacker101](https://www.hacker101.com/)

    - [100 Hacking Tools and Resources](https://www.hackerone.com/blog/100-hacking-tools-and-resources)

    - [Welcome to HackerOne Docs](https://docs.hackerone.com/hackers.html)

-   [BugCrowd](https://www.bugcrowd.com/):

    - [How to become a Bug Bounty Hunter](https://forum.bugcrowd.com/t/researcher-resources-how-to-become-a-bug-bounty-hunter/1102)

    - [Bughunter University](https://sites.google.com/site/bughunteruniversity/)

    - [Github bugcrowd_university](https://github.com/bugcrowd/bugcrowd_university?utm_source=website&utm_medium=labs&utm_content=education&utm_campaign=resourcekits)

-  [BugHunt](https://admin.bughunt.com.br/)
-  [YesWeHack](https://www.yeswehack.com/)
-  [Intigriti](https://www.intigriti.com/)

Também separei um tempo pra fazer o [curso de introdução ao Bug Bounty do NahamSec](https://www.udemy.com/course/intro-to-bug-bounty-by-nahamsec/). Recomendo seguir ele também, o [canal do Youtube](https://www.youtube.com/channel/UCCZDt7MuC3Hzs6IH4xODLBw) é muito bom e ele faz lives sobre Recon e entrevistando outros bug hunters no [Twitch](https://www.twitch.tv/nahamsec). Ainda não terminei o curso, mas ele explica sobre os tipos de vulnerabilidades mais conhecidas e depois a gente coloca a mão na massa no lab. Durante o vídeo da explicação eu anoto o que eu entendi e acho relevante, e depois tento fazer o lab sozinho antes de ver a resolução. 

Ao longo da semana, com a recomendação de um amigo, passei a acompanhar o [Ofjaaaah e suas lives](https://www.twitch.tv/ofjaaaah). As lives dele tem várias dicas interessantes e ver/ouvir ele falando e fazendo o processo de caçar um bug ajuda muito a entender como as coisas funcionam e te motiva a tentar fazer igual também. As vezes é importante você apenas consumir o conteúdo, mesmo não entendo muita coisa na hora, porque seu cérebro já vai aceitando aquilo como normal e quando você vê você já está botando a mão na massa e aquela barreira de "onde eu começo, o que eu faço, onde clico agora, qual o próximo passo?" some. 

Também entrei no grupo do Telegram da comunidade de Bug Hunters brasileira: [Bug Bounty Hunters Brasil](https://t.me/bugbountyhunterbrasil). Lá a galera é muito de boas, as vezes fala de bounty, as vezes cobram do outro umas coisas engraçadas e quando alguém precisa de ajuda, vai ter alguém pra te responder e te ajudar. 

Nesses primeiros 15 dias eu consegui me familiarizar com as plataformas, aprendi mais sobre como identificar e explorar um Open Redirect, XSS e ainda estou processando mentalmente como identificar um CSRF. Também to me acostumando e aprendendo mais a fundo sobre como usufruir do Developer Tools (F12) e do Burp Suite. Abri 1001 abas, fiquei com elas abertas por um bom tempo, até que eu decidi separar tudo cada um em seu devido lugar. Organização é um ponto chave também.

![img](/assets/images/DiarioBounty/1/1.png)

![img](/assets/images/DiarioBounty/1/2.png)

![img](/assets/images/DiarioBounty/1/3.png)

Abaixo segue alguns recursos (posts, vídeos e ferramentas) que vi ao longo da semana que me motivaram e agregaram algum conhecimento dahora:

-  [Blog Intigriti](https://blog.intigriti.com/)

-  [Playlist Bug Bounty da Roadsec](https://www.youtube.com/playlist?list=PLGdaaZUNDlN5HsJBxBD3dBXzgC-zUZ7qF)

- [Vídeo sobre CSRF](https://www.youtube.com/watch?v=eWEgUcHPle0)

- [Vídeos sobre SSTI](https://www.youtube.com/watch?v=SN6EVIG4c-0&t=185s)

- Sobre XSS:

    - [https://xsswingman.com/](https://xsswingman.com/)

    - [https://github.com/hahwul/dalfox](https://github.com/hahwul/dalfox)

    - [https://xss.pwnfunction.com/](https://xss.pwnfunction.com/)

    - [https://github.com/R0X4R/D4rkXSS](https://github.com/R0X4R/D4rkXSS)

- [Vídeos sobre Race Conditions](https://www.youtube.com/watch?v=bhHvT788juk&t=429s)

- Sobre Cookies:

    - [https://www.youtube.com/watch?v=44c1t_cKylo](https://www.youtube.com/watch?v=44c1t_cKylo)

    - [https://www.youtube.com/watch?v=rdVPflECed8](https://www.youtube.com/watch?v=rdVPflECed8)

- [Live sobre OWASP TOP 10](https://www.youtube.com/watch?v=FhyLmDBdIO0&t=5s)

- Sobre Open Redirect:

    - [https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Open Redirect](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Open%20Redirect)

    - [https://blog.detectify.com/2019/05/16/the-real-impact-of-an-open-redirect/](https://blog.detectify.com/2019/05/16/the-real-impact-of-an-open-redirect/)

    - [https://pentester.land/cheatsheets/2018/11/02/open-redirect-cheatsheet.html](https://pentester.land/cheatsheets/2018/11/02/open-redirect-cheatsheet.html)

    - [https://infosecwriteups.com/open-redirection-leads-to-a-bounty-d94029e11d17](https://infosecwriteups.com/open-redirection-leads-to-a-bounty-d94029e11d17)

- Como começar em bug bounty:

    - [https://github.com/bughuntersbr/forum/issues/1](https://github.com/bughuntersbr/forum/issues/1)

    - [https://github.com/nahamsec/Resources-for-Beginner-Bug-Bounty-Hunters](https://github.com/nahamsec/Resources-for-Beginner-Bug-Bounty-Hunters)

    - [https://www.youtube.com/watch?v=kn0jClWSdD8](https://www.youtube.com/watch?v=kn0jClWSdD8)

    - [https://www.youtube.com/watch?v=A0LTyH4tOmQ](https://www.youtube.com/watch?v=A0LTyH4tOmQ)

    - [https://www.youtube.com/watch?v=CU9Iafc-Igs&t=1s](https://www.youtube.com/watch?v=CU9Iafc-Igs&t=1s)

    - [https://www.youtube.com/watch?v=vAjJBBnsPmM](https://www.youtube.com/watch?v=vAjJBBnsPmM)

    - [https://www.youtube.com/watch?v=AbebbJ3cRLI&t=3302s](https://www.youtube.com/watch?v=AbebbJ3cRLI&t=3302s)

    - [https://www.youtube.com/watch?v=t3lwdl0zfPo](https://www.youtube.com/watch?v=t3lwdl0zfPo)

    - [https://www.youtube.com/watch?v=roVg_wgGgxQ](https://www.youtube.com/watch?v=roVg_wgGgxQ)

- Falha no facebook (videos do Gabriel Pato)

    - [https://www.youtube.com/watch?v=Q0pKIwHbI5s](https://www.youtube.com/watch?v=Q0pKIwHbI5s)

    - [https://www.youtube.com/watch?v=mQthhtlryMg](https://www.youtube.com/watch?v=mQthhtlryMg)

- Misc:

    - [BUG BOUNTY LIFE - BUGCROWD BUGBASH SF 2019 (Hacking Atlassian - Bug Bounty Life)](https://www.youtube.com/watch?v=g42pD8P4ZZ8)

    - [Ekoparty Bug Bounty Space Keynote: A Look at My Journey](https://www.youtube.com/watch?v=jnS687-5rqM)