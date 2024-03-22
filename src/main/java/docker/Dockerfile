FROM  openjdk:8
VOLUME /home/fishexam
ADD fishexam.jar fishexam.jar
ADD application.yml application.yml
EXPOSE 8888
ENTRYPOINT ["java","-jar","/fishexam.jar" , "--spring.config.location=/application.yml"]