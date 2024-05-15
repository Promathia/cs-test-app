locally I used Java 17 (for example jdk-17.0.8)

mvn clean package

LOCAL:
"C:/Program Files/Java/jdk-17.0.8/bin/java.exe" -jar aemaacs-0.0.1-SNAPSHOT.jar
Request:
http://localhost:8081/api/v1/health

SERVER (start as a service):  
...  
...  
Request:
http://{{server_domain}}:8081/api/v1/health


-> observe 200 Success