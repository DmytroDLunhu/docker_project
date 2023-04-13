FROM openjdk
COPY . /src
WORKDIR /src
EXPOSE 8001
RUN javac src/main/java/org/example/Main.java
CMD ["java", "Main"]

