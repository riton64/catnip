# catnip
# creer una appli docker
docker run -d -P -v $HOME/web_nginx:/usr/share/nginx/html --name monsite nginx
# verrifie si l'image a été créé
docker ps
# ouvrir un navigateur et aller à l'adresse
localhost:<port indiqué par docker ps>
