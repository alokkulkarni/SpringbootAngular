# SpringbootAngular
springboot with Angular 2


first change folder location from parent to src/main/webapp

run "ng build" command to build the angular project in dist under webapp

go back to the root folder of the application and execute below command

mvn spring-boot:run or mvn clean package -DskipTests or mvn clean install -DskipTests

in the pom.xml file there is a maven resource plugin added which will copy the compiled frontend static resources from webapp/dist 
directory to target/classess/static folder.

now you can just go to http://localhost:8080 and Hurray !!!!

you will see below output which is default template loaded when execuing angular 2 application

"app Works !!" 

Enjoy and happy Coding !!!
