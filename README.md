
<h1 align="center">
	Born2beroot
</h1>

<p align="center">
	<b><i>Development repo for 42 projects</i></b><br>

---

## 🗣️EN QUE CONSISTE

> _El objetivo de este proyecto es introducirte al increíble mundo de la virtualización. Mediante la creacion de una maqina virtual.

## 📝COMANDOS UTILES

> _ REBOOT: Reiniciar el sistema

> _SUDO -V: Nos muestra la version de sudo y también los argumentos pasados para configurar cuando se creo sudo

> _KERNEL Y SO: uname -a

> _SUDO AA-STATUS: Estado del AppArmor

> _LSBLK: Listar las particiones

> _SHASUM“nombre de archivo”: Permite leer el .vdi de nuestra firma.

> _SYSTEMCTL ENABLE/DISABLE CRON

> _SYSTEMCTL START/STOP CRON

> _SUDO CRONTAB -e: Archivo donde modificamos cada cuanto se ejecuta el script.

> _SUDO ADDUSER LOGIN: Crear un usuario.

> _SUDO ADDGROUP GRUPO: Crear un grupo.

> _GETENT GROUP GRUPO: Consultar un grupo.

> _CAT /ETC/GROUP: Todos los grupos y los usuarios.

> _SUDO ADDUSER USER GRUPO: Añadir un usuario en un grupo.

> _/etc/hostname: Cambiar host name.

> _/etc/hosts: Cambiar host name.

> _SUDO HOSTNAMECTL SET-HOSTNAME “NOMBRE”: Cambiar host name.

> _SUDO APT UPDATE: Actualizar los repositorios del archivo.

> _SUDO APT INSTALL OPENSSH-SERVER: Instalar la herramienta OpenSSH

> _/etc/ssh/sshd_config: Este archivo es el ssh server system wide configuration

> _ssh "USER"@localhost -p 4242 : conectarse mediante ssh a la MV.

> _SUDO SYSTEMCTL STATUS SSH: Estado del servicio ssh.

> _SUDO SYSTEMCTL RESTART SSH

> _SUDO APT INSTALL UFW: Instalar UFW.

> _SUDO UFW ALLOW 4242: Permitir que nuestro firewall permita las conexiones a través del puerto 4242.

> _SUDO UFW STATUS: Estado de nuestro cortafuegos.

> _SUDO PASSWD: Cambiar contraseña

> _/etc/sudoers.d/sudo_config: Almacenara la configuración de las contraseñas

> _/var/log/sudo: Donde quedara almacenado cada comando tanto output como input

> _/etc/login.defs: Fichero donde modificaremos los parámetros de política de contraseña fuerte. En cuanto a días.

 > _/etc/pam.d/common-password: Fichero donde estableceremos las condiciones de una buena contraseña.

> _/etc/security/pwquality.conf: Tambien podríamos haberlo hecho aqui


## ❗COSAS QUE NECESITAS SABER PARA ESTE PROYECTO

> _VIRTUALIZACION
Representation o imitation de un sistema. Representación virtual de un sistema físico.  Se utiliza para lograr mas eficiencia, mejorar los procesos de la administración de los sistema, otorga fiabilidad. Ahorro energético, creación y recuperación mas ágil. Entornos de prueba temporales. 

> _HYPERVISOR
La capa que esta encima del servidor físico. Software que crea y ejecuta las maquinas o servidores virtuales y que pone a disposicion el hardware del servidor fisico.

> _CPU
Es el corazón de la computadora. El procesador. Por donde pasa toda la información, la analiza y decide que hacer con ella. Coordina y procesa.

> _RAM
Es donde se almacenan de forma temporal los datos de los programas que estas utilizando en este momento. Random Access Memory.  Gran velocidad y los datos solo se almacenan de forma temporal. Esta relacionada directamente con el rendimiento del dispositivo.

> _PLACA BASE
Es el componente común donde se interconectan todos los demás componentes. 

> _SISTEMA OPERATIVO
Es el software que gestiona todos los recursos de un sistema informático permitiendo la comunicación entre el usuario y la computadora.

