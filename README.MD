### This repo is Roboshop configuration through Ansible


--> When we run a playbook then the executions we see in the terminal executing the tasks one by one. To don't want to see this executions in the terminal just use, 
   " nohup ansible-playbook -i inventory.ini -e ansible_username=centos -e ansible_password=DevOps321 <filename.yaml> & > /dev/null "

--> Ansible is developed with 'Python'.