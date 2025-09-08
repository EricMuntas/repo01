# Ejercicio 1
## 1.1
Creamos el repositorio mediante la creación de una carpeta, abrimos la terminal y escribios `git init`.  
Para ver que el repositorio se ha inicializado correctamente, podemos observar que pone `(master)` en la terminañ.
![Ejercicio1.1](img/img1.png)

## 1.2
Creamos el archivo `readme.md`.

## 1.3
Hacemos `git add .` para añadir los cambios al "staging area" y visualizamos el estado del repositorio con `git status`. Finalmente creamos el commit. El "file status lifecycle" que se encuentra es "staged".

## 1.4 - 1.5 - 1.6
No funciona porque no estamos ni autenticados con GitHub ni tenemos vinculados ningún repositorio remoto.  

Despues de haberlo creado y vinculado, hacemos el push.

## 1.7
Hacemos `git remote -v` y nos muestra:

`
origin  https://github.com/EricMuntas/repo01.git (fetch)
origin  https://github.com/EricMuntas/repo01.git (push)`