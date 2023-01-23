FORK: se emplea para crear una copia de un repositorio remoto en una cuenta personal. 
      Sin embargo se guarda en la nube y no en local.


GIT CLONE: clona un repositorio remoto en local. Descarga todos los archivos en una carpeta
           Establece una conexión entre el repositorio local y remoto para sincronizar los cambios.

![image](https://user-images.githubusercontent.com/97589757/214023634-c5d9ad06-9517-4736-afd0-902f20f6ae07.png)

Para comprobar que realmente se ha clonado:
![image](https://user-images.githubusercontent.com/97589757/214023663-e9b13455-5e52-4d07-b6e2-18af152e7409.png)


GIT STATUS: indica si ha cambiado algo en el repositorio. 
            Muestra la información de los archios que hayan sido modificados.
            
Cuando no ha cambiado nada desde la última vez sale de a siguiente manera:
![image](https://user-images.githubusercontent.com/97589757/214023764-b8ffd651-eca9-4519-82d9-e6d8889535a7.png)

Cuando ha cambiado cosas, queda así:
![image](https://user-images.githubusercontent.com/97589757/214023906-0d525d4c-9d10-4634-91c9-68d67e6a97e3.png)


GIT ADD .: es un comando que se emplea para guardar los cambios. 
           Realmente crea un borrador que en el siguiente paso será confirmado.

![image](https://user-images.githubusercontent.com/97589757/214023995-b2484036-3116-49d5-bfba-5ae64b47a836.png)


GIT COMMIT -M "Practica1": confirma los cambios que fueron guardados en el borrador. 
                           El -m sirve para incluir un mensaje para el commit.

![image](https://user-images.githubusercontent.com/97589757/214024045-22163da7-a2e1-4c25-b0f1-1cf88d8564bf.png)


GIT PUSH ORIGIN MAIN: copia lo que hay en el repositorio origen a el main.
                      En nuestro caso sube a la nube los archivos

![image](https://user-images.githubusercontent.com/97589757/214024109-85394942-8546-46fe-9068-df65dac630a6.png)

Si ya estuviera todo en la nube sale el siguiente mensaje:
![image](https://user-images.githubusercontent.com/97589757/214024204-360646f8-f5f4-4710-b79c-d574573cae55.png)


