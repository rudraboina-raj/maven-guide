# maven-guide
detailed explaination on build tool
Maven-build tool

It is a  build/project management tool

* Build generation

* dependency resolution

* documentation etc.

* Maven uses POM (project Object model) to achieve this.

* when maven Command is given, it looks for " pom.xml" in Current directory.

Maven is a build tool which is used to automate the build process for Java applications.

What is build process?

Downloading the required dependencies, Compiling the project Source code, executing the unit test cases, and packing the project as a jar file or war file. is called build process.

Instead of we are doing this build process manually we can automate by using maven.

maven Software is developed by Apache Organisation and it is free  and open source.

It is developed by using Java and we can use it for java projects build automation. 


What actually Maven do

1.Compile into byte-cade

2.Test (to ensure code functions properly)

3.packaging [app is packaged into Jar or war file for deployment]

Doing all this manually is not scalable this is where build tools come in.

Maven uses an xml based Configuration in the Pom file to manage dependencies and build projects in a structured way.

* As a alternate for a Maren we can use Gradle also. 

Gradle tool is more flexible, and uses groovy  based configuration in a build Gradle file.