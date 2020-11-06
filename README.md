# catnip
# creer une image docker aller dans le répertoire catnip-main
docker build -t monsite .
# verrifie si l'image a été créé
docker ps
# lancer l'execution
docker run -d -p 8888:5000 monsite
# ouvrir un navigateur et aller à l'adresse
http://localhost:8888
