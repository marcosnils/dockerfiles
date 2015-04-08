FROM makuk66/docker-oracle-java7

MAINTAINER Marcos Lilljedahl, marcosnils@gmail.com

RUN wget -O- http://dynamodb-local.s3-website-us-west-2.amazonaws.com/dynamodb_local_latest | /bin/tar xz

ENTRYPOINT ["/usr/bin/java", "-Djava.library.path=./DynamoDBLocal_lib", "-jar", "DynamoDBLocal.jar"]

CMD ["-help"]
