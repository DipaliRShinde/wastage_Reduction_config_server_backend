FROM openjdk:11

ADD ./target/registration-server-0.0.1-SNAPSHOT.jar /usr/src/registration-server-0.0.1-SNAPSHOT.jar

ADD ./src/main/java/com/stackroute/registrationserver/seedData/charityseed.xlsx /usr/src/charityseed.xlsx

WORKDIR usr/src

ENTRYPOINT ["java","-jar", "registration-server-0.0.1-SNAPSHOT.jar"]