# All-about-Jenkins

Installing Jenkins 

Jenkins is typically run as a standalone application in its own process. The Jenkins WAR file bundles Winstone, a Jetty servlet container wrapper, and can be started on any operating system or platform with a version of Java supported by Jenkins.

Theoretically, Jenkins can also be run as a servlet in a traditional servlet container like Apache Tomcat or WildFly, but in practice this is largely untested and there are many caveats. In particular, support for WebSocket agents is only implemented for the Jetty servlet container. See the Servlet Container Support Policy page for details.
