# python-tgstore-app
La aplicación de TG Store hecha en Django

# Pasos para arrancar
- 1. Instalar Postgresql
- 2. Instalar Django
```
python -m pip install Django
```
- 3. Crear projecto con el admin de Django
```
django-admin startproject app
```
- 4. Entrar en la carpeta del proyecto
```
cd app
```
- 5. Lanzar la aplicación
```
python3 manage.py runserver
```
- 6. Visitar nuestro sitio web
Abrir el navegador en la siguiente ruta:
[http://127.0.0.1:8000](http://127.0.0.1:8000)

Con estos pasos se levanta la aplicación raíz

# Siguientes pasos
- 1. Inicializar un modulo para construir nuestra primera aplicación Django
```
python3 manage.py startapp store
```
Desde este punto ya solo es desarrollar las rutas, vistas y servicios de la aplicación.