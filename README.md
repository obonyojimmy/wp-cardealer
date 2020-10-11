# wp-cardealer

## stacks

- php-7.4
- LEMP (Nginx, Wordpress)

## Instructions

1. Install LEMP [https://www.tecmint.com/install-lemp-with-phpmyadmin-in-ubuntu-20-04/]
2. Configure LEMP [https://www.tecmint.com/install-wordpress-with-nginx-in-ubuntu-20-04/]

## Misc

- link dev dir to nginx root

```
sudo ln -s  <PATH TO THIS DIR>/wp-cardealer /var/www/html/car.wordpress.example
```

- Create development host entry

```
echo "127.0.0.1  car.wordpress.example" | sudo tee /etc/hosts
```