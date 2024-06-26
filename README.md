# Домашнее задание к занятию "`Система мониторинга Zabbix`" - `Сологуб Евгений`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
[Задания](https://github.com/SeSloup/netology_zabbix/blob/master/hw-02.md)
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Приведите ответ в свободной форме........`

1. `скриншот авторизации в админке.`  
![скриншот авторизации в админке 1.](https://github.com/SeSloup/netology_zabbix/blob/master/screens/01.png)

![скриншот авторизации в админке 2.](https://github.com/SeSloup/netology_zabbix/blob/master/screens/02.png)

3. [текст](https://github.com/SeSloup/netology_zabbix/blob/master/install%20Zabbix) использованных команд в GitHub.`  


---

### Задание 2


1. `sudo apt-get install zabbix-agent`  
2. `cp zabbix_agentd.conf ./zabbix_agentd.conf.back`  
3. `SERVER=host Server_activate=host`  
4. `sudo systemctl restart zabbix_agentd.service`  
5. `Agent vm: sudo ufw allow *.*.*.0/24`  
6. `http://localhost/zabbix/: /Monitoring/Hosts/Create host`  
![host](https://github.com/SeSloup/netology_zabbix/blob/master/screens/03.png)

![hosts](https://github.com/SeSloup/netology_zabbix/blob/master/screens/04.png)`

![host info](https://github.com/SeSloup/netology_zabbix/blob/master/screens/05.png)
---

Спасибо за проверку !
