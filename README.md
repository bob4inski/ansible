# ansible
## Вторая лаабааа 

>В чем мем всей ситуации?
>>Вот все задание, которо енам дали:

 + На серверах rrobin, web1, web2 установить nginx.
 + На серверах web1, web2 Nginx должен работать по порту 8080 и отдавать кастомную страницу, зайдя на которую можно понять на каком сервере вы находитесь.
 + На сервере rrobin Nginx должен обеспечить балансировку нагрузки серверов web1 и web2 в режиме round-robin. Вес каждого сервера одинаковый.
 + Установка и настройка всего ПО должна быть обеспечена Ansible-сценарием.
 + Все файлы по этому заданию выложить в Github и написать ReadMe со скринами работоспособности и инструкцию по запуску вашего Ansible-сценария
> что я сделал? да вообще хз, оно само как-то

## Tckb ns ytvyjuj negjq? nj vjlyj crjgbhjdfnm 
### если ты немного(много тупой) то вот че надо сделать в этой штуке
 + Скопировать репу 
 + Потом зайти через терминал в папку которую скопировали
 + Открываем Vagrantfile [как этот](https://github.com/bob4inski/ansible/blob/main/task-2/Vagrantfile)
 + меняем 39ую строчку `ssh_pub_key = File.readlines("/home/robert/.ssh/id_rsa.pub").first.strip`
 + +  надо указать тут свой путь до ключа
 + Пишем в консольке `vagrant up`  чтобы подднять виртуалки
 + Если ничего не получилось - пошел ты отсюда, неуч
 + Далее прописываем в консольке `ansible-playbook aboba.yml`
 + ждем
 + ждем
 + ждем
 + ****и еще раз ждем****
 + если все ок, то вбиваем в браузер [192.168.11.113](http://192.168.11.113/)
 + и при обновлении должен меняться сервер(?)
 + 

