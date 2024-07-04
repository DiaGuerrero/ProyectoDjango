# ProyectoDjango

## INSTALACION

### 1. Crear el ambiente virtual 

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

 ```bash
python -m venv venv
```

### 2. Activar el ambiente virtual

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

En Windows:

```bash
venv\scripts\activate
```

### 3. Instalar la librerias y dependencias

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
pip install -r requirements.txt
```

### 4. Ir a la carpeta del proyecto

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
cd proyectoweb
```


### 5. Correr las migraciones

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

## 6. Crear usuario ADMIN para acceder a la interfaz de admin de Django

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
python manage.py createsuperuser
```

### Arrancar el Servidor

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
python manage.py runserver
```

### Vista de la pagina

Escribir en el navegador http://127.0.0.1:8000/ para ver la aplicacion.

### Agregar datos a la aplicacion

Para agregar datos usando el admin de Django.

Escribir en el navegador http://127.0.0.1:8000/admin Usando las credenciales creadas en la seccion 5.

Copyright © 2024 Diana Guerrero y Juan Pablo Valdebenito. Programacion Web DUOC UC.
