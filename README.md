# sample-repo
This repository has been created for DevOps-Engineer test.

It has a simple java program that will print "Hello World! My name is Tarun Sharma" as soon as the program  is executed.

	sample-repo/
	|-- src/main/java/
	|		--hello-world/
	|			--Main.java
	|			--Test.java
	|--target/
	|-- pom.xml
	|-- READ.md

This repository is integrated with jenkins to create a pipeline.
-Whenever there is any push in the master branch, the pipeline will be triggered
-code will be compiled using "mvn compile"
-test build will be triggered to run "mvn test"  
-the latest build should get copied to the mentioned path(a folder will be created named the timestamp) with timestamping.




