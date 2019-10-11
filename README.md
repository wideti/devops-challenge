Wide Software - DevOps Challenge
Bem vindo ao teste de DevOps da Wide.
Recebemos uma estória de usuário do nosso time de marketing para auxiliar em uma nova campanha do nosso produto.
Em um brainstorm o time chegou à conclusão que para ter maior eficácia será necessário criar dois sites distintos, um para leads do setor alimentício e outro para leads do setor de eventos.
A estória diz o seguinte:
“Como administrador de marketing, preciso conseguir escolher qual versão do site será disparado para nossa base de leads.”
Desta forma o time de desenvolvimento já preparou a plataforma de marketing para receber duas URL's e desta forma o pessoal do marketing poderá optar por uma ou por outra.
Sua missão é entregar duas versões do site em URL's distintas. Abaixo um desenho da arquitetura proposta pelo time de tecnologia:

Requisitos
Fazer o deploy de 2 Wordpress no EKS.
Ao acessar /alimenticio, o acesso será redirecionado para wordpress_ali. 
Ao acessar /evento, o acesso será redirecionado para wordpress_eve.
O endereço DNS deverá ser utilizado o do ELB mesmo.
O banco de dados (MySQL) deverá estar em cluster e também no EKS.
Será necessário configurar o Prometheus e mostrar alguma métrica do Wordpress.
O que avaliaremos?
Arquivos .yml
Monitoramento no Prometheus
Volumes persistentes no banco de dados
Será um diferencial
Autoscaling dos Pods
Backup
Segurança
 
Compartilhe o seu código conosco via GitHub (público).


