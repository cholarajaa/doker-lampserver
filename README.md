# doker-lampserver
docker compose for LAMP server

git clone https://github.com/cholarajaa/doker-lampserver

cd doker-lampserver

docker-compose up

## need fixing on apache auto starting
## open a new tab
docker exec -it lamp_web_1 /bin/bash
service apache start
exit

visit 127.0.0.1:8000
127.0.0.1:8000/info.php
