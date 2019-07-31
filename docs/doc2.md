---
id: desafios
title: Desafio DevOps
---
&nbsp;

*Os links com " * " não estão disponíveis ainda

## Nível Stagg
### Desafio Linux I
Este desafio tem como objetivo o desenvolvimento das habilidades em ambientes Linux multi-distribuição.

#### Missão:

O DevOps deverá implementar o seguinte cenário:


* 1 Servidor Linux CentOs com webserver Nginx instalado;
* 1 Servidor Linux Ubuntu com banco de dados Mysql com uma base de dados chamada "teste_database";

O ambiente pode ser implementado utilizando-se de Máquinas Virtuais ou Instâncias lançados em alguma cloud de sua preferência, porém é necessário que as 3 máquinas estejam acessíveis de um notebook cliente e não apenas localmente.

### Desafio Linux II
Este desafio tem como objetivo o desenvolvimento das habilidades em Redes de computadores em cloud e implementação de uma primeira aplicação baseada em Front/BackEnd + Banco de Dados.

#### Missão:

O DevOps deverá implementar o seguinte cenário:

* 1 Servidor CentOs com Zabbix server instalado sem o banco de dados local;
* 1 Servidor  Debian com banco de dados MySql para utilização do Zabbix Server;
Após a finalização do Zabbix Server com banco de dados configurado, deverá ser inserido as duas máquinas do Desafio Linux I no monitoramento do Zabbix, os itens a serem monitorados são:
  * Cpu;
  * Memória;
  * Disco;
  * Serviço do Nginx;
  *  Serviço do MySql;

O ambiente pode ser implementado utilizando-se de Máquinas Virtuais ou Instâncias lançados em alguma cloud de sua preferência, porém é necessário que as 3 máquinas estejam acessíveis de um notebook cliente e não apenas localmente.

### Desafio Cloud I
Este desafio tem como o objetivo o desenvolvimento das habilidades em Cloud Computing utilizando-se da plataforma AWS neste primeiro desafio, inserindo um pouco o contexto de rede em Cloud com a virtualização das máquinas.

#### Missão:

O DevOps deverá implementar o seguinte cenário:

*  1 Servidor CentOs com IP Elástico na AWS;
   *  O Servidor deve ser acessível apenas do IP Público de navegação da Mandic unidade Haddock;
*  1 RDS MySQL;
   * O RDS Não deverá ter acesso público, ou seja deve ser acessível apenas via rede interna da AWS;

O bloqueio e liberação de acesso deve ser feito no Security Group de cada recurso (ec2 instance e rds mysql)

Ao final do desafio o DevOps deverá acessar o RDS via servidor CentOs;
### Desafio Docker *
### Desafio IAC *
### Desafio CI/CD *

## Nível Junior *
### Desafio Linux
### Desafio Cloud
### Desafio Docker
### Desafio IAC
### Desafio CI/CD

## Nível Pleno
### Desafio Linux *
### Desafio Cloud *
### Desafio Docker

Este desafio tem como objetivo desenvolver as habilidades do DevOps em tecnologias de container atuais e utilizadas em diversos clientes com niveis maiores e menores de complexidade.

#### Missão:

O DevOps deverá implementar um ambiente de gerenciamento de containers, um servidor para registry das imagens Docker, e 3 containers contendo serviços diferentes e públicos.

* 1 Servidor para Registry;
* 1 Cluster Kubernetes com 1 master e 3 nodes;
* 3 Containers com serviços públicos (WebServer, Redis etc.)

A escolha do método de implementação do Cluster Kubernetes, a Cloud que hospedará os recursos, o serviço de registry, e os 3 containers com serviços públicos ficarão a cargo do DevOps.

O Resultado final é as imagens dos containers inseridas e sendo utilizadas pelo Registry interno, os containers rodando e sendo acessíveis publicamente.

### Desafio IAC I

Este desafio tem como objetivo melhorar as habilidades em Infraestrutura como código do DevOps, e fazê-lo desenvolver um case mais complexo que envolva tanto infraestrutura de aplicação, rede, como as melhores práticas de Infraestrutura como Código.

#### Missão:

O DevOps deve subir uma aplicação Web que utilize banco de dados como parte de sua estrutura utilizando da arquitetura de sistemas distribuídos, essa aplicação deve estar com seu frontend atrás de um Application LoadBalancer na AWS, o seu banco de dados deve ser um banco de dados relacional como serviço na AWS.

* Application Load Balancer :

* Listener HTTP/HTTPS

* Rules baseadas em http header 'HOST'

* Retorno Fixo (200 status code);

* RDS :

* Relacional;

* Multi-Az;

* Route53 :

* Dns interno para aplicação Web;

Toda a insfraestrutura deve ser configurada e implementada com ferramentas de Infraestrutura como código, quer seja terraform, cloudformation ou similar para infraestrutura (máquinas e serviços), quer seja ansible, saltstack, puppet ou similar para configuração da aplicação Web.

A escolha da aplicação web e sgbd do RDS ficará a cargo do DevOps escolher.

Ao final do Desafio o DevOps deverá apresentar uma Talk pro time, explicando a arquitetura e mostrando o código do Terraform e Ansible (Máximo 1H)

### Desafio CI/CD *

## Nível Sênior *
### Desafio Linux
### Desafio Cloud
### Desafio Docker
### Desafio IAC
### Desafio CI/CD
