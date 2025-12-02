**# mavenweb
in order to this jenkins piple line we need to deploy some plugin like 
1.maven intergration
2.copy articafts
3.deploy to container
4.piple line build
5.pipeline utility
then follow the steps as given document
and configure jenkins
1.java
2.maven
3.git for this project
hi hello
webhook trigger  t jenkins......


docker build -t mywebapp .

docker run -p 8080:8080 mywebapp




maven web project 1234
Go to Eclipse
Create a Maven Project → File → New → Maven Project!
Select Create a simple project (skip archetype selection) and click Next!
Give Group Id and Artifact Id of your choice
Set Packaging = war and click Finish, Maven Web Project is created!
In the created project, check project structure:
src/main/java for Java files
src/main/webapp for JSP & WEB-INF folder
Right click on your project and Run As → Maven Clean - It clears out the existing classes that you compiled from last compile!
Check the console for Build Success!
Right click on your project and Run As → Maven Install - to create WAR file inside target folder!
Check the console for Build Success!
Now create a JSP file inside src/main/webapp → index.jsp
Write a simple Hello World text in JSP!
Now Run the Project on Server → Right click → Run As → Run on Server   (open windows show views -> server -> select tomcat v9.0)
Select Tomcat Server → Click Finish!
In browser we can view the output of the project on:
http://localhost:8080/your-artifact-id

Next is to push the project into GitHub, for this, create a new repository in GitHub!
Click on Create repository!
Copy the HTTPS URL as shown to be copied into Git Bash!
Open Git Bash to push the project into GitHub!
Make project as working directory by:
git init
Now add files:
git add .
Now commit:
git commit -m "first commit"
Now add remote:
git remote add origin https://github.com/username/mavenweb.git
Check remote:
git remote -v
Push to GitHub:
git push -u origin main
