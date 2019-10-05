# Linux Server Configuration
##### SSH Access: 
IP Address: `35.182.37.84`
Port: `2200`

##### Items Catalog Application:
URL: `http://35.182.37.84/itemscatalog/`

##### Project Summary:
For this project I configured a Lightsail Linux server using the Ubuntu operating system. Software installed on this server included a PostgreSQL database and a WSGI application. The WSGI application included the installation of virtualenv for environment configuration, Flask as the application framework and a sqlite database instance as the application backend. A UFW firewall was configured to limit server access via a select number of ports, as described in the project requirements. A new user was also added to the server, as described in the project requirements. 

##### Third Party Resources:
WSGI Application installation: `https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps`