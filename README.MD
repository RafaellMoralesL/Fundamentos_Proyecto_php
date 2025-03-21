_ Este proyecto es una práctica de php, el cual es un lenguaje no compilado, y por lo tanto, el realizar cambios al código y que se refleje en la ejecución es muy fácil. _

### En resumen
`este proyecto php es un hola mundo, el cual utiliza el comando echo para mostrar información, y una imagen adjunta que aparece junto con el Hola mundo, que utiliza el comando img src, para identificar la locación del archivo de la imagen.` 
### Para ejecutar el proyecto 
`Se necesita SSH, que es una conexión remota a una IP, en este caso a una máquina virtual de Ubuntu, se utiliza el ssh para tener una terminal fuera de la máquina virtual, con la terminal, se hace una conexión a la página de apache, el cual da acceso a un HTML dentro de la IP de la máquina virtual, se crea un archivo php, y se utiliza, como antes fue explicado, los comando echo e img src, al tener acceso al HTML y el archivo php, simplemente se accede por medio de la ruta donde se encuentra, en este caso, seria, IPdeTuMáquinaVirtual/RutaDelArchivo, haciendo uso de / para separar como es debido la ruta, ppor ejemplo, digamos que colocan que el archivo está en una carpeta, dentro de otra carpeta, dentro de otra carpeta, cada nombre de carpeta debe ser separado, y por ultimo el nombre del archivo php.`

### Instalación y ejecución de Archivo
Se necesitan varios pasos, 
1. Descargar Virtual Box y Ubuntu desde sus páginas oficiales
2. Crear una máquina virtual en Ubuntu
3. Dentro de la máquina virtual utilizar sudo apt, para instalar ifconfig, ssh y apache
``` Para ifconfig, se utiliza sudo apt -y install net-tools, para ssh sudo apt install openssh-server y para apache sudo apt install apache2 ```
4. Instalar VSCode desde su página oficial en su escritorio
5. Dentro de VSCode instalar la extensión de SSH
6. Utilizar la extensión SSH con la terminal de VSCode para acceder al servidor de la máquina virtual con apache
``` se utiliza el comando ssh remote_username@remote_host, donde se reemplaza por el usuario que se posee dentro de ubuntu, digamos ssh @proyectosremotos ```
7. Proveer de permisos a la conexión de VSCode
``` Con el comando chmod se otorgan los permisos dentro de Ubuntu, se necesitan permisos de escritura, lectura y ejecución ```
8. Colocar una carpeta o solamente el archivo php
9. Dentro del Navegador establecer conexión con la IP
``` Debe colocar la IP de la conexión remota y la ruta del archivo ```
Y eso seria todo lo que se necesita realizar
