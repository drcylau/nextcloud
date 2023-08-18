# nextcloud
Nextcloud for docker
Put a valid cert in the cert directory.

	docker-compose up -d	or deploy in Synology docker project

	docker exec -it nextcloud_nextcloud bash
	chown www-data:www-data /var/www/data 
	chmod 0770 /var/www/data
	exit	


Set port forwarding 8080 in your router  
Go to https://yourdomain:8080/ to install
