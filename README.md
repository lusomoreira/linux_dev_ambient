# linux_dev_ambient

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Neste repositório contem as configurações iniciais de um ambiente de desenvolvimento em LINUX.

  - Instalação do VSCODE
  - Configuração do PHP
  - Instalação e Configuração do MYSQL
  - Instalação do MYSQL WORKBENCH
  - Alguns comandos principais para start e stop de serviços.

# Instalação do VSCODE

  - Baixar pacote .DEB no site oficial (https://code.visualstudio.com/)
  - Executar pacote .deb

### Observações
> é possivel sincronizar as extensoes do VSCODE,
basta utilizar a sincronização via github.

# Configuração do PHP

```sh
$ sudo apt-get update

$ sudo apt-get install apache2 php libapache2-mod-php

$ sudo apt-get install php-soap php-xml php-curl php-opcache php-gd php-sqlite3 php-mbstring php-mysql

```

# Instalação e Configuração do MYSQL

### Comandos utilizados:
```sh
$ sudo apt update
$ sudo apt upgrade
$ sudo apt mysql-server mysql-client
$ service mysql status

- OBS: 
- Para alterar a senha do root executar os dois comandos abaixo.

$ sudo mysql -uroot -p
$ ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'suasenha';
```

# Instalação do MYSQL WORKBENCH

  - Baixar pacote .DEB no site oficial (https://dev.mysql.com/downloads/workbench/)
  - Executar pacote .deb
 
### Observação:
> Apos instalar basta abrir o programa, cliar com o direito na conexao localhost e editar. Então coloque a senha correspondente ao root.


# Alguns comandos principais para start e stop de serviços

```sh
$ sudo /etc/init.d/apache2 start

$ sudo /etc/init.d/apache2 stop

```



