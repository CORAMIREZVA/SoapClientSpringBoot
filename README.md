## Spring Boot SOAP client

This is an example project to demonstrate how to connect to SOAP web services from a Spring Boot component.

This is a SOAP service which converts numbers to words, exposing this function through a REST controller.

### Build & run

This project was built with Intellij Idea. So, to build and run this project, execute following commands:

    git clone https://github.com/CORAMIREZVA/SoapClientSpringBoot.git
    ./mvnw package
    cd target
    java -jar soap-client-0.0.1-SNAPSHOT.jar

To test, just point your browser to:

    http://localhost:8080/num2words/80

This should show something like:
    Eighty
Any comment please write me to camilorava@gmail.com
