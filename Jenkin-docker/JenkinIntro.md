## What is Continuous Integration
- Continuous Integration after a code commit, the software is built and tested immediately.
- In a large project with many developers, commits are made many times during a day. With each commit code is built and tested.
- If the test is passed, build is tested for deployment.
- If the deployment is a success, the code is pushed to Production.
- This commit, build, test, and deploy is a continuous process, and hence the name continuous integration/deployment.

## What is Continuous Delivery (CD)?
- Continuous Delivery is a software engineering method in which a team develops software products in a short cycle.
- It ensures that software can be easily released at any time.
- The main aim of continuous delivery is to build, test, and release software with good speed and frequency.
- It helps you to reduce the cost, time, and risk of delivering changes by allowing for frequent updates in production.
  
<img width="792" alt="image" src="https://github.com/Ashujauhari/Jenkin/assets/27730844/02c31a7b-3f17-4016-9214-f3bc668ecd71">

## Difference between Compilation and Continuous Integration
###DB integration
  -  Ensure DB and code in sync
  -  Automated creation of DB and test data.
### Code Inspection
  - Ensures a healthy codebase
  - Identifies problems early and applies best practices
  - Automated Deployment
  - Allows you to release product anytime
  - Continually demo-able state and it is works on any machine
### Document generation
  - Ensure documentation is current
  - Removes burned from the developer
  - Produces build reports and metrics
### Compilation
  - Compilation is the process the computer takes to convert a high-level programming language code into a machine language that the computer able to understand. It ensures a code compiler on every target platform.


## What are Steps of CI?
<img width="808" alt="image" src="https://github.com/Ashujauhari/Jenkin/assets/27730844/3ab24e71-012f-4c13-9059-285ddc3889da">

- Ideally, the build should come from the command line and should not depend on an integrated development environment (IDE).
- The build should happen continuously using a dedicated Cl server, not a cron job.
- CI built should be triggered on every check-in and not just at midnight
- The build should provide immediate feedback and Require no developer effort
- Identify key metrics and track them visually. More importantly, act on them immediately
- 
## What is Jenkins?

- Jenkins is a continuous open-source integration written in Java. 
- It was forked from Hudson Project after a dispute with Oracle. Since the fork, Jenkins has grown to be much more than a continuous integration solution.
- Jenkins is not just a Continuous Integration tool anymore. Instead, it is a Continuous Integration and Continuous delivery tool. You can orchestrate application deployments using Jenkins with a wide range of freely available community plugins and native Jenkins workflows.
- Jenkins also supports GitOps workflows with Jenkins X. 
- It helps you accelerate the continuous delivery pipeline on Kubernetes.

## How does Jenkins work?
- Jenkins is a server-based application and requires a web server like Apache Tomcat to run on various platforms like Windows, Linux, macOS, Unix, etc. To use Jenkins, you need to create pipelines which are a series of steps that a Jenkins server will take.
- Jenkins Continuous Integration Pipeline is a powerful instrument that consists of a set of tools designed to host, monitor, compile and test code, or code changes, like:

- Continuous Integration Server (Jenkins, Bamboo, CruiseControl, TeamCity, and others)
- Source Control Tool (e.g., CVS, SVN, GIT, Mercurial, Perforce, ClearCase and others)
- Build tool (Make, ANT, Maven, Ivy, Gradle, and others)
- Automation testing framework (Selenium, Appium, TestComplete, UFT, and others)

## Jenkins Use Cases
- Continuous Integration: With Jenkins pipelines, we can achieve CI for both applications and infrastructure as code.
- Continuous Delivery: You can set up well-defined and automated application delivery workflows with Jenkins pipelines.
- Automation & Ad-Hoc Tasks: With Jenkins jobs and pipelines, you can automate infrastructure components and perform ad-hoc infrastructure tasks (Backups, remote executions, etc.).

  ## Before and After Jenkin
  <img width="845" alt="image" src="https://github.com/Ashujauhari/Jenkin/assets/27730844/b769ae84-53d1-4475-96c4-561583256257">
## Jenkin Setup 
## Jenking Projects 
### Freestyle - When to Use a Jenkins Freestyle Project?
- An access to the shell or a batch environment propagates a high level of security access for the Jenkins freestyle project. 
- In freestyle project environments, it’s convenient to create a script that instructs a Jenkins freestyle job to FTP a file from one server to another, compile a directory of Java code, or even run a SonarQube test.
- A Jenkins freestyle job can be as powerful and complex as any build job built with a Jenkins pipeline or a Groovy DSL. But the only drawback to freestyle projects is that the user must know how to script all of these actions, and developers need to learn how to manage these scripts.

- Plugins such as Git, Maven, and SonarQube are the preferred way to access resources.
-  And technologically, every developer can write a script to access those resources within a Jenkins freestyle project. However, it is recommended that every developer in the development team should follow the guided security best practices and inhibit from adapting a scripted approach.
  
 #### How to Set up a Build Job in Jenkins
Follow the steps outlined below to set up and run a new Jenkins freestyle project.

Creating a Freestyle Build Job
To set up freestyle projects using Jenkins, we need to ensure that we have Jenkins installed and up and running. Also, it is mandatory to be authenticated as the ‘Admin.’ You can refer to our hands-on Jenkins tutorial to learn more.

Once you have Jenkins up & ready, let us create a Jenkins freestyle job.
Step 1.
1. Get logged on to your Jenkins dashboard through the Jenkins installation path.
2. Unless you have defined a private host, it will be hosted on the localhost at http://localhost:8080.
3. In case your Jenkins is installed in another path, make sure to use the appropriate URL to access the dashboard.
<img width="554" alt="image" src="https://github.com/Ashujauhari/Jenkin/assets/27730844/12008ceb-6178-4443-8de9-74dfb96d82b8">

Step 2. Go to the “New Item” option at the top left-hand side of your main dashboard.
Step 3. On the next screen,

1. Here enter the name of the item you want to create. Let us use the “Hello world.”
2. Select ‘Freestyle project’ as the option for this new Item.
3. Click OK
   <img width="743" alt="image" src="https://github.com/Ashujauhari/Jenkin/assets/27730844/69ef72a1-03e7-4c02-8d0a-24b472f73837">

Step 4. Enter the project details in the General tab, including the name and description of the project that needs to be tested.
Hello Java
- Select Execute shell -> write echo " Hello Jenkin"




<img width="743" alt="image" src="https://github.com/Ashujauhari/Jenkin/assets/27730844/86fbd240-9665-4b31-92ef-1aaa392e19c1">





 
  

