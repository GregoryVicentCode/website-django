# website-django

Mira el video en youtube [aquí][gvc].

Este es un pequeño proyecto de sitio web con la intención de probar el framework para desarrollo web Django y entender como se pueden cargar archivos estáticos en una aplicación de este estilo.

## Tecnologías
- Python
- Django
- HTML
- Jinja2
- CSS
- Javascript

## ¿Como correr el proyecto?
**1:** Clonar el repositorio con el comando de git:
```
git clone <dirección del repo>
```
**2:** Ingresar desde la terminal dentro de la carpeta del proyecto. Ejemplo en linux:
```
cd <nombre del directorio>
```
**3:** Crear un entorno virtual:
```
python -m venv venv
```
**4:** Ingresar en el entorno virtual:
- Para linux y Mac:
```
source venv/bin/activate
```
- Para Window:
```
venv\Scripts\activate.bat
```
**5:** Descargar las dependencias del archivo 'requirements.txt' con el comando:
```
pip install -r requirements.txt   
```
**6:** Ingresar en la carpeta del proyecto Django:
```
cd <nombre del proyecto Django>
```
**7:** Ejecutar el servidor de desarrollo de Django:
```
python manage.py runserver
```
**8:** En el navegador ir al localhost:8000.

[gvc]:https://www.youtube.com/watch?v=Cx-1tX0Hm5Y
