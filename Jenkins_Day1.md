-   Install Jenkins using package.

Fristly Install the java 1.8

wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3
A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" http://downl
oad.oracle.com/otn-pub/java/jdk/8u171-b11/512cd62ec5174c3487ac17c61aaa89e8/jdk-8
u171-linux-x64.tar.gz

tar -xzvf jdk-8u171-linux-x64.tar.gz -d /opt/

cd jdk-8u171-linux-x64.tar.gz /opt/

![](media/182cb7c21a67a299a5e86fbd8bd43e46.png)

Now Installed the Jenkins

wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat/je
nkins.repo

![](media/300fdcb38bb675d46ec9db2e1684aca9.png)

![](media/c860eb8b6066a30064012bad318d0c4c.png)

Stop the Jenkins service and now installed the tomcat server

wget http://www-us.apache.org/dist/tomcat/tomcat-8/v8.5.31/src/apache-tom
cat-8.5.31-src.tar.gz

![](media/3f52e37ec92ba6404a4b4b7e8dc8ae0a.png)

Download the War File

wget <http://mirrors.jenkins-ci.org/war/latest/jenkins.war>

Deployed the war file

cp jenkins.war /opt/apache-tomcat-8.5.31/webapps/.

**Install any five plugin and use them**

![](media/1b077e43f7dc3a1b700b22f773c6b260.png)

Assignment2:

-   Installed a plugin manually.

>   Created a free style job installed the maven 3.2.5 manually

**Assignment3:**

![](media/9501ccc77b83ff017162a0522110e3ab.png)

![](media/6793e4ca42caa0c11f984264d7623bc3.png)

![](media/c4f6a84d4f4ff087d0659e9a6aa22bb6.png)
