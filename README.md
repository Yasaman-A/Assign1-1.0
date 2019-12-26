MyBatis JPetStore V1.0
======================

JPetStore 6 is a full web application built on top of MyBatis 3, Spring 5 and Stripes. This version is modified as a teaching tool for software testing.

Essentials
----------

## Run on Application Server
Running JPetStore sample under Tomcat (using the [cargo-maven2-plugin](https://codehaus-cargo.github.io/cargo/Maven2+plugin.html)).


- Download the application (v1.0):
	$git clone https://github.com/Yasaman-A/Assign1-1.0.git
- Enter to the folder
	$cd Assign1-1.0
- Now, start your application on port 7070:
	$./mvnw cargo:run -Dcargo.servlet.port=7070 -P tomcat90;

- Run application in browser http://localhost:7070/jpetstore/ 

- Press Ctrl-C to stop the server.


================================================================
  > Note:
  >
  > We provide maven profiles per application server as follow:
  >
  > | Profile        | Description |
  > | -------------- | ----------- |
  > | tomcat90       | Running under the Tomcat 9.0 |
  > | tomcat85       | Running under the Tomcat 8.5 |
  > | tomcat70       | Running under the Tomcat 7.0 |
  > | tomee80        | Running under the TomEE 8.0(Java EE 8) |
  > | tomee71        | Running under the TomEE 7.1(Java EE 7) |
  > | wildfly18      | Running under the WildFly 18(Java EE 8) |
  > | wildfly13      | Running under the WildFly 13(Java EE 7) |
  > | liberty-ee8    | Running under the WebSphere Liberty(Java EE 8) |
  > | liberty-ee7    | Running under the WebSphere Liberty(Java EE 7) |
  > | jetty          | Running under the Jetty 9 |
  > | glassfish5     | Running under the GlassFish 5(Java EE 8) |
  > | glassfish4     | Running under the GlassFish 4(Java EE 7) |
  > | resin          | Running under the Resin 4 |
