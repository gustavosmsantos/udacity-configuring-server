# udacity-configuring-server

Your README.md file should include all of the following:

## i. The IP address and SSH port so your server can be accessed by the reviewer.
3.93.34.156, ssh port 2200

## ii. The complete URL to your hosted web application.
http://3.93.34.156/

## iii. A summary of software you installed and configuration changes made.
I've installed just the software that were required to start the application: apache and postgresql. The configuration in apache was about configuring the route that apache will respond, redirecting to the python application. In postgresql, i've created the database and user. Besides that, i've setted up the security rules (configuring firewall, and creating linux user).

## iv. A list of any third-party resources you made use of to complete this project.
The only external resource used was the mod_wsgi, for running the python project in apache.
