### Trata de llevar a cabo alguna instalación y desinstalación mediante un instalador y un gestor de paquetes, e indica las ventajas e inconvenientes que has observado en uno y otro.
El primer paso antes de cualquier instalación, es la de comprobar la
compatibilidad de la aplicación a instalar, con la máquina de destino. En este
ejercicio uso un entorno controlado como es el de una máquina virtual
(VirtualBox) usando Windows 10 en una máquina virtual y Ubuntu 22.04 LTS
en otra. De esta forma, la prueba de instalación y desinstalación es
independiente a la máquina huésped, por lo que si falla algo, no deteriora el
sistema huésped.
En ambos casos se ha tratado de tareas sencillas, si bien en el gestor de
paquetes has de localizar el nombre del paquete (programa a instalar), para
ejecutar la instalación habitualmente en sistemas operativos basados en
Linux.
Por otro lado, el instalador (que suele usarse en distribuciones de
Windows), va íntimamente ligado al programa que va a instalar, es decir, el
instalador está dedicado únicamente a ese programa y no como ocurre con el
gestor de paquetes que es un programa en sí mismo que puede instalar toda
la gama de aplicaciones que se necesiten. En este sentido, resulta interesantedestacar que Windows anunció en 2020 su propio gestor de paquetes Winget,
al más puro estilo de Linux.
No he encontrado inconvenientes bajo mi humilde punto de vista. Cada
tecnología finaliza instalando la aplicación que el usuario final necesita, sin
demasiados conocimientos de informática
