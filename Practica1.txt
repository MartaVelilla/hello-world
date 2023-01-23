FORK: se emplea para crear una copia de un repositorio remoto en una cuenta personal. 
      Sin embargo se guarda en la nube y no en local.


GIT CLONE: clona un repositorio remoto en local. Descarga todos los archivos en una carpeta
           Establece una conexión entre el repositorio local y remoto para sincronizar los cambios.

@MartaVelilla ➜ /tmp $ git clone https://github.com/MartaVelilla/hello-world
Cloning into 'hello-world'...
remote: Enumerating objects: 41, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 41 (delta 1), reused 3 (delta 1), pack-reused 34
Unpacking objects: 100% (41/41), 59.80 KiB | 1.81 MiB/s, done.


GIT STATUS: indica si ha cambiado algo en el repositorio. 
            Muestra la información de los archios que hayan sido modificados.

@MartaVelilla ➜ /workspaces/hello-world (main ✗) $ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   fichero

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        fichero2

no changes added to commit (use "git add" and/or "git commit -a")


GIT ADD .: es un comando que se emplea para guardar los cambios. 
           Realmente crea un borrador que en el siguiente paso será confirmado.

@MartaVelilla ➜ /workspaces/hello-world (main ✗) $ git add .


GIT COMMIT -M "Practica1": confirma los cambios que fueron guardados en el borrador. 
                           El -m sirve para incluir un mensaje para el commit.

@MartaVelilla ➜ /workspaces/hello-world (main) $ git commit -m "Practica1"
[main 3bf196f] Practica1
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename fichero => Practica1 (100%)


GIT PUSH ORIGIN MAIN: copia lo que hay en el repositorio origen a el main.
                      En nuestro caso sube a la nube los archivos

@MartaVelilla ➜ /workspaces/hello-world (main) $ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 580 bytes | 580.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/MartaVelilla/hello-world
   99397d6..3bf196f  main -> main