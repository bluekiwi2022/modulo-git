# modulo-git

Entrega lab-git

**Primero:**

-Instalo git en pc y abro mi cuenta

**Segundo:**

-Creo carpeta mkdir modulo-git
-Inicializo mediante el comando: git init

**Tercero:**

Creo repositorio en gitHub

![Repositorio Git](./capturas/creando-repo.png)

**Cuarto**

- Creo archivo en carpeta:

-       index.html y saludo.js
        -Los añado a staging mediante add.

- Creo un commit descibiendo los cambios con git commit -m "descripcion"

- Subo los cambios a github mediante un git push

![Creando commit](./capturas/creando-commit.png)

![Creando commit](./capturas/subir-servidor.png)

**Quinto**

-Creo rama "development" mediante comando: git branch nombrerama y cambio de rama mediante el comando: checkout nombreRama

![Rama creada](./capturas/nuevarama.png)

-Realizo cambios en rama en archivo y los subo.

    con git push --set-upstream origin development

![Cambios en rama](./capturas/CambioRama.png)

**Sexto**

-Vuelvo a la rama main con: git checkout main

![Cambio a main](./capturas/cambioRamaMain.png)

-Hago un merge a la rama development mediante comando: git merge development
![Haciendo merge](./capturas/mergeRamaDevelopment.png)

-Finalizo haciendo un push --set-upstream development
![Subiendo cambios con push](./capturas/subir%20cambiosRamaDevelopment.png)

Finalizo laboratorio
