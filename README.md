# Playbook sencillo

En este ejercicio realizaré las siguientes tareas:

1. Preparar una máquina virtual en KVM que es la que configuraré de forma automática con ansible.
2. Crear un playbook que realice las siguientes tareas de forma automática:
- Crear un usuario en el servidor remoto que tenga mi nombre.
- Descargar el fichero desde la url https://wordpress.org/latest.zip.
- Descomprimir ese fichero en el home del usuario creado anteriormente.
- Instalar el paquete mariadb.
- Crear una base de datos que se llamará larap_wordpress.
- Crear un usuario que se llamará larap que tenga privilegios sobre la base de datos.
- Clonar el repositorio: https://github.com/josedom24/ansible_ejemplos.giten el home del usuario creado en el primer punto.
