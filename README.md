# Registro de Usuario con Django y PostgreSQL

En esta tarea se implementa un registro básico de usuarios usando Django como framework web y PostgreSQL como base de datos.

## Tecnologías utilizadas
- Python 3
- Django
- PostgreSQL
- HTML
- Git y GitHub

## Requisitos previos
Antes de ejecutar se debe tener instalado:
- Python 3.10 o superior
- pip
- PostgreSQL
- Git (opcional)

## Pasos para ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/hyanesd/Arquitectura_software.git
``` 

2. Entrar a la carpeta del proyecto: 
```bash
cd usuario_project
``` 

3. Crear y activar el entorno virtual:
```bash
python -m venv venv
``` 
Para macOS / Linux:
```bash
source venv/bin/activate
``` 
Para windows:
```bash
venv\Scripts\activate
``` 

4. Instalar dependencias:
```bash
pip install django psycopg2-binary
``` 

5. Ejecutar migraciones:
```bash
python manage.py makemigrations
python manage.py migrate
``` 

6. Ejecutar el servidor:
```bash
python manage.py runserver
``` 

7. Abrir el navegador en: 
http://127.0.0.1:8000/

## Evidencias del funcionamiento 
