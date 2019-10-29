

В home создаем папку docker и кидаем туда docker-compose.yml (лежит тут) 

 

В папке enviroments (dev/pre/prod) для каждого подпроекта проекта должны лежать настройки для nginx
 

 

Добавляем хосты в  

sudo gedit /etc/hosts 

Пример: 

127.0.0.1       yii2template.admin 

127.0.0.1       yii2template.front 

 

Заходим в папку с проектом где лежит docker-compose.yml 

sudo docker-compose up просто запустить проект 

sudo docker-compose up –d запуск проекта в режиме демона 

sudo docker-compose stop остановить проект 

sudo docker-compose ps посмотреть запущенные окружения 


запускаем dockstation и через него можно запускать терминал контейнера


# в случае проблем с правами выполнить 

sudo chmod -R 777 ./yii2template 
