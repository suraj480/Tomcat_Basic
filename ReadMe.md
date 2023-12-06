# Tomcat
1. Download and install tomcat
2. For using tomcat make sure you have define JAVA_HOME , JRE_HOME and CATALINA_HOME in environment varibale
 ![image](https://github.com/suraj480/Tomcat_Basic/assets/72219318/d59c249f-7366-423f-b40e-9d740c94b490)

3. In cmd goto tomcat folder till bin
4. type command startup.bat
 ![image](https://github.com/suraj480/Tomcat_Basic/assets/72219318/83f054b3-9404-4bde-b9f1-ed63d19ff320)

5. Tomcat will successfully run on http://localhost:8080/  server

# Creating and deploying webApp in tomcat
1. create a maven project  *select catalog as internal in eclipse and artifact id as maven-webapp 
2. In pom.xml define
<!-- https://mvnrepository.com/artifact/javax.servlet/javax.servlet-api -->
< dependency >
    < groupId>javax.servlet< /groupId>
    < artifactId>javax.servlet-api< /artifactId>
    < version>4.0.1< /version>
    < scope>provided< /scope>
< /dependency>

3. Update project
4. run as clean up
5. Build maven and define goal as package
6. Inside target copy war that is created 
7. Now go to apache-tomcat in program-files inside that goto webapps C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps
8. paste that created war.
9. tomcat server user step1. to step 4.(as disccuss in tomcat section)
10. run http://localhost:8080/mavenWeb.explore/ in chrome (/mavenWeb  is war name )
