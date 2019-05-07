#Linux Configuratoion for item catalog project

##Ip address and SSH port
You can visit http://18.194.209.163/ for the website deployed.
And the SSH post is 2200

##summary of software you installed and configuration changes made
1. Create AWS account
2. Create instance with AWS Lightsail
3. Allow port 2200 in the firewall of the instance, in able to change SSH port to 2200
4. SSH to the instance using old port 22
5. Change the SSH port to be 2200
6. Create a new user named grader
7. Give the grader the permission to sudo
8. Update all currently installed packages
9. Change the SSH port from 22 to 2200
10. Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
10. Configure the local timezone to UTC
11. Install and configure Apache to serve a Python mod_wsgi application
12. Install and configure PostgreSQL:
	- Do not allow remote connections
	- Create a new user named catalog that has limited permissions to your catalog application database
12. Install git, clone and setup your Catalog App project (from your GitHub repository from earlier in the Nanodegree program) so that it functions correctly when visiting your server’s IP address in a browser. Remember to set this up appropriately so that your .git directory is not publicly accessible via a browser!