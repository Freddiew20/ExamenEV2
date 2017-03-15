# ExamenEV2

## Descripción:
**_Programa que recibe una key y le asocia un valor y lo imprime, no tiene mayor funcionalidad debido a que se ha hecho así para que sea mas sencillo trabajar con el._**

## Utilización del proyecto:
    Utilizamos el comando git clone https://github.com/Freddiew20/ExamenEV2/
    En la carpeta ExamenEV2 que se descargará ejecutamos mvn package.
    Este comando creará todo lo necesario para la ejecución del proyecto.
  
## Ejecución:
    Una vez creado el repositorio local en la carpeta ExamenEV2,
    Importamos el proyecto a STS o trabajamos desde la consola.
    Ejecutaremos mvn jetty:run para que se ejecute el servidor local que hosteará nuestra aplicación web
    Este servidor local está alojado en el puerto 9999 (así viene configurado en el pom.xml y se puede cambiar)
    En el navegador escribimos localhost:9999/ y se abrirá el cliente de nuestra aplicación que tiene una interfaz muy simple
    El programa recibirá dos argumentos, una key y un value y los imprimirá con el formato que he decidido darle.
    Y ya tenemos el programa funcionando perfectamente, es un buen ejemplo de proyecto maven.
