# WordPress Installation Commands

## Update Packages

```bash
sudo apt update && sudo apt upgrade -y
```

## Install Apache

```bash
sudo apt install apache2 -y
```

## Install MariaDB

```bash
sudo apt install mariadb-server mariadb-client -y
```

## Install PHP

```bash
sudo apt install php php-mysql libapache2-mod-php php-cli php-curl php-gd php-xml php-mbstring unzip -y
```

## Restart Apache

```bash
sudo systemctl restart apache2
```
