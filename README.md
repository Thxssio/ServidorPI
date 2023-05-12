<h1 align="center"> ServidorPI </h1>



**Atualizando pacotes**
```
sudo apt update
```

**Instalando o Servidor em nossa maquina**

```
sudo apt-get install apache2 -y
```

**Instalando as bibliotecas php**
```
sudo apt-get install php libapache2-mod-php -y
```

**Instalando o Gerenciador do nosso bando de dados**
```
sudo apt-get install mariadb-server
```
**Instalando o bando de dados**
```
sudo mysql_secure_installation
```
**Conectando o banco de dados com php**
```
sudo apt install php-mysql
```
**Resertando o serviço para aplicar as configuraçoes**
```
sudo service apache2 restart
```
