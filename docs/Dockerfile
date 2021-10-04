# Adds javaJDK to Docker
#FROM openjdk:11

#Will copy file from EC2 to image's file system
#COPY ./Main1.class /usr/Main1.class

#Set current directory
#WORKDIR /usr

#Do something
#CMD java Main1



#FROM openjdk:11

#ARG JAR_FILE=target/HiWeb-0.0.1-SNAPSHOT.jar

#COPY ./HiWeb-0.0.1-SNAPSHOT.jar /usr/HiWeb-0.0.1-SNAPSHOT.jar

#EXPOSE 8080

#ENTRYPOINT ["java","-jar","HiWeb-0.0.1-SNAPSHOT.jar"]


#FROM openjdk:11


#COPY ./HiWeb-0.0.1-SNAPSHOT.jar /usr/HiWeb-0.0.1-SNAPSHOT.jar


#WORKDIR /usr

#EXPOSE 8080


#ENTRYPOINT ["java","-jar","db_hw-0.0.1-SNAPSHOT.jar"]












FROM openjdk:11


COPY ./db_hw-0.0.1-SNAPSHOT.jar /usr/scripts/db_hw-0.0.1-SNAPSHOT.jar


WORKDIR /usr/scripts

EXPOSE 8080


ENTRYPOINT ["java","-jar","db_hw-0.0.1-SNAPSHOT.jar"]









