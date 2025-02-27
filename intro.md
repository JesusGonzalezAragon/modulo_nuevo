# Breve introducción
---
![intro](img/intro.png)

Este módulo permite configurar la partición de dispositivos de almacenamiento utilizando la herramienta de línea de comandos parted.

[!WARNING]
> Solo sirve para crear la partición, no para formatearla, para eso hacemos uso de otro módulo llamado ``ansible.builtin.filesystem``

## Requisitos
* Instalar en las máquinas el paquete ``parted``