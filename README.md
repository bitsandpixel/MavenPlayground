# Maven Playground

* [General Information](#general-information)
* [What When How](#what-when-how)
* [Random Notes](#random-notes)
* [Referred Links](#referred-links)

## General Information

* Apache Maven is a build automation tool that is based on POM (Project Object Model). It is used primarily for Java projects. It can also be used to build and manage projects written in C#, Ruby, Scala, and other languages.
* Maven is used for projects build, dependency and documentation. It takes care of the process of including the jar and dependency packages when we want to connect with other entities of the developing environment and it deals with how the software is built.
* Maven is very helpful for a project while updating central repository of JARs and other dependencies.
* Using maven we can easily integrate our project with source control system (such as Subversion or Git).


## What When How
### When should someone use Maven
  * One can use the Maven Build Tool in the following condition:
      * When there are a lot of dependencies for the project. Then it is easy to handle those dependencies using maven.
      * When dependency version update frequently. Then one has to only update version ID in pom file to update dependencies.
      * Continuous builds, integration, and testing can be easily handled by using maven.
      * When one needs an easy way to Generating documentation from the source code, Compiling source code, Packaging compiled code into JAR files or ZIP files.

* Core concepts of Maven
    * POM (Project Object Model)
        * Contains the metadata of the project
        * Responsible for managing dependencies
        * To configure plug-ins which helps us in automating repetitive tasks.
    
        * **<project>** is top level tag in a pom.xml file, which encapsulates all the information related to our maven
            project
        * **<modelVersion>** represents the version of pom you are using. for maven verison 3, pom version is always
            set as 4.0.0
        * **<groupId>** is the unique identifier of the project
        * **<artifactId>** is the name of the project
        * **<version>** is a unique number which identifies the version of our artifact. 
        
        * Different types of pom files
            * Simple POM - will be in the project
            * Super POM - will be in the installation directory 
            * Effective POM - a combination of simple and super POM files. 
                * to see Effective POM open the maven terminal and run the command mvn help:effective-pom 
    
## Random Notes
* **? core concepts of maven refer(2nd url)**
## Referred Links:
* https://www.youtube.com/watch?v=dqJanLvjDqc&t=2s
* https://www.geeksforgeeks.org/introduction-apache-maven-build-automation-tool-java-projects/
