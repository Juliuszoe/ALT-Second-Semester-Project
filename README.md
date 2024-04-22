# Second-Semester-Project
Deploying LAMP Stack
(Deploy LAMP Stack)

Objective
Automate the provisioning of two Ubuntu-based servers, named “Master” and “Slave”, using Vagrant.
On the Master node, create a bash script to automate the deployment of a LAMP (Linux, Apache, MySQL, PHP) stack.
This script should clone a PHP application from GitHub, install all necessary packages, and configure Apache web server and MySQL. 
Ensure the bash script is reusable and readable.
Using an Ansible playbook:
Execute the bash script on the Slave node and verify that the PHP application is accessible through the VM’s IP address (take screenshot of this as evidence)
Create a cron job to check the server’s uptime every 12 am.

https://github.com/laravel/laravel

Submission:


# Create VMs
<img width="604" alt="create-vm" src="https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/30504b35-39c0-4ed5-98a9-7d217b2395e1">

# Clone the assignment repo and CD into it
<img width="604" alt="clone-project" src="https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/d8973e9b-80dc-44f2-85f6-84d6c92e7407">

# Install ansible, configure hosts and ping
<img width="604" alt="10" src="https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/82bdba2b-1961-4cbd-af94-deb157fa5434">
<img width="634" alt="100" src="https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/9f6875c6-01c0-4a18-a7e4-d04d33c30d39">

# Create bash script, run and install laravel on master and Test on master IP
![julius](https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/d24682df-52a8-4f0b-80fc-89c79a17e9ea)

# Create playbook and give correct permissions
<img width="623" alt="ansible" src="https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/2395a386-6291-475d-ad33-1604e0a4ee82">

# Run playbook
<img width="623" alt="playbook" src="https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/8de28f1b-6740-4b8d-bd2e-579e34eac0c9">

# Playbook success
![juliuse](https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/0965aaa6-99e5-4ce5-b57c-7ed22fff73cf)

# Testing on slave IP
![juliuse](https://github.com/Juliuszoe/ALT-Second-Semester-Project/assets/149674358/7eb5075d-73cc-4e74-8e12-aaa851e0a111)
