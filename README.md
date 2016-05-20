# tomcat8-alpine-oraclejdk8

Slim image for Tomcat8 using OracleJDK 8 and Alipine Linux.

Example:
```
docker run --name tomcat -d -p 8080:8080 -v /home/user/workspace/:/usr/local/apache-tomcat-8.0.35/webapps tomcat8-alpine-oraclejdk8
```
