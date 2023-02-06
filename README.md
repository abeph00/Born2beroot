<img src="https://raw.githubusercontent.com/JaeSeoKim/badge42/main/public/badge42_logo.svg" width ="10%"/>
<h1 align="center">
	Born2beroot
</h1>

<p align="center">
	<b><i>Development repo for 42 projects</i></b><br>

---

## 🗣️EN QUE CONSISTE

> _El objetivo de este proyecto es introducirte al increíble mundo de la virtualización. Mediante la creacion de una maqina virtual.

## 📝COMANDOS UTILES

> REBOOT: Reiniciar el sistema

> SUDO -V: Nos muestra la version de sudo y también los argumentos pasados para configurar cuando se creo sudo

> KERNEL Y SO: uname -a

> SUDO AA-STATUS: Estado del AppArmor

> LSBLK: Listar las particiones

> SHASUM“nombre de archivo”: Permite leer el .vdi de nuestra firma.

> SYSTEMCTL ENABLE/DISABLE CRON

> SYSTEMCTL START/STOP CRON

> SUDO CRONTAB -e: Archivo donde modificamos cada cuanto se ejecuta el script.

> SUDO ADDUSER LOGIN: Crear un usuario.

> SUDO ADDGROUP GRUPO: Crear un grupo.

> GETENT GROUP GRUPO: Consultar un grupo.

> CAT /ETC/GROUP: Todos los grupos y los usuarios.

> SUDO ADDUSER USER GRUPO: Añadir un usuario en un grupo.

> /etc/hostname: Cambiar host name.

> /etc/hosts: Cambiar host name.

> SUDO HOSTNAMECTL SET-HOSTNAME “NOMBRE”: Cambiar host name.

> SUDO APT UPDATE: Actualizar los repositorios del archivo.

> SUDO APT INSTALL OPENSSH-SERVER: Instalar la herramienta OpenSSH

> /etc/ssh/sshd_config: Este archivo es el ssh server system wide configuration

> ssh "USER"@localhost -p 4242 : conectarse mediante ssh a la MV.

> SUDO SYSTEMCTL STATUS SSH: Estado del servicio ssh.

> SUDO SYSTEMCTL RESTART SSH

> SUDO APT INSTALL UFW: Instalar UFW.

> SUDO UFW ALLOW 4242: Permitir que nuestro firewall permita las conexiones a través del puerto 4242.

> SUDO UFW STATUS: Estado de nuestro cortafuegos.

> SUDO PASSWD: Cambiar contraseña

> /etc/sudoers.d/sudo_config: Almacenara la configuración de las contraseñas

> /var/log/sudo: Donde quedara almacenado cada comando tanto output como input

> /etc/login.defs: Fichero donde modificaremos los parámetros de política de contraseña fuerte. En cuanto a días.

> /etc/pam.d/common-password: Fichero donde estableceremos las condiciones de una buena contraseña.

> /etc/security/pwquality.conf: Tambien podríamos haberlo hecho aqui


## ❗COSAS QUE NECESITAS SABER PARA ESTE PROYECTO

> VIRTUALIZACION
Representation o imitation de un sistema. Representación virtual de un sistema físico.  Se utiliza para lograr mas eficiencia, mejorar los procesos de la administración de los sistema, otorga fiabilidad. Ahorro energético, creación y recuperación mas ágil. Entornos de prueba temporales. 

> HYPERVISOR
La capa que esta encima del servidor físico. Software que crea y ejecuta las maquinas o servidores virtuales y que pone a disposicion el hardware del servidor fisico.

> CPU
Es el corazón de la computadora. El procesador. Por donde pasa toda la información, la analiza y decide que hacer con ella. Coordina y procesa.

> RAM
Es donde se almacenan de forma temporal los datos de los programas que estas utilizando en este momento. Random Access Memory.  Gran velocidad y los datos solo se almacenan de forma temporal. Esta relacionada directamente con el rendimiento del dispositivo.

> PLACA BASE
Es el componente común donde se interconectan todos los demás componentes. 

> SISTEMA OPERATIVO
Es el software que gestiona todos los recursos de un sistema informático permitiendo la comunicación entre el usuario y la computadora.

