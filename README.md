<h1>Задача 1</h1>

 
![image](https://github.com/user-attachments/assets/286effc7-63e9-4efc-a5f4-b5c4a63955c8)


https://hub.docker.com/repository/docker/ne0kk/custom-nginx/general




<h1>Задача 2</h1> 


Пул из docker 
 ![image](https://github.com/user-attachments/assets/45ef6ceb-3b33-4ca9-9e15-e7319c347df5)

Run контейнера
 ![image](https://github.com/user-attachments/assets/3cfc3f10-2fa5-4525-aecd-3bda0d8e1737)

Rename контейнера
 ![image](https://github.com/user-attachments/assets/3dad1310-08ed-43ae-bbad-30b9c7bdf9b7)

Выполнение команды 
 ![image](https://github.com/user-attachments/assets/4988d899-3c2d-401f-8b7e-ca21eafab663)

Проверка порта и страницы
 ![image](https://github.com/user-attachments/assets/e3f68ea5-b904-4d38-8ef2-d19a14f3aac8)



<h1>Задача 3</h1> 



Присоединение к потоку вывода
 ![image](https://github.com/user-attachments/assets/cb467b02-41fd-410d-a3c1-0f7ab8b16cb4)

Выход произошел из за того что CTRL+C это команда завершения процесса. 
Мы подключились не посредственно к контейнеру и это команда его и завершила. 
Зайдем в контейнер 
Проверяем наличие установленных nano или vim.
Пробуем установить, видим, что apt-get не отрабатывает
 ![image](https://github.com/user-attachments/assets/d5ceae58-08a7-4213-86d2-3480874181b3)


Запускаем обновление и уже инсталлируем редактор
![image](https://github.com/user-attachments/assets/a61cbe15-cb7c-483f-81c0-678600fa07f3)

Редактируем фаил
 ![image](https://github.com/user-attachments/assets/f99364ab-1d82-4534-9be3-8ca7eb7b5faa)

 ![image](https://github.com/user-attachments/assets/9238eaff-d84d-4463-b2fc-01c117194906)

Перезапуск сервера и проверка портов
 ![image](https://github.com/user-attachments/assets/6ba5930e-521c-4650-bf90-0fde3f73f69a)


Вывод команды 
![image](https://github.com/user-attachments/assets/0271d41e-3a47-4909-a39d-49abcabe09ba)
 
Порт ссылается на 80, а внутри контейнера мы его изменили на 81, надо изменить привязку порта в контейнере
 ![image](https://github.com/user-attachments/assets/9875e679-1024-4786-97bf-47b75df3efce)

Узнаем ID 
 ![image](https://github.com/user-attachments/assets/6a6fb6c5-2298-4f43-b3d3-13abd98c9258)

31888732e820e6328a64ac08bb40f9ef2b46fcea8a4c87b852cb7b9070e6df7d
Останавливаем контейнер и докер 
 ![image](https://github.com/user-attachments/assets/a44684d8-9240-4fc2-bbaf-14f25a7b7a05)

Редактирем фаил добавляем 81 порт 
 ![image](https://github.com/user-attachments/assets/2cf08cd8-31e9-4c4f-ad7d-e8c672d776cb)

После старта
 ![image](https://github.com/user-attachments/assets/107ea6bc-ea3c-40dd-a224-0f15b654dec6)

Удаляем контейнер
![image](https://github.com/user-attachments/assets/99c84d26-0437-4482-bddb-3f87f9a61d9a)
 







<h1>Задача 4</h1>



Создаем контейнеры с ключами v – lдля монтирования папки, --name – для имени, d -t- для старта 
 ![image](https://github.com/user-attachments/assets/461aa172-2eb1-457f-bdf7-621c03f255ba)

Зайдем centos и создадим фаил
 ![image](https://github.com/user-attachments/assets/063281a4-fe57-47fe-a265-ececefd9eb7c)

Создадим еще фаил на хосте 
 ![image](https://github.com/user-attachments/assets/7d5d55a7-e098-46e3-9858-1a7aedcb9f36)

Выполнили команду во втором контейнере 
 ![image](https://github.com/user-attachments/assets/4fa5fa0f-113f-4e78-9bc6-4f7e2f9692fd)






<h1>Задача 5</h1> 



Создадим паку
 ![image](https://github.com/user-attachments/assets/0b106d1e-778e-4d94-b449-eb79d39b49ce)

Создадим 2 фаила 
![image](https://github.com/user-attachments/assets/1be4cd61-ac4a-400a-804d-965d6928f7e2)
 
Выполним команду 
 ![image](https://github.com/user-attachments/assets/e2ca0b2f-3a50-49cd-93ba-2db7e2c83b68)

Запустился только портайнер
Редактируем фаил и перезапускам добавим https://docs.docker.com/reference/compose-file/include/ 
 ![image](https://github.com/user-attachments/assets/5870761d-8b0d-4065-8175-de045a83edd2)


Созданы оба контейнера 
 ![image](https://github.com/user-attachments/assets/555ec534-24fe-49a7-8b95-f9450e28ffff)


Отредактировал файлы, убрал host, что бы заработали пробросы. 

Создаем локальный контейнер 
 ![image](https://github.com/user-attachments/assets/731af060-0951-4147-8b0d-24c04a424dcd)



Пулим образ меняем тег 
 ![image](https://github.com/user-attachments/assets/adccf75d-aa05-4eeb-b40e-d3d3c4789859)


Пушим образ 
 ![image](https://github.com/user-attachments/assets/6e532ded-b260-41a3-9682-b2e34679dec4)

 ![image](https://github.com/user-attachments/assets/686ed83c-9f17-40cb-a955-cec11e2c568e)

Заходим в веб portainer и создаем контейнер
 ![image](https://github.com/user-attachments/assets/056649a5-a8bb-465b-953a-0ffde3269b7c)

Инспектируем контейнер 
 
![image](https://github.com/user-attachments/assets/7105344c-f75e-4661-a294-bfedac8e181b)

 Удаялем фаил и пробуем собрать проект, выполоняем рекомендации и собираем еще раз 

 ![image](https://github.com/user-attachments/assets/3d760da8-fa06-4f8b-b2d6-d875a6904ca0)


 

Все что осталось от проекта выключено (подглядел на вебинаре Docker stop $(docker ps -a -q))
 ![image](https://github.com/user-attachments/assets/6a957b67-c322-4ae0-a350-a53d4b3f0f18)


