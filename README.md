

Запустить контейнер с БД, отличной от mariaDB, используя инструкции на сайте: https://hub.docker.com/
![alt text](/images/1_1.png)

![alt text](/images/1_2.png)

Добавить в контейнер hostname такой же, как hostname системы через переменную:
![alt text](/images/2_1.png)

Для наглядности:

![alt text](/images/2_2.png)

Заполнить БД данными через консоль:
![alt text](/images/3.png)

Запустить phpmyadmin (в контейнере) и через веб проверить, что все введенные данные доступны:
![alt text](/images/4_1.png)

![alt text](/images/4_2.png)
