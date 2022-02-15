Crear un entorno virtual
Para crear un entorno virtual, llama al módulo. El módulo espera un nombre como argumento venv.

Sigue estos pasos:

Desde tu terminal ve al directorio donde deseas guardar tu proyecto. (Documentos/TuFolderPreferido) Ejemplo en windows: cd Documents/TuFolderPreferido

Utiliza el siguiente comando para llamar al módulo venv. El comando difiere ligeramente dependiendo de tu sistema operativo.

En consola: python3 -m venv env

Donde:

python3: La versión de python a utilizar.
venv: Llamada al módulo venv conocido como virtual environment.
env: Nombre de nuestro entorno virtual.
En este punto, se crean algunos directorios:
/env
  /bin
  /include
  lib
  