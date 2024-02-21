# Comandos de git - titulo grande

## Comando para ver la versión de git - subtítulo

### Esto equivale a un h3

- git - v
- git --version

## Comandos para configuración inicial de git

- git config --global user.name "Your name"

git es la tecnologia
config  es lo que se le va a hacer
-- es una especificación del comando
user.name: al usuario en la posición name le vamos a colocar tal nombre

- git config --global user.email "Your email"


## Comando para editar o ver la configuración de git

### Para editar
- git config --global --edit
### Para listar
- git config --global --list


## Como iniciar git en un directorio

- git init

## Comandos para saber el estado de nuestros archivos

- git status

## Comando para listar las versiones de mi proyecto

- git log
- git log --oneline

## Comando para cambiar de versión

- git checkout <Id del commit o nombre e la rama>

## Luego para cambiarme del commit a la rama, escribo:
- git checkout main // nombre de la rama  porque master ya no se debe usar

## Pasos para crear una versión de nuestro código

1. Agregar todos los archivos al commit

- git add .
- git add *.js // agrega todos los archivos que tengan la extensión js por ejemplo
- git add styles.css


2. Tomar la foto del código (Crear una nueva versión)

- git commit -m "Nombre del commit" // Mensaje de menos de 50 palabras


## Nota - comando con el que se arregló el edit de las credenciales

- nano /home/riwip4o-007/.gitconfig

