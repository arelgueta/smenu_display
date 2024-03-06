*Probado en Debian

PASOS PARA CREAR EL MENÚ:

1) Crear los scripts que desee que el usuario ejecute y dejarlos en un path determinado
2) Ubicar smenu en /usr/bin/
3) Modificar el archivo smenu para que ejecute los scripts
4) Agregar en:
   /home/USUARIO/.bash_profile
la siguiente línea:
   exec /usr/bin/smenu
