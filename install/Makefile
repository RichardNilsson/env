#
#
.PHONY: server7.2 server pi composer desktop manual

server7.2:
	grep "^[^#;]" server7.2 | xargs sudo apt-get -y install

server:
	grep "^[^#;]" server | xargs sudo apt-get -y install

desktop:
	grep "^[^#;]" desktop | xargs sudo apt-get -y install

pi:
	grep "^[^#;]" pi | xargs sudo apt-get -y install

composer: 
	curl -sS https://getcomposer.org/installer | php
	sudo install composer.phar /usr/local/bin/composer
	rm composer.phar

manual:
	bash ./manual

