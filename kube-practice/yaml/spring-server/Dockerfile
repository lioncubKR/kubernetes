#JDK17の配布が終了したため、amazoncorrectto:17を使用
FROM amazoncorretto:17

COPY build/libs/*SNAPSHOT.jar app.jar

ENTRYPOINT ["java" , "-jar" , "/app.jar"]
