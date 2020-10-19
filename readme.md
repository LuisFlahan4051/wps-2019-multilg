Descargar WPS de repositorios deepin:
http://packages.deepin.com/deepin/pool/non-free/w/wps-office-2019/
    http://packages.deepin.com/deepin/pool/non-free/w/wps-office-2019/wps-office-2019_11.1.0.8392_amd64.deb
ALT DE:
https://facilitarelsoftwarelibre.blogspot.com/2019/10/como-instalar-wps-office-2019-32-y-64.html
    https://mirror.yandex.ru/mirrors/deepin/packages/pool/non-free/w/wps-office-2019/
O:  https://mega.nz/folder/WhdGUCbD#AScUhE8HB_GI457CW2n3FQ


Descargar lod Dicts y Mui:
https://github.com/wachin/wps-office-all-mui-win-language/releases/tag/11.2.0.9255
----------------------------------------------------------
Nota: Si se va a emplear el explorador de archivos, tratar de ser muy especifico con los ficheros a los que le aplicas permisos(puedes descomponer el sistema).
$   sudo chmod 777 -R /dir

Lo mejor sería hacer todos los movimientos mediante consola de comandos.
$   sudo mv dir-origin/ dir-dest/
$   sudo cp dir/ dir/
$   sudo rm file.file
$   sudo rmdir dir/

Mover todas las carpetas a sus respectivos contenedores en sistema.
Los dicts y los mui se mueven a:
/opt/kingsoft/wps-office

Las fonts se mueven a:
~/.fonts

En caso de que sea Fedora.
Se tienen que comparar los archivos del .deb con la versión actual descargada de la página oficial. Para poner los .desktop.