> _DEBIAN
Sistema operativo. Porque es mucho mas sencillo en su utilización e instalación. Sus características mas apreciadas son la estabilidad y los procesos de actualización de paquetes. Funciona en numerosas arquitecturas y dispositivos y ofrece un sistema de seguimiento de incidencias publico.

> _SERVIDOR
Programa que hace una serie de servicios. Almacenar archivos y distribuirlos. Varios tipos de servidores. Puede ser cliente y servidor a la vez. Equipo que tiene instalado un software que sirve servicios útiles o información que necesitamos.

> _MAQUINA VIRTUAL
Un software que permite emular el funcionamiento de un ordenador dentro de otro ordenador con todos los componentes de hardware de un orennador real que necesita para funcionar.

> _PARTICION
El nombre que recibe cada una de las divisiones presentes en un disco duro.
  -PRIMARIA: Divisiones del disco que dependen de una tabla de particiones y son las que detecta el ordenador al arracar, es donde se instalan los SO. Max 4.
 -SECUNDARIA: Fue ideada para poder tener mas de 4 particiones, aunque no se puede instalar en ella un SO. 
 -LOGICA: Son las particiones que se hacen dentro de un particiones extendida. Funciona como si fueran dispositivos independientes.

> _SISTEMA DE ARCHIVOS
Los sistemas de archivos se encargan de administrar y facilitar el uso de memorias de nuestro equipo. Sus principales funciones son la asignación del espacio libre y la administración del acceso a los datos

> _EXT4
Sistema de archivos que permite trabajar con volúmenes de gran tamaño. Rápido y fiable. Sucesor de ext2/3

> _LV
Volumen lógico es cada uno de los trozos lógicos en los que se puede dividir un volume group. Algo semejante a una partición de volumen lógico.

> _LVM
Es un método de localización del espacio del disco duro en volumenes lógicos que pueden ser fácilmente redimensionados en vez de particiones.

> _SSH
Es el nombre de un protocolo y del programa que lo implementa cuya principal función es el acceso remoto a un servidor por medio de un canal seguro en el que toda la información está cifrada.

> _BIOS
Pequeño chip en la placa base que se encarga de initializer y verificar diferentes componente del sistema.

> _ENCRIPTAR
Ocultar el contenido de un mensaje para poder desvelar ese contenido. 

> _MOUNT POINT
Es una ubicación en la partición utilizada como sistema de archivos raiz.

> _SUDO
Es una utilidad que permite a los usuarios ejecutar programas con los privilegios de seguridad de otro usuario normalmente root. 

> _FIREWALL
También llamado cortafuegos es un sistema cuya función es prevenir y proteger a nuestra red privada de intrusiones o ataques de otras redes bloqueando el acceso. 

> _GID
El identificador de grupo, abreviatura de group id.

> _UFW
Es un firewall el cual utiliza la línea de comandos para configurar las iptables usando un pequeño número de comandos simples

> _SCRIPT
 Es una secuencia de comandos guardada en un fichero que cuando se ejecuta hara la funcion de cada comando.

> _KERNEL
Nucleo del sistema operativo, se encarga principalmente de mediar entre los procesos de usuario y el hardware disponible en la maquina. Concede al software acceso al hardware

> _DISK SIGNATURE
Es un numero distintivo y unico de un disco duro u otro dispositivo de almacenaje que es parte del master root record. 

> _.VDI
Virtual Disk Image. 

> _APT
Advantage Package Tool. Es un administrator de paquetes de bajo nivel. Instalacion y desinstalacion de paquetes.

> _APTITUDE
Administrador de paqueres de alto nivel. Gestiona mejor las de dependencias de los paquetes. Incluye mas opciones.

> _APPARMOR
Es un modelo de seguridad del kernel Linux que permite al administrador del sistema restringir las capacidades de un programa. Para definir las restricciones asocia a cada programa un perfil de seguridad.

> _MAC
Mandatory access control.  Se refiere a un tipo de control de acceso en el que el sistema operativo limita la habilidad del sujeto de realizar algún tipo de operación en algún objetivo.

PHP
Lenguaje de programación interpretado. No se compila. Incrustracion de html. Dinamismo. Php solo es interpretado por el servidor no por el cliente.

> _MYSQL
Sistema de gestión de bases de datos relaciones de código abierto y basado en SQL.

