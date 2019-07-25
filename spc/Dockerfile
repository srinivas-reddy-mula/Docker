ARG version=3.7
FROM alpine:${version}
LABEL Author="SrinivasReddyMula"
ADD  https://naresh-springpetclinicjarfile.s3-us-west-2.amazonaws.com/spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar /springpetclinic.jar
EXPOSE 8080
CMD ["java", "-jar", "spring-petclinic-2.1.0.BUILD-SNAPSHOT.jar"]
