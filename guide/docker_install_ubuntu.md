Устанавливаем докер 

    sudo apt-get update 

    sudo apt-key adv --keyserver hkp://p80.pool.sks-keyservers.net:80 --recv-keys 58118E89F3A912897C070ADBF76221572C52609D 
    
    echo "deb https://apt.dockerproject.org/repo ubuntu-xenial main" | sudo tee /etc/apt/sources.list.d/docker.list 

    sudo apt-get update 

    apt-cache policy docker-engine 

    sudo apt-get install -y docker-engine 

    sudo systemctl status docker 

 

    sudo curl -L "https://github.com/docker/compose/releases/download/1.9.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose 

    sudo chmod +x /usr/local/bin/docker-compose 

    docker-compose --version 
 



    установить https://dockstation.io  для управления контейнерами

 

Посмотреть запущенные окружения docker-compose ps 