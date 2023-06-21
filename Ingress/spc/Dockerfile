FROM ubuntu:22.04
RUN apt update
RUN apt install openjdk-17-jdk -y
RUN apt install wget -y
RUN wget https://referenceapplicationskhaja.s3.us-west-2.amazonaws.com/spring-petclinic-2.4.2.jar
EXPOSE 8080
CMD ["java" , "-jar" , "spring-petclinic-2.4.2.jar"]