#Comandos a utilizar en linux:
#Primero clonar repo
git clone https://github.com/luherre/osticket_luherrera.git
#Dentro de la carpeta clonada ejecutar docker build
docker build -t osticket .
#Luego ejecutar el compose
docker compose up -d

#Una vez hecho ingresar a la IP de la maquina y configurar con tus datos el setup
#La configuracion de la DB:
HOST: osticket-db
DB_NAME: osticket_db
USER: osticket
PASS: manager_secret


#Ya configurado podrás generar ticket desde la IP de la maquina 
http://TUIP
#Para tener el panel de control y la revisión de tickets: 
http://TUIP/scp
