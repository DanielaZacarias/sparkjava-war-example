# sparkjava-war-example
Build war with maven and sparkjava framework

Steps:

1. Download a fresh [Tomcat 8 distribution](https://tomcat.apache.org/download-80.cgi)
2. Clone this repository to your local machine
3. Run mvn package
4. Copy the generated `sparkjava-hello-world-1.0.war` to the Tomcat `webapps` folder (EC2 PATH: /usr/share/tomcat/webapps)
5. Start Tomcat by running `sudo systemctl start tomcat` for EC2)
5. Tomcat will automatically deploy the war
6. Open [https://(IP public EC2)/sparkjava-hello-world-1.0/hello] in your browser
