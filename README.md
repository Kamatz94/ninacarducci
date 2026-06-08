Pour passer le site en mode https, veuillez lancer dans le serveur la commande suivante :
http-server -S -C certs/localhost.pem -K certs/localhost-key.pem -c0 -a localhost
Ainsi vous récupérez l'adresse  https://localhost:8080 pour un site sécurisé en local.
Pour cela j'ai déploiyé le package MKcert via un "npm install"