> _DEBIAN
Sistema operativo. Porque es mucho mas sencillo en su utilización e instalación. Sus características mas apreciadas son la estabilidad y los procesos de actualización de paquetes. Funciona en numerosas arquitecturas y dispositivos y ofrece un sistema de seguimiento de incidencias publico.

> SERVIDOR
Programa que hace una serie de servicios. Almacenar archivos y distribuirlos. Varios tipos de servidores. Puede ser cliente y servidor a la vez. Equipo que tiene instalado un software que sirve servicios útiles o información que necesitamos.

> MAQUINA VIRTUAL
Un software que permite emular el funcionamiento de un ordenador dentro de otro ordenador con todos los componentes de hardware de un orennador real que necesita para funcionar.

> PARTICION
El nombre que recibe cada una de las divisiones presentes en un disco duro.
  -PRIMARIA: Divisiones del disco que dependen de una tabla de particiones y son las que detecta el ordenador al arracar, es donde se instalan los SO. Max 4.
 -SECUNDARIA: Fue ideada para poder tener mas de 4 particiones, aunque no se puede instalar en ella un SO. 
 -LOGICA: Son las particiones que se hacen dentro de un particiones extendida. Funciona como si fueran dispositivos independientes.

> SISTEMA DE ARCHIVOS
Los sistemas de archivos se encargan de administrar y facilitar el uso de memorias de nuestro equipo. Sus principales funciones son la asignación del espacio libre y la administración del acceso a los datos

> EXT4
Sistema de archivos que permite trabajar con volúmenes de gran tamaño. Rápido y fiable. Sucesor de ext2/3

> LV
Volumen lógico es cada uno de los trozos lógicos en los que se puede dividir un volume group. Algo semejante a una partición de volumen lógico.

> LVM
Es un método de localización del espacio del disco duro en volumenes lógicos que pueden ser fácilmente redimensionados en vez de particiones.

> SSH
Es el nombre de un protocolo y del programa que lo implementa cuya principal función es el acceso remoto a un servidor por medio de un canal seguro en el que toda la información está cifrada.

> BIOS
Pequeño chip en la placa base que se encarga de initializer y verificar diferentes componente del sistema.

> ENCRIPTAR
Ocultar el contenido de un mensaje para poder desvelar ese contenido. 

> MOUNT POINT
Es una ubicación en la partición utilizada como sistema de archivos raiz.

> SUDO
Es una utilidad que permite a los usuarios ejecutar programas con los privilegios de seguridad de otro usuario normalmente root. 

> FIREWALL
También llamado cortafuegos es un sistema cuya función es prevenir y proteger a nuestra red privada de intrusiones o ataques de otras redes bloqueando el acceso. 

> GID
El identificador de grupo, abreviatura de group id.

> UFW
Es un firewall el cual utiliza la línea de comandos para configurar las iptables usando un pequeño número de comandos simples

> SCRIPT
 Es una secuencia de comandos guardada en un fichero que cuando se ejecuta hara la funcion de cada comando.

> KERNEL
Nucleo del sistema operativo, se encarga principalmente de mediar entre los procesos de usuario y el hardware disponible en la maquina. Concede al software acceso al hardware

> DISK SIGNATURE
Es un numero distintivo y unico de un disco duro u otro dispositivo de almacenaje que es parte del master root record. 

> .VDI
Virtual Disk Image. 

> APT
Advantage Package Tool. Es un administrator de paquetes de bajo nivel. Instalacion y desinstalacion de paquetes.

> APTITUDE
Administrador de paqueres de alto nivel. Gestiona mejor las de dependencias de los paquetes. Incluye mas opciones.

> APPARMOR
Es un modelo de seguridad del kernel Linux que permite al administrador del sistema restringir las capacidades de un programa. Para definir las restricciones asocia a cada programa un perfil de seguridad.

> MAC
Mandatory access control.  Se refiere a un tipo de control de acceso en el que el sistema operativo limita la habilidad del sujeto de realizar algún tipo de operación en algún objetivo.

> PHP
Lenguaje de programación interpretado. No se compila. Incrustracion de html. Dinamismo. Php solo es interpretado por el servidor no por el cliente.

> MYSQL
Sistema de gestión de bases de datos relaciones de código abierto y basado en SQL.

