# ansible-docker

#Apache web server configuration docker using Ansible

Ansible is a simple yet one of the most powerful tool to automate complex multi-tier IT application environments. With IT environments too complex, automation is so crucial for simplifying the complex tasks and increasing efficiency.
Here, I've created a Ansible playbook which can be used to configure web server on docker container along with in between dependencies like configuring docker.

The ansible playbook will perform the following tasks:
  1. Configure Docker
  2. Start and enable Docker services
  3. Pull httpd web server image from the Docker Hub
  4. Run the docker container and expose it to the public
  5. Copy the html code in /var/www/html directory and start the web server
  
  To know more about it, do visit the article link given below:
  https://www.linkedin.com/pulse/automation-apache-web-server-configuration-docker-using-bharti/
  
  
  Thank you :)
