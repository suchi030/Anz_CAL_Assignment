# Anz_CAL_Assignment
Calculator page 
##Cucumber-BDD-Automation-Framework

#Behavior Driven Development Cucumber - Selenium-Cucumber-Maven framework with Page Object Model. It is a Java based framework.

##The source structure of Maven Project:

	#src/main/test/java/Features: feature file (all test scenarios)
	#src/main/test/java/Pageobjectrepo:  calculator page elements and methods (POM)
	#src/main/test/java/Stepdefinitions: glued code with feature file
	#src/main/Resources: Browser’s file

##Prerequisite to setup 

	#Install java and set up environment variable 
          #JAVA_HOME-C:\Program Files\Java\jdk-16.0.2
          #java Path-%JAVA_HOME%\bin
	#install maven and set up environment variable 
   		#M2_HOME-C:\Program Files\apache-maven-3.8.1
   		#MAVEN_HOME-C:\Program Files\apache-maven-3.8.1
   		#Path-%M2_HOME%\bin
  #POM XML- Set up Configuration file with all dependencies and MAVEN build
	#Current version of framework works well on Windows10
	#For best results use Chrome browser
   

 ##How to Run the Project 
   		# Clone the project repository from github from weblink.
   		# import the project in eclipse as maven project.
      # Open command line prompt cmd and traverse to the root folder of your maven project.
   		# Run command "mvn clean".
   		# Run command "mvn Test" to execute.
 
 
 ##How to verify test reports
   	  #Maven Test will generate the surefile-reports at following path
     	Anzcalculator\target\surefire-reports

      #HTML reports will be generated at following
       path /anzcalculator/target/HtmlReports 
