FROM openjdk:8
COPY ./sec/java
WORKDIR /src/java
RUN ["javac","ADD.java"]
ENTRYPOINT ["java","Main"]