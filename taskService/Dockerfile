From openjdk
WORKDIR user/lib

ENV MONGO_DATABASE=todotrackerdb
ENV MONGO_URL=mongodb://localhost:27017/todotrackerdb

ADD ./target/taskService-0.0.1-SNAPSHOT.jar  /usr/lib/taskService-0.0.1-SNAPSHOT.jar

#run the jar file
ENTRYPOINT ["java","-jar","taskService-0.0.1-SNAPSHOT.jar"]