From openjdk
WORKDIR user/lib

ENV MONGO_DATABASE=todotrackerArchivedb
ENV MONGO_URL=mongodb://localhost:27017/todotrackerArchivedb

ADD ./target/ArchieveService-0.0.1-SNAPSHOT.jar  /usr/lib/ArchieveService-0.0.1-SNAPSHOT.jar

#run the jar file
ENTRYPOINT ["java","-jar","ArchieveService-0.0.1-SNAPSHOT.jar"]