# WordPress Deployment on AWS EC2

## Project Overview

This project demonstrates deployment of a WordPress application on an AWS EC2 instance using:
- Apache
- PHP
- MariaDB
- Ubuntu EC2

## AWS Services Used

- EC2
- Security Groups
- VPC

## Deployment Steps

1. Launched Ubuntu EC2 instance
2. Configured Security Groups
3. Installed Apache
4. Installed MariaDB
5. Installed PHP
6. Configured WordPress
7. Connected WordPress with MariaDB

## Challenges Faced

### Apache Default Page Issue
Resolved by removing index.html.

### Database Connection Issue
Resolved by fixing duplicate DB configuration in wp-config.php.
