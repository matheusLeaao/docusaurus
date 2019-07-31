---
id: doc1
title: Documentação Comandos Linux
sidebar_label: Comandos úteis de Linux
---



## Comandos Util Linux

Criar diretórios
```
mkdir <nome>
```

Mostrar os processos que estão rodando com o PID
```
top
```

Mostrar os processos como se fosse um gerenciador de tarefas do Linux
```
htop
```

Descobrir o IP
```
curl ifconfig.me
```

Para acessar um servidor via SSH

```
ssh -i  <chave ppk pu pem>  user@<ip de conexão ou end privado>
```

Na conexão, mostra quais portas estão em uso

```
netstat -plntu
```

Mudar o owner e permissões para o Arquivo

```
chmod <soma> <nome_do_arquivo>
```

## Regras Permissões


    4 = read

    2 = write 

    1 = execute

Usamos a soma para utilizar o comando chmod
EX: 
```
chmod 777 <nome_do_arquivo>
```
Permissão de root em relação ao arquivo escolhido

## Utilizando comandos no Banco de Dados

Criando usuário MySQL
```
CREATE USER user@localhost;
```

Criando senha para usuário MySQL
```
SET PASSWORD FOR user@localhost=password("Senha");
```

Definindo privilégios para usuarios do banco

```
GRANT ALL PRIVILEGES ON database.* TO user@localhost;
FLUSH PRIVILEGES;
```

Realiza determinada atividade com o serviço descrito no cod
```
sudo systemctl <status/restart/stop> <service name>
```

