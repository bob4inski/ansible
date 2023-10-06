# ansible
## Шестая лабораторная работа
## Задание
 + on servers rrobin, web1, web2 to install nginx.
 + on servers web1, web2 Nginx he works on port 8080 and gives a custom page.
 + on server rrobin Nginx provides load balancing of servers web1 и web2 in the mode round-robin.
 + Installation and configuration of all software should be provided by Ansible script.
 + upload all files to Github and write ReadMe 


##  the script works
### a short work script
 + copy the repository 
 + through the terminal, go to the copied folder
 + open [Vagrantfile ](https://github.com/Ekaterina04/emamus/blob/main/lab4/Vagrantfile)
 + replacing line 39 `ssh_pub_key = File.readlines("/home/sirius/.ssh/id_rsa.pub").first.strip`
 + +  path to the key
 + write in console `vagrant up` 
 + write in console `ansible-playbook aboba.yml`
 + wait
 + ****we've been waiting a long time****

 + if you are not sure about the correctness of your work, then repeat after [Robert](https://www.youtube.com/watch?v=ZzvM6_S0HXA)
