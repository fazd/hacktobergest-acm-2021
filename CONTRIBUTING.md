# Organiza: ACM UNINORTE 2021

# Hacktober fest

Este repositorio está diseñado con fines educativos para explicar como realizar un pull request a los usuarios del grupo de ACM uninorte (2021)

## Paso 0

Se debe tener instalado git en el computador

- Para descargar git en el pc, debes descargar el siguiente programa [Git](https://git-scm.com/downloads)
- Instalar git y abrirlo en la carpeta donde guardarás el repositorio
- Tener una cuenta en [Github](htpps://www.github.com)

## Paso 1

Visitamos el repositorio al cual queremos contribuir
https://github.com/fazd/hacktobergest-acm-2021

## Paso 2

realizamos un fork al repositorio presionando el botón de fork:

![alt text](https://raw.githubusercontent.com/fazd/Hacktober-fest-2020-ACM/master/guide-files/fork.PNG "Fork")

## Paso 3

Visitamos nuestro repositorio creado en nuestra cuenta:
https://github.com/yourUser/Hacktober-fest-2020-ACM

## Paso 4

Clonamos el repositorio:

```ssh
$ git clone https://github.com/yourUser/hacktobergest-acm-2021`
$ cd hacktobergest-acm-2021`
```

Paso 5
Agregar un archivo. ya sea un archivo donde te presentes. (puede ser en HTML. Lo que tu desses)

Paso 6
Agregar en el archivo de README.md
"- Tu nombre"

## Paso 7

Creamos una nueva rama y agregamos los cambios al repositorio

```ssh
$ git checkout -b AddYourName_Contribution
$ git add -A
$ git commit -m "add Your name into readme files"
$ git push origin AddYourName_Contribution
```

## Paso 8

Verificamos que los cambios estén en el repositorio de github.

## Paso 9

Nos dirigimos al repositorio nuestro (https://github.com/yourUser/hacktobergest-acm-2021) y allí nos vamos a la ventana de pull request.

## Paso 10

Presionamos el botón de Pull request y llenamos la información de la siguiente manera:

- base repository: fazd/hacktobergest-acm-2021
- base: master
- head repository: yourUser/hacktobergest-acm-2021
- base: La rama que acaban de crear

Presionas en crear pull request y escribes el mensaje explicando que hiciste

# Contribución

Muchas gracias por contribuir a este repositorio

- Fabio Zapata
