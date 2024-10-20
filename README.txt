Portal de eventos
Este proyecto es un portal de eventos d

Caracterista
Panel de eventos : descubre eventos emocionantes cerca de ti.
Foro de comentarios : Los usuarios pueden dejar comentarios sobre los eventos.
Panel de administración : Acceso especial para el usuario administrador para gestionar el portal.
Tecnologías utilizadas
Flask : Framework web utilizado para desarrollar la aplicación.
PostgreSQL : Base de datos utilizada para almacenar los datos d
Heroku : Plataforma utilizada para
Bootstrap : Framework para el diseño de la interfaz.
psycopg2 : Conector de PostgreSQL para Python.
Instalación local
Clonar el repositorio:

intento

Copiar código
git clone https://github.com/usuario/portal-eventos.git
cd portal-eventos
Crear un entorno virtu

intento

Copiar código
python -m venv venv
source venv/bin/activate  # En Windows usa venv\Scripts\activate
Instalar dependencias:

intento

Copiar código
pip install -r requirements.txt
Configurar las variables de entorno, creando un archivo .envcon:

archivo make

Copiar código
SECRET_KEY='tu_clave_secreta'
SQLALCHEMY_DATABASE_URI=
SQLALCHEMY_DATABA
'URL_de_tu_base_de_datos'
Iniciar la base

intento

Copiar código
flask db init
flask db migrate
flask db upgrade
Ejecutar

intento

Copiar código
flask run
Desplegar
Crear una aplicación en Heroku:

intento

Copiar código
heroku create miappdeprueba
Añadir PostgreSQL a Heroku:

intento

Copiar código
heroku addons:create heroku-postgresql:hobby-dev
Configurar variable

intento

Copiar código
heroku config:set SECRET_KEY='tu_clave_secreta' SQLALCHEMY_DATABASE_URI='tu_base_de_datos_heroku'
Subir y

intento

Copiar código
git push heroku master
Contribución
Si deseas contribuir a este proyecto, siéntete libre de hacer un fork y enviar tus pull request.

Licencia
Es

