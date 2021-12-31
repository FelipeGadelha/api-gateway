FROM openjdk:11

ARG CONVERT_PROFILE
ENV CONVERT_PROFILE=${CONVERT_PROFILE}

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
CMD java -jar /app.jar --spring.profiles.active=${CONVERT_PROFILE}