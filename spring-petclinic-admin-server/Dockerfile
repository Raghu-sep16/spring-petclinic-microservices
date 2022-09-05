FROM openjdk:8-jdk-alpine
# Environment Variable that defines the endpoint of sentiment-analysis python api.
ENV SA_LOGIC_API_URL http://localhost:5000
ADD target/spring-petclinic-admin-server-2.6.7.jar /
EXPOSE 8080
CMD ["java", "-jar", "spring-petclinic-admin-server-2.6.7.jar", "--sa.logic.api.url=${SA_LOGIC_API_URL}"]

#this is test line for git test
