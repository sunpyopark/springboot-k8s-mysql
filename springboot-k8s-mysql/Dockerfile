FROM adoptopenjdk/openjdk11:alpine-jre
ADD springboot-k8s-mysql/target/springboot-k8s-mysql-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
