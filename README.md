# BDD-Cucumber-Gherkin-JAVA-API
A Test scenarios using BDD (Cucumber/Gherkin) and implementation on Java to test an API


I have created a Test Suite that tests all the below API’s using BDD(Cucumber/Gherkin) in Java.

Tools & Technologies:

1.Rest Assured 
2.Cucumber
3.IntelliJ
4.Java
5.postman 

Step 1:


Create New Project in IntelliJ and convert it into Maven Project

Step 2: 

Add required dependency in pom.xml file

Step3:

Under Test - Java

Create Feature package under which Feature files are created 
Create Step Definition package under which Java Class files are created

Step 5:

Under Main – Java

Create a helper package under which “ToDoHelper” java class file is created functions of Get, Put, Post and delete are written.

These functions are called in step definition file.

Step 6:

Write Scenarios in Feature file and Step definitions for each scenario get created automatically 

We can copy the step definition skeleton created by feature file and use it in step definition file and customize our code to execute the Get operation.

When we execute it will return result as 5 scenarios passed

