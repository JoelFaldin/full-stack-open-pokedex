Language chosen: Java!
There are multiple options when it comes to linting in Java. Some of the most popular tools are CheckStyle, Spotbugs, SonarLint and Google Java Format.
In the testing area for Java, we encounter frameworks like Selenium (which is orientated to web applications), JUnit (used for unit tests, and is often compared to Jest), and TestNG (testing framework that automates testing).
Now, it is necessary to pass for a build process before executing a Java program. It is normally done by using "javac fileName.java" (java compiler). After that, we can do "java fileName" to execute it. But IDEs like IntelliJ, Eclipse and VSCode do this automatically when running the code, so there's no need for manual hassle!

Now, when it comes to setting up CI, people normally use Gitlab CI, Gitea and Argo Workflows.

Finally, deciding to use a self-hosted enviroment or a cloud-based one depends on the type and complexity of the project. Let's say we are contributing to a web server in Java created with springboot, for a big company. Maybe the project would need high customization or secutiry is a big concen, in that case the ideal would be to opt for a self-hosted enviroment. In contrast, if we are a group of friends working on a simple web server, we would choose a cloud-based enviroment because it requires minimal setup and we don't need a very complex customization.