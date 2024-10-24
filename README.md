# CRUDPythonDjango
Este es un proyecto básico de CRUD (Crear, Leer, Actualizar, Eliminar) utilizando Django y Python. El proyecto permite gestionar productos en una base de datos.

Requisitos previos
  Antes de instalar y ejecutar el proyecto de manera local, asegúrate de tener lo siguiente instalado:
  
  Python (versión 3.6 o superior)
  Pip (gestor de paquetes de Python)
  Git (opcional, para clonar el repositorio desde GitHub)
  
Instalación
  Sigue los siguientes pasos para instalar y ejecutar el proyecto en tu entorno local.

1. Clonar el repositorio
  Clona este repositorio de GitHub en tu máquina local usando el siguiente comando: git clone https://github.com/tu_usuario/tu_repositorio.git
  Luego, navega a la carpeta del proyecto: cd tu_repositorio

2. Crear y activar un entorno virtual (opcional pero recomendado)
  Es recomendable crear un entorno virtual para evitar conflictos con otras bibliotecas de Python en tu sistema.
  python -m venv env

Activa el entorno virtual:

  En Windows: env\Scripts\activate
  En macOS/Linux: source env/bin/activate

3. Instalar las dependencias
  Instala las dependencias necesarias para el proyecto, incluidas Django y otras bibliotecas listadas en el archivo requirements.txt.
   pip install -r requirements.txt

  Si no tienes el archivo requirements.txt, puedes crearlo ejecutando el siguiente comando antes de subir el proyecto: 
   pip freeze > requirements.txt

4. Migrar la base de datos
  Aplica las migraciones a la base de datos para crear las tablas necesarias: python manage.py migrate

5. Crear un superusuario
  Para acceder al panel de administración de Django, necesitarás un superusuario. Puedes crearlo ejecutando: python manage.py createsuperuser

  Sigue las instrucciones para crear un nombre de usuario, correo electrónico y contraseña.

6. Ejecutar el servidor
  Inicia el servidor de desarrollo de Django: python manage.py runserver

Ahora puedes abrir tu navegador y acceder al proyecto en http://127.0.0.1:8000.

7. Acceso al panel de administración
Para gestionar los productos y otros datos del proyecto, puedes acceder al panel de administración en http://127.0.0.1:8000/admin utilizando el superusuario que creaste en el paso 5.




Características
  Crear, Leer, Actualizar y Eliminar productos.
  Panel de administración de Django para la gestión de modelos.
Contribuir
  Si deseas contribuir a este proyecto, sigue estos pasos:
  Haz un fork del repositorio.
  Crea una nueva rama (git checkout -b feature/nueva-característica).
  Realiza los cambios y haz commit (git commit -m 'Agregar nueva característica').
  Sube los cambios (git push origin feature/nueva-característica).
  Abre un pull request.
