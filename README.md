# 3-tierAutomationScripts
This automation script helps to install App environment:
	1. Maven Build Tool
	2. Tomcat App Server
	3. Nginx Web Server
	4. Maria DB Server
	5. Git
Total 2 scripts haveen implemented to complete 3 tier App deployment
 
First script helps to complete following tasks:
1.install_app_tools.sh
Run the script to setup the tools: ** Login as root user and run the script:**

     $ sudo su -
     $ ./scriptname.sh
 Task-1.Update System Packages and Stop Firewalld
 Task-2.Set Hostname enable PasswordAuthentication
 Task-3.Configure Git
 Task-4.Installing Java 11
 Task-5.install maven
 Task-6.tomcat server seting up and register as a service
 Task-7.Setup Nginx
 Task-8.Setup Maria DB
Second script helps to complete following tasks:
2.deployment_script.sh
Run the script to deploy the application: ** Login as devop user and run the script:**

     $  su - devops 
     $ ./scriptname.sh
Task-1.Set SELinux Boolean for Apache to Allow Network Connections
Task-2.git clone student app repository
Task-3.Import MySQL Database Schema
Task-4.Add User to Tomcat
Task-5.Load DB Driver
Task-6.Integrate Tomcat with DB
Task-7.Restart the Tomcat SErvice
Task-8.Deploying Student App
Task-9.Configures the Java version using
Task-10.Nginx static app deployment
Task-11.git clone static-project
Task-12.Nginx static app deployment
Task-13.Reverse Proxy Configuration
Task-14.Stops and then starts the Nginx service to apply the configuration changes.







