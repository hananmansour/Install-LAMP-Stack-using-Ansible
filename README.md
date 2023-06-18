# Install-LAMP-Stack-using-Ansible
Ansible Playbook to install  LAMP  Stack in CentOS with Apache, MySQL, and PHP.


Make sure that you have SSH Key installed and have direct root access. Mention the webservers and dbservers in hosts file and run the playbook using the below command:

      ansible-playbook -v -i hosts site.yml
  
Once done, you can check the results by browsing to http://ipaddress/. You should see a simple test page and a list of databases retrieved from the database server.
