# jboss-sample
Running an application on JBoss EAP 7.3.0

- Download latest JBoss EAP from here https://developers.redhat.com/products/eap/download
- Install it
- Open the folder where you installed JBoss
- Go to bin folder and run `standalone.bat` file
- Clone this repo and inside this project folder, type command `mvnw clean package`
- Go to `target` folder and copy the `.war` file and paste on your desktop.
- Open any browser and Open `127.0.0.1:8080`
- It will ask username and password that you provided while installing JBoss
- Go to Deployment tab and upload the `.war` file.
- After deployment it will show the Context root url.
- On clicking the url it will open the application.

reference: https://dzone.com/articles/deploying-spring-boot-app-to-jboss-wildfly
