# spring-cloud-config-server

---------------------------------------
Application	                         Port
Limits Service	                   8080, 8081, ...
Spring Cloud Config Server	       8888
Currency Exchange Service	       8000, 8001, 8002, ..
Currency Conversion Service	       8100, 8101, 8102, ...
Netflix Eureka Naming Server	   8761
Netflix Zuul API Gateway Server	   8765
Zipkin Distributed Tracing Server  9411

----------------------
Create a folder (git-localconfig-repo) -> git init
View Project in Package Explorer Mode -> Build Path -> Link Source -> browse to git-localconfig-repo -> Finish
create file limits-service.properties (limits-service application name)

Go to  git-localconfig-repo and open Git Bash -> Run following commands
git add -A
git commit -m "first commit"

Right click on git-localconfig-repo -> properties -> Resource -> Copy location and put in spring-cloud-config-server.properties file
http://localhost:8888/limits-service/default