### *Un servidor Linux está muy ralentizado y tú como administrador de sistemas necesitas saber que procesos están colapsando la máquina. ¿Qué harías?*

Primeramente intentar identificar algún proceso,aplicación o servicio que pueda estar consumiendo más recursos de los que necesita. Esto podría hacerse desde la línea de comandos con la operación *top*. También una revisión del uso del ancho de banda de red y confirmar que coinciden las peticiones de red con el proceso que consume recursos.
A partir de ahí identificar el propietario del proceso, si éste corresponde al administrador proceder a su solución. En caso de pertenecer a otro proceso de la empresa, consensuar cuál es la mejor forma de recuperar un nivel de servicio adecuado ya que puede el servicio sea bien crítico bien esencial.
Caso especial y de mayor análisis requerirá si el software es el virtualizador de máquinas (ex: VirtualBox, VMWare,...).

