# loadBalancerWithSpringBoot
Here I am running 2 instance of a rest App ( on diff ports)  and then load balancer is discovering the instances using eureka server 

gradlew bootRun -Dorg.gradle.java.home="C:\Program Files\Java\jdk-17" --args="--server.port=8080"
F:\Personal\Projects\microservices\rest-app
gradlew bootRun -Dorg.gradle.java.home="C:\Program Files\Java\jdk-17" --args="--server.port=8081"
