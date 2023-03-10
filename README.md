# Vprofile_devops_project
This is java app uses various services using various virtual machines. It is done by ,first manual provisioning and the by  automated provisioning. This shows the glimpse of how the work happens  at IT level.

In this, first we have the load balancer for which I used Nginx web server. It's work is ,as soon as the user try to fetch the IP address, It redirect the Request
to our next Service which is "APACHE TOMCAT" service.

"APACHE TOMCAT" is a 'JAVA WEB APPLICATION SERVICE' used to serve all java apps.All the developer code will reside in this service.

After that we have a service called "RABIT MQ" well it is a 'MESSAGING BROKER' basically used to communicate between two or more services.

After that we have the Database service called "MYSQL" which is named as "MARIADB" in rpm based VM.

But before the MYSQL we Have used a "MEMCACHED service". It is a cache. Like we use in the browser.

This completes the format of our app and this the map in itself.
My first HANDS ON project :

1) FROM MANUAL PROVISIONING
2) FROM AUTOMATION 

thank you!
