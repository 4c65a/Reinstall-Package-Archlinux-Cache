# Install-Package-Archlinux-Cache
Estos pasos son para instalar paquetes que fueron borrados del sistema.
Ir a la carpeta pkg.
```bash
cd  /var/cache/pacman/pkg
```
Buscar el paquete necesario.
```bash
unzip-6.0-21-x86_64.pkg.tar.zst
```
Y luego usar este comando.
```bash
sudo pacman -U unzip-6.0-21-x86_64.pkg.tar.zst
```
