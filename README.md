DEVE INCIAR O CLONE EM UM EQUIPAMENTO COM OS SEGUINTES:

INSTALAÇÃO INICIAL: GIT, APACHE, PHP

sudo apt-get install apache2 php7.4 libapache2-mod-php7.4 php7.4-common php7.4-curl php7.4-intl php7.4-mbstring php7.4-json php7.4-xmlrpc php7.4-soap php7.4-mysql php7.4-gd php7.4-xml php7.4-cli php7.4-zip wget mysql-client unzip git binutils ruby -y

COMMANDO PARA INICIAR E APLICAÇÃO:

git clone git@github.com:tadeuwilson/app.git

sudo unzip -o app.zip -d /var/www/html/

sudo rm /var/www/html/index.html

sudo chmod -R 777 /var/www/html
