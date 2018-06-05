**Assignment1:**

1.  Install Nginx

[root\@amar \~]\# yum install epel-release -y

[root\@amar \~]\# yum intsll nginx

[root\@amar \~]\# \~]\# chkconfig nginx on

[root\@amar \~]\# service nginx restart

<https://github.com/amarchauhan7866/Jenkin_Media_Day3/blob/master/day41.png>

Install below listed plugins

Installed the ssh plugin

Git plugin already installed in Jenkins

Changed the Jenkins user login shell manually

https://github.com/amarchauhan7866/Jenkin_Media_Day3/blob/master/day42.png

Check Global configuration and provide SSH remote host(root) details.

https://github.com/amarchauhan7866/Jenkin_Media_Day3/blob/master/day43.png

Assignment3:

Created a tag creator Jenkins Job

Job will create tag on your forked repo.

Job should accept 2 parameters

SRC_BRANCH

TAG_NAME

https://github.com/amarchauhan7866/Jenkin_Media_Day3/blob/master/day44.png

1.  Sync your forked jenkins repo
    with <https://github.com/ot-training/jenkins.git> (using multiple remote).

Assignment5:

https://github.com/amarchauhan7866/Jenkin_Media_Day3/blob/master/day45.png

Installed tomcat7

[root\@localhost tmp]\# wget
<http://www-us.apache.org/dist/tomcat/tomcat-7/v7.0.88/bin/apache-tomcat-7.0.88.tar.gz>

tar xzvf apache-tomcat-7.0.88.tar.gz

[root\@localhost \~]\# cd /usr/local/tomcat7/apache-tomcat-7.0.88/bin/

[root\@localhost bin]\# ./startup.sh

Using CATALINA_BASE: /usr/local/tomcat7/apache-tomcat-7.0.88

Using CATALINA_HOME: /usr/local/tomcat7/apache-tomcat-7.0.88

Using CATALINA_TMPDIR: /usr/local/tomcat7/apache-tomcat-7.0.88/temp

Using JRE_HOME: /usr

Using CLASSPATH: /usr/local/tomcat7/apache-tomcat-7.0.88/bin/bootstrap.jar
:/usr/local/tomcat7/apache-tomcat-7.0.88/bin/tomcat-juli.jar

Tomcat started.

**Installed mysql**

[root\@amar \~]\# yum install mysql-server

[root\@amar \~]\# chkconfig --levels 235 mysqld on

[root\@amar \~]\# service mysqld start

[root\@amar \~]\# mysql_secure_installation

Set the root password

Remove anonymous users? [Y/n] y

Disallow root login remotely? [Y/n] y

... Success!

Remove test database and access to it? [Y/n] y

\- Dropping test database...

... Success!

\- Removing privileges on test database...

... Success!

Reload privilege tables now? [Y/n] y

... Success!

Cleaning up...

All done! If you've completed all of the above steps, your MySQL

installation should now be secure.

Thanks for using MySQL!

[root\@amar \~]\#

https://github.com/amarchauhan7866/Jenkin_Media_Day3/blob/master/Jenkins_6.png

**Create a job Spring3HibernateApp-deployment**
