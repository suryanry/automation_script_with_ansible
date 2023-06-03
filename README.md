# automation_script_with_ansible
Network Automation using Ansible

I have automated a network with the use of Ansible, where the network consists of 5 servers that are 'devhaproxy' - a server with HA Proxy configuration for public usage, 'devA' 'devB' 'devC' - are servers with Nginx configuration which gives services to public and 'bastionET2598' - is server with Bastion configuration for user usage.

I have given two ssh keys, one for only 'bastionET2598' server and other for remaining servers, but you can give how many keys you want and mention them in ssh-config file.

First clone the git repository assignment-2, then run the ansible-playbook with the command ansible-playbook -i hosts site.yaml.

It should run without any errors and the testing commands are giving at the end of execution where the three nginx servers provide the services by executing the php file. 
