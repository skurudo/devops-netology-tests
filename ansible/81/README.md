* Где расположен файл с some_fact из второго пункта задания?
playbook/group_vars/all/examp.yml 

* Какая команда нужна для запуска вашего playbook на окружении test.yml?
$ ansible-playbook site.yml -i inventory/test.yml

* Какой командой можно зашифровать файл?
$ ansible-vault encrypt group_vars/deb/examp.yml

* Какой командой можно расшифровать файл?
$ ansible-vault decrypt group_vars/deb/examp.yml

* Можно ли посмотреть содержимое зашифрованного файла без команды расшифровки файла? Если можно, то как?
$ ansible-vault view group_vars/deb/examp.yml

* Как выглядит команда запуска playbook, если переменные зашифрованы?
$ ansible-playbook -i inventory/prod.yml site.yml --ask-vault-pass

* Как называется модуль подключения к host на windows?
ansible_connection: winrm

* Приведите полный текст команды для поиска информации в документации ansible для модуля подключений ssh
https://docs.ansible.com/ansible/latest/index.html

* Какой параметр из модуля подключения ssh необходим для того, чтобы определить пользователя, под которым необходимо совершать подключение?>
ansible_user=myuser
```