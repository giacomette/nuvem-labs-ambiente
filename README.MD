# Configuração do Ambiente

* baixar e instalar android studio (https://developer.android.com/studio)
* baixar e instalar Xcode (Apple Store )
* instalar o gerenciador de pacotes brew (https://brew.sh/index_pt-br)
* instalar o nodejs (brew install node)
* instalar o cli do react native (npm install @react-native-community/cli -g)
* instalar o cli do react (npm install create-react-app -g)
* instalar o docker (brew install docker)
* instalar o cli da heroku (brew tap heroku/brew && brew install heroku)
* instalar mysql workbench (https://dev.mysql.com/downloads/workbench ou brew install cask mysqlworkbench)


Docker Scripts

Mysql/MariaDB
* docker run -e MYSQL_ALLOW_EMPTY_PASSWORD=true --name mariaDB-localhost -d -p 3306:3306 mariadb:10.3
* docker run -d --hostname my-rabbit --name rabbitMQ-localhost -p 15672:15672 -p 5672:5672 -p 25676:25676 rabbitmq:management
