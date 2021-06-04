# Project Specification
- Introduction about WAMPSERVER
- Introduction about WORDPRESS
- Create a new website for an existing website which is not built with WORDPRESS


# WampServer  
- Go to: https://www.wampserver.com/ and download the installer  
- In case of issues, go to: https://wampserver.aviatechno.net/, download the tool to analyse issues and patch them, or go at the bottom of the page and download the zip file containing all files and install them one by one
- Launch the WampServer, you have to see the logo in green in your services:    
![image](https://user-images.githubusercontent.com/61125395/120862671-a129e180-c589-11eb-9927-b517dd4fab6b.png)
- Check WordPress pre-requisities to see which versions of PHP and SQL you need, change it if necessary:  
![image](https://user-images.githubusercontent.com/61125395/120863034-31682680-c58a-11eb-9d31-b948da326fdf.png)  
- Develop your website in "www" repo of your wampserver to get acces to the server  
- To ease your website access, crete a VirtualHost from localhost:  
![image](https://user-images.githubusercontent.com/61125395/120864060-e5b67c80-c58b-11eb-83b5-14e101c1e243.png)  
- Restart your DNS service to enable your VirtualHost (right click on icon):  
![image](https://user-images.githubusercontent.com/61125395/120864238-30d08f80-c58c-11eb-9fad-b58832b274d3.png)  


# WordPress
* Go to: https://fr.wordpress.org/download/ and download the zip file
* Unzip the WordPress zip file into "www" repo of your WampServer  
* Launch PhpMyAdmin from your localhost (For windows users, login is "root" and password is empty ""  
![image](https://user-images.githubusercontent.com/61125395/120865285-07b0fe80-c58e-11eb-86e5-fedfec6ce10a.png)  
* Create a new database, choose the name you want and choose (utf8-general-ci) as encoding
![image](https://user-images.githubusercontent.com/61125395/120865664-c2d99780-c58e-11eb-8a8e-97246c1acd5a.png)  
* Install WordPress, go to: http://localhost/<your-site-name\>, and fill the forms with necessary informations, once it's done you have the see the back-office, and you are ready to build your website! Choose your theme, and necessary plugins, and enjoy it!  
![image](https://user-images.githubusercontent.com/61125395/120866019-6f1b7e00-c58f-11eb-856a-7c1bd6f99ac8.png)


# Create a new website 
* I choosed https://www.pepinieres-baches.com/baches/ as reference to re-build for my project, this is an eCommerce website, selling different types of citruses plants and seeds 
![image](https://user-images.githubusercontent.com/61125395/120866588-90309e80-c590-11eb-8d7f-c10df16242e2.png)
* You can check if the website was built using WordPress or not by seeing the source, check if you have any prefix "wp-"
* I choosed "Blossom Recette" as Theme  
![image](https://user-images.githubusercontent.com/61125395/120867266-dd614000-c591-11eb-832e-7a83f84ce029.png)  
* For Plugins I installed "Contact Form 7" for my contact form, and "WooCommerce" to have necessary eCommerce items, like user accounts, shops, carts  
* The old website had only static pages, they dont differentiate posts and pages, by introspecting  the website I've seen that they have many posts takling about plants and stories about them, for my new website I choosed to create posts and pages instead of keeping only pages.  
* I choosed also some free and modern pictures to illustrate the posts  
* About the menu, the old site had many items




* Code reference: https://codex.wordpress.org/Function_Reference
* download: https://fr.wordpress.org/download/#download-install
* wordpresss
    login: 	pras <br>
    pass: 	BBzLsSLP)2EHX0O*R2 <br>
    mail: 	pptech.ds@gmail.com <br>

# SQL database
* from wampserver homepage click on "phpmyadmin"
* for windows users: login=root / pass=<empty>
* create new database
    
# Projet 1
* Rebuild an existing website, which is not built in WordPress
* Check in page source of website if any "wp-" is define, to see if the website is built in WordPress or not
* I choosed "https://www.pepinieres-baches.com/baches/"
    
# For CSS
* Use bootstrap framework to use most common CSS used on web: https://getbootstrap.com/   

# For Icons
* Use: https://fontawesome.com/
    
# Check synthaxes
* https://validator.w3.org/
 
