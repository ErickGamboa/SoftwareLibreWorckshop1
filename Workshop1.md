
# Erick Josué Gamboa Rodríguez
# Instalando un servidor web LAMP
- Instalar vagrant
- Instalar virtual box
- Instalar visual studio code
- Activar capacidad de virtualización en el bios del sistema operativo de windows
- Desactivar el secure boot en la maquina anfitriona
- Ejecutar el comando -> `vagrant init debian/bullseye64`
- Se puede realizar configuraciones personalizadas en el vagrantfile que este comando crea (Opcional)
- En el archivo `c:\windows\system32\drivers\etc\hosts` se setea el nombre del sitio web que se va a relacionar con la Ip
- Ejecutar el comando `ssh vagrant@hostNombre` en caso de no saber la contraseña del sistema
-Se debe de configurar el alias en el archivo bashrc
-Ejecutar `source .bachsrc` para que funcionen los alias
-Ejecutar `sudo apt-get update` para ejecutar los paquetes del sistema
-Ejecutar el comando `sudo apt-get vim vim-nox curl git apache2 mariadb-server mariadb-client php7.4 php7.4-bcmath php7.4-curl php7.4-json php7.4-mystring php7.4-mysql php7.4-xml` para instalar elementos importantes
