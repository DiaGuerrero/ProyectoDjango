<h1 align="center">Tienda Tecnológica</h1>

<p><img align="right" height="250" width="250" src="https://raw.githubusercontent.com/SubhadeepZilong/SubhadeepZilong/main/icons/animation_500_kxa883sd.gif" alt="SubhadeepZilong" /></p>

&emsp;
<h3 align="left">Hola 👋, instructivo de como instalar y acceder al proyecto.</h3>
&emsp;
<br/>
<br/>
<br/>
<br/>

# Tabla de Contenido Proyecto Django
- [Instalación](#instalación)
- [Tech Stack](#tech-stack)
- [Development](#development)
- [Version Controll & Tools](#version-controll--tools)


## INSTALACION

### :one:. Crear el ambiente virtual 

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

 ```bash
python -m venv venv
```

### :two:. Activar el ambiente virtual

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

En Windows:

```bash
venv\scripts\activate
```

### :three:. Instalar la librerias y dependencias

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
pip install -r requirements.txt
```

### :four:. Ir a la carpeta del proyecto

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
cd proyectoweb
```


### :five:. Correr las migraciones

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

### :six:. Crear usuario ADMIN para acceder a la interfaz de admin de Django

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
python manage.py createsuperuser
```
### Nombre de usuario: admin
### Password: 1234

### :seven:. Reemplazar el archivo db.sqlite3 por el archivo que viene el zip

En la carpeta del proyecto descomprimir el archivo zip y reemplazarlo
por el que se crea en el Paso 5

### :eight:. Arrancar el Servidor

En la carpeta del proyecto usando PowerShell usar el siguiente comando:

```bash
python manage.py runserver
```

### :nine:. Vista de la pagina

Escribir en el navegador http://127.0.0.1:8000/ para ver la aplicacion.

### :one::zero:. Agregar datos a la aplicacion

Para agregar datos usando el admin de Django.

Escribir en el navegador http://127.0.0.1:8000/admin Usando las credenciales creadas en la seccion 6.


## 🛠 &nbsp;Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)&nbsp;
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)&nbsp;
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)&nbsp;
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)&nbsp;
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)&nbsp;


## ⚙️ Development
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)&nbsp;


## 🧰 &nbsp;Version Controll & Tools 

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)&nbsp;
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)&nbsp;

## Autores

[<sub>Diana Guerrero</sub>](https://github.com/DiaGuerrero) |  [<sub>Juan Pablo Valdebenito</sub>](https://github.com/zlSirodev)
<br/>
Copyright © 2024. Programacion Web DUOC UC.
