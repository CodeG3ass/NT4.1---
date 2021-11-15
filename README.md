# NT4.1---
https://docs.google.com/document/d/1yWW0frd1MdW0onBCcwQYSQk_NZWtkNSQ_f9uzCEbA0Q/edit#

Установка и запуск веб-сервера в Linux
Цель работы
Освоить основные навыки установки и первоначальной настройки веб-сервера в ОС Linux.
Задания для выполнения
Используя apt-get установить Apache2 на виртуальную машину
С браузера хост-машины по IP-адресу виртуальной машины увидеть приветствие

![image](https://user-images.githubusercontent.com/92590831/141717888-fad5c312-2124-4b9f-9d50-35e2179e647b.png)

![image](https://user-images.githubusercontent.com/92590831/141717936-46632309-fa2c-41c8-bdb7-2f437cd22194.png)

В настройках сервера изменить  порт на :8080

![image](https://user-images.githubusercontent.com/92590831/141717992-4e2f3c34-3d43-4134-a42f-fbf65b9f6659.png)

![image](https://user-images.githubusercontent.com/92590831/141718131-83c0bdd4-ca70-4e14-83d2-8eb7c09df145.png)

![image](https://user-images.githubusercontent.com/92590831/141718495-2c271e2b-7a10-4206-b779-22210aee7d96.png)

Снова выполнить п 2, но с указанием порта

![image](https://user-images.githubusercontent.com/92590831/141718527-f189700a-79b5-49cb-9cb7-f1a6232c1c50.png)

Изменить порт обратно и проверить как работает заглушка

![image](https://user-images.githubusercontent.com/92590831/141718376-d09b8f02-56ef-4931-a62f-e16836fcf758.png)

![image](https://user-images.githubusercontent.com/92590831/141718406-d3f76623-fc64-429a-8f3a-28fcf807a14e.png)


В hosts хост-машины создать три домена: a1.com, b2.com, c3.com и связываем с IP виртуальной машины с Apache

![image](https://user-images.githubusercontent.com/92590831/141718585-d386e749-1966-4aa7-98b4-91a035ed44f0.png)


Для каждого домена проверить всё ли правильно, с помощью ping

![image](https://user-images.githubusercontent.com/92590831/141718634-70fee027-ef96-43ce-8a89-d529c70f41d6.png)

Зайти на все три домена, написав их вместо IP виртуальной машины

![image](https://user-images.githubusercontent.com/92590831/141718690-b8ac5f44-01c6-4410-b2a6-595c459ca98c.png)

![image](https://user-images.githubusercontent.com/92590831/141718712-9259f563-ab51-4ef3-b900-425254786836.png)

![image](https://user-images.githubusercontent.com/92590831/141718728-b29abe39-43e7-492c-a3fc-5b6d55a7a8f4.png)

Создать директории /var/www/a1.com, /var/www/b2.com, /var/www/c3.com

![image](https://user-images.githubusercontent.com/92590831/141718843-812fd75d-7d5a-4bda-8e0d-0353a5dc7ba6.png)

![image](https://user-images.githubusercontent.com/92590831/141718891-46c48183-957c-4885-bbf0-b199924fc382.png)

В каждой из них создать пустой index.html
В каждом из них написать различное содержимое

![image](https://user-images.githubusercontent.com/92590831/141719327-b4b64303-0f2e-49e4-b330-cacd3754b71f.png)

![image](https://user-images.githubusercontent.com/92590831/141719314-5f4a7238-3bee-40d2-bdea-ec015b8d0929.png)

![image](https://user-images.githubusercontent.com/92590831/141719280-4e5f8939-2671-407c-8844-240ff8c01cf3.png)

Сделать так, чтобы из браузеров хост-машины открывались сайты из директории, а не общая заглушка

![image](https://user-images.githubusercontent.com/92590831/141720116-7e815610-fb71-41bd-ab2a-21338508cb08.png)

![image](https://user-images.githubusercontent.com/92590831/141720142-17ac062c-bdd8-4879-bc0d-61fddc47c134.png)

![image](https://user-images.githubusercontent.com/92590831/141720150-b53b1b1c-bd13-4d75-a6d2-aa12af983908.png)

![image](https://user-images.githubusercontent.com/92590831/141720167-fefcfeef-a3d7-4c38-9620-a63e8eb0fe8f.png)

Контрольные вопросы

Что такое веб-сервер и для чего нужна эта программа?

Что такое рабочая директория веб-сервера?

Основные настройки сервера Apache. Файл настроек.

Что такое виртуальные хосты веб-сервера? Как настроить их в Apache?

Что такое файл hosts, где он находится в Windows и Linux, какой его формат и для чего он нужен?

Какова основная структура HTML-файла?

Дополнительные задания

Повторите все задания лабораторной работы, используя nginx в качестве рабочего веб-сервера вместо Apache2.

Напишите простой веб-клиент, запрашивающий у пользователя имя хоста и идентификатор ресурса (файла) и обращающийся к веб-серверу на этом хосте по методу GET, запрашивая данный ресурс.

