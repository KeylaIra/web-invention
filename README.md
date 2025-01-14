# Simple Website Using Github Pages
Make a simple HTML website and publish it using Github Pages.  

## Setup Website
Step 1 : Install package yg dibutuhkan

    apt install apache2 git -y
    
Step 2: Download Source Code

    git clone https://github.com/tiaradwim1306/simple-web

Step 3: Edit file VirtualHost

    .......
    ServerAdmin webmaster@localhost
    DocumentRoot /var/www/html/simple-web
    .......

Step 4 : 

    a2ensite 000-default.conf
    
Step 5: Restart apache2 

    systemctl restart apache2

Step 6: Access web server

    http://ip_address_server/  

## Result
![image](https://github.com/tiaradwim1306/simple-web/assets/120786669/a12cf73a-0836-4e01-9e7e-d14551cbe4aa)

