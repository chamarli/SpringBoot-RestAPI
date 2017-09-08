# SpringBoot-RestAPI
Implement a Restful API in spring-boot application to upload a file and save it local disk

# Project Files Description:
1. pom.xml: This project is developed by using maven build in tool. with maven we don’t have to worry about dependency injections, project structure and build process. I have loaded all the required jars for spring boot application from spring repo “https://repo.spring.io/libs-release”.
2. Application.java: This is a spring boot app. This let us run the spring appli- cation standalone. This is achieved through the annotation “@SpringBootApplica- tion”
3. UploadingFile.java: This is a service layer for the application. When a rest call is made from the UI, Our service layer will be called and will make appropri- ate rest call based on the URL or method type. In this example I have used only POST method.
4. Index.html: This is simple UI used to upload a file.
