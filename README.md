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


