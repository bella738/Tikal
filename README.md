# Tikal
home drill
Implement ci proccess on spring-petclinic:
To start the project you have to run jenkins file
The jenkins file steps is:
checking repository for 
prepare to start:
    install java
    install git
to start the project type:
git clone https://github.com/spring-projects/spring-petclinic.git
cd spring-petclinic
./mvnw package
java -jar target/*.jar
You can then access petclinic here: http://localhost:8080/




