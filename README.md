# gitlab-cicd
Mise en place d'une usine logicielle basée sur gitlab
openssl genrsa -out domain.key 2048
openssl req -new -x509 -key domain.key -out domain.crt -days 365