<h1 align="center"> Creaci贸n de API con Django </h1>

_El proyecto tiene como fin elegir una tecnolog铆a para realizar una API para una cadena de restaurantes en la cual se pueda realizar los pagos y adicional tambi茅n poder ver el historial de pagos realizados_

## Comenzando 馃殌

_En primer lugar, es necesario poder clonar el repositorio con el fin de poder realizar las diferentes pruebas._

### Pre-requisitos 馃搵

_Para poder realizar un uso completo de la API se recomienda realizar la instalaci贸n de los siguientes paquetes_

```
pip install Django==4.0
sudo apt install postgresql postgresql-contrib
pip install psycopg2
```

### Iniciaci贸n 馃敡

_Comencemos_

_Despues de haber clonado vamos a ubicar el directorio con nombre siata_backEnd_

```
nombre_usuario:~/Directorioendondeseclono/siata_backEnd$
```

_Despu茅s de estar en el directorio ra铆z del proyecto, debemos abrir ese directorio con la herramienta de desarrollo de nuestra elecci贸n, en este caso se utiliz贸 Visual Studio Code, y vamos a ejecutar el anterior comando para correr la aplicaci贸n Restaurante, el comando es el siguiente:_

```
python3 manage.py runserver
```

_Y nos aparecer谩 que nuestra aplicaci贸n indicando que ya est谩 corriendo por el puerto 6969 en nuestro local host, que ya est谩 predefinido_

![image](https://user-images.githubusercontent.com/98775024/218368296-51e02f61-7ff4-4136-8732-3337a13bf30f.png)


## Pruebas de entrada y salida 鈿欙笍

### Prueba con el metodo POST

![Screenshot from 2023-02-12 22-22-05](https://user-images.githubusercontent.com/98775024/218368544-440d30f3-f4de-4ebf-927c-06e48e516561.png)

### Prueba con el metodo GET

![image](https://user-images.githubusercontent.com/98775024/218368730-5967f2cb-c212-48a4-9c0a-29360d475380.png)

_En este caso para poder utilizar nuestros endpoint hemos utilizado la extension Thunder CLient que nos deja hacer las consultas POST y GET, y en cada consulta podemos ver la ruta necesaria para poder obtener los datos_

## Pruebas de validacion de los campos de la base de satos 馃敥

_Ciertos campos de la base de datos ten铆a unas validaciones, aqu铆 se deja plasmada la demostraci贸n_

### Prueba del campo nombre del restaurante

![nombre](https://user-images.githubusercontent.com/98775024/218369354-7336bd19-0d85-4c66-a9a6-1faaadd92959.png)

### Prueba valor del men煤


![image](https://user-images.githubusercontent.com/98775024/218369768-98a858c0-5585-46e3-a5c6-95effb0a7a0f.png)

![image](https://user-images.githubusercontent.com/98775024/218369846-b053d1aa-d567-4edc-a4fa-a61e2f408868.png)

### Demostraci贸n de la base de datos desde la interface

![image](https://user-images.githubusercontent.com/98775024/218370860-56d0c7c1-a202-45c2-a625-9f84cbee92f1.png)


## Construido con 馃洜锔?

_Herramientas basadas en el Framework Django_

* [Django](https://www.djangoproject.com/download/) - El framework para el BackEnd
* [Postgres](https://www.postgresql.org/download/) - Base de datos
* [REST](https://www.django-rest-framework.org) - Framework para la creacionde la API

## Desarrollador 鉁掞笍

* **Felipe Rios** - [GitHub](https://github.com/felipeholbi)

