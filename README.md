# Android
This README file aims to expalin the steps involved in using Jenkins to build Android code from GitHub repo when required.
The pre req to download Jenkins is having a Java 7 or above version pre installed Java 8 is recommended.Jenkins is first downloaded on the local machine from https://jenkins.io/ depending on the type of OS.The Jenkins version used in this test framework is 2.60.1
The command prompt is used to start jenkins using java -jar jenkins.war httpPort=8080 .This command specifies on the port where jenkins is hosted on local machine.
During the first time istgallation an alphanumeric key is generated which is to be stored in a file as it is required later.When the message INFO: Jenkins is fully up and running is seen on the command prompt check if the localhost at the required port shows up the initial screen .It will ask for the key generated previously.We enter the key and then the next screen appears which shows an option to install all recommended plugins ,which is advisable.
Once the Jenkins is up and running it also gives the option to create user but we can skip it ,this means that there is only one user i.e admin (you )and pwd is the key used.
In the dashboard we can set up build jobs from various sources .The screenshots of how to configure the jobs and jenkins has been attached in the word doc .
