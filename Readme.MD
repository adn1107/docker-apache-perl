# Setup

git clone https://github.com/adn1107/docker-apache-perl.git

cd docker-apache-perl

docker build -t docker-apache-perl .

docker run -v c:/www:/var/www/html -p 80:80 -d docker-apache-perl /usr/sbin/apache2ctl -D FOREGROUND

Access http://localhost
