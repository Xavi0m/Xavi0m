### Hi there 👋

<!--
**Xavi0m/Xavi0m** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

https://blackarch.org/downloads.html#install-repo

nstalación sobre ArchLinux
BlackArch Linux es compatible con instalaciones Arch existentes / normales. Actúa como un repositorio de usuarios no oficial. A continuación, encontrará instrucciones sobre cómo instalar BlackArch de esta manera.

# Ejecute https://blackarch.org/strap.sh como root y siga las instrucciones.

$ curl -O https://blackarch.org/strap.sh
# Verifique la suma SHA1

$ echo f014a9d2884252349241a8bde76a539fad9fd1bb strap.sh | sha1sum -c
# Establecer bit de ejecución

$ chmod + x strap.sh
# Ejecutar strap.sh

$ sudo ./strap.sh
# Habilite multilib siguiendo https://wiki.archlinux.org/index.php/Official_repositories#Enabling_multilib y ejecute:

$ sudo pacman -Syu
Ahora puede instalar herramientas desde el repositorio de Blackarch.
# Para enumerar todas las herramientas disponibles, ejecute

$ sudo pacman -Sgg | grep blackarch | cut -d '' -f2 | sort -u
# Para instalar todas las herramientas, ejecute

$ sudo pacman -S blackarch
# Para instalar una categoría de herramientas, ejecute

$ sudo pacman -S blackarch- <categoría>
# Para ver las categorías de Blackarch, ejecute

$ sudo pacman -Sg | grep blackarch
# Nota: tal vez sea necesario sobrescribir ciertos paquetes al instalar las herramientas de Blackarch. Si
# experimenta errores de "no se pudo confirmar la transacción", use los interruptores --needed y --overwrite
# Por ejemplo:

$ sudo pacman -Syyu --needed blackarch --overwrite = '*'
La lista completa de herramientas del repositorio BlackArch Linux se puede encontrar aquí .

-->
