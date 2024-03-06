*Probado en Debian

INSTALACION PREVIA

$sudo apt install dialog   - instalar dialog
$touch /usr/bin/smenu      - crear archivo
$chmod +x /usr/bin/smenu   - importante dar permisos
$vim /usr/bin/smenu        - para modificar


PASOS PARA CREAR EL MENÚ:

1) Crear los scripts que desee que el usuario ejecute y dejarlos en un path determinado
2) Ubicar smenu en /usr/bin/
3) Modificar el archivo smenu para que ejecute los scripts
4) Agregar en:
   /home/USUARIO/.bash_profile
la siguiente línea:
   exec /usr/bin/smenu
