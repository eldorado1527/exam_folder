# Exam Project

Objective
Automate the provisioning of two Ubuntu-based servers, named “Master” and “Slave”, using Vagrant.
On the Master node, create a bash script to automate the deployment of a LAMP (Linux, Apache, MySQL, PHP) stack.
This script should clone a PHP application from GitHub, install all necessary packages, and configure Apache web server and MySQL. 
Ensure the bash script is reusable and readable.
Using an Ansible playbook:
Execute the bash script on the Slave node and verify that the PHP application is accessible through the VM’s IP address (take screenshot of this as evidence)
Create a cron job to check the server’s uptime every 12 am.
Requirements

Submit the bash script and Ansible playbook to (publicly accessible) GitHub repository.
Document the steps with screenshots in md files, including proof of the application’s accessibility (screenshots taken where necessary)
Use either the VM’s IP address or a domain name as the URL.
PHP Laravel GitHub Repository:

https://github.com/laravel/laravel

Submission:

Submit your work via the AltSchool of Cloud Engineering Tinyuka 2nd Semester Exam Submission Link

Push your code to GitHub.
Share your GitHub link using the submission form.

# Vagrantfile Image
 Automate the provisioning of two Ubuntu-based servers, named “Master” and “Slave”, using Vagrant.

 # Playbook Image
 The playbook image shows link, full path to the bash script "best.sh" and also displays cronjob syntax.

 # Bash Script Image
 This shows syntax that's used to install LAMP stack with their various dependencies.

 # Laravel Image
 This is the output of slave IP when run on browser.

