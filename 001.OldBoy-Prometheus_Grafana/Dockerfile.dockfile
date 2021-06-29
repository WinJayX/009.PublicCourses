FROM centos:7

ADD spring-cloud-eureka-0.0.1-SNAPSHOT.jar /opt/spring-cloud-eureka-0.0.1-SNAPSHOT.jar

RUN yum install java-1.8.0-openjdk* -y

WORKDIR /opt

EXPOSE 8761

CMD java -jar spring-cloud-eureka-0.0.1-SNAPSHOT.jar
