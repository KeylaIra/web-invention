# Simple Website Using Github Pages
Make a simple HTML website and publish it using Github Pages.  

## Setup Website
Step 1 : Install package yg dibutuhkan

    apt install apache2 git -y
    
Step 2: Download Source Code

    git clone https://github.com/SonyVansha/invention-2025.git

Step 3: Edit file VirtualHost

    .......
    ServerAdmin webmaster@localhost
    DocumentRoot /var/www/html/invention-2025
    .......

Step 4 : 

    a2ensite 000-default.conf
    
Step 5: Restart apache2 

    systemctl restart apache2

Step 6: Access web server

    http://your_ip_address_server/  

## Result
![alt text](image.png)

