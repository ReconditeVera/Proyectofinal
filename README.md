instrucciones de instalacion y ejecución

debes tener:

instalados Docker, sql y un navegador, obvi 

instalar y ejecutar

1.Clona el repositorio y entra a la carpeta principal:

git clone https://github.com/ro11dan/Proyecto-final-web1.git
cd Proyecto-final-web1/PDO_PHP

2.Construye y arranca el proyecto:

docker compose up -d --build


3.Abre el sistema en tu navegador web:
http://localhost:8085


Para detener el proyecto:

docker compose down

Para reiniciar desde cero 
docker compose down -v
docker compose up -d --build
