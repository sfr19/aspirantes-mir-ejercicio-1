1.Abrir la consola e imprimir la ubicación actual.
Abri git bash. Luego coloque el comando pwd el cual me
arrojo como resultado /c/Users/MYLAPTOPCITO

2.Crear una carpeta llamada ejercicios desde la consola.
Comando mkdir ejercicios

3.Cambiar la ubicación a la nueva carpeta que crearon.
cd ejercicios/

4.Abrir la carpeta con VSCode.
comando code

5.En VSCode crear una carpeta ejercicio1.
Dentro de VSCode-Archivo - Abrir Carpeta -Selecciono la carpeta
creada ejercicios - Nueva Carpeta - Se nombro como ejercicio1 de manera grafica. Por comando seria dentro de la carpeta ejercicio mkdir ejercicio1.

6.Cear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
Dentro de la carpeta EJERCICIO1 en VSCODE creo el archivo y lo nombro README.md de manera grafica. Por comando dentro de la ruta cd ejercicio1/ con el comando touch README.md

7.Configurar nombre e email globalmente en git.
Desde git bash utilizando los comandos 
git config --global user.name sandra
git config --global user.email saforo19@gmail.com


8.Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
Desde la carpeta ejercicios ejecuto el comando git init
Initialized empty Git repository in C:/Users/MYLAPTOPCITO/ejercicios/.git/

9.Crear un primer commit con el mensaje “Versión Inicial”.
git add .
git commit -m "Version Iinicial"
