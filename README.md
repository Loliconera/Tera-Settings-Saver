## Tera-Settings-Saver 2.1

Tera settings saver es un módulo para TeraToolbox que evita que se restablezcan sus configuraciones, y también le permite transferir fácilmente configuraciones entre personajes/servidores/región

# Comandos
Tenga en cuenta que si utiliza los comandos en el canal proxy o `/8`, ignore el prefijo `!`

Comando | Argumento(s) | Ejemplo | Descripción
---|---|---|---
**!settings** | lock | !settings lock | bloquea su configuración actual
**!settings** | Filename | !settings name-4001 | reemplaza su configuración actual con la configuración del nombre de archivo deseado que se puede encontrar a continuación

los alias disponibles en lugar de `!settings` son `!keybinds`, `!key` y `!set` mantenidos como una opción "heredada" para aquellos que pueden haber usado uno de ellos en el pasado

un ejemplo más claro para aquellos que lo necesitan, digamos, por ejemplo, que tenía un personaje llamado "Kaseatard" del que quería tener la configuración en otro personaje, iría a la carpeta a continuación y encontraría su nombre de archivo y usaría el comando `/8 settings Kaseatard-4001`

(tenga en cuenta, asegúrese de mirar el nombre del archivo y no use los números utilizados en este ejemplo, ya que serán 100% diferentes)

## Los nombres de los archivos se pueden encontrar yendo a `[toolbox folder]/mods/Tera-Settings-Saver/data`
o haciendo clic en `Mostrar carpeta de mods` en la interfaz de usuario de la caja de herramientas y yendo a `/Tera-Settings-Saver/data` desde allí

### Bugs:
Puede potencialmente restablecer una página de conjunto de elementos y glifos si la configuración se ha restablecido (se imprimirá en el chat)
