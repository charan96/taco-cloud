# Notes

## Spring
1. For the templates, any template engine can be used; Thymeleaf is common but for a Jinja-style template, use Mustache. JSP can be used and it doesn't need any dependency since it ships out with Tomcat. However, Tomacat/Java Servlet looks for JSPs under /WEB-INF. But, if you're building your application as an executable JAR file, there's no way to satisfy that requirement. So, JSP is only an option if you're building your application as a WAR file and deploying it in a tradition servlet container.  
2. WAR files are usually used for web applications but we use a JAR file for this application since deploying the code is easier with a JAR file.
3.   