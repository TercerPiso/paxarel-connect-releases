# Paxarel Connect

Descargas públicas del script de Paxarel Connect. El código fuente no está en este repositorio.

Cada ambiente tiene un enlace fijo. El archivo se reemplaza cuando cambia la versión; la URL no cambia.

- Desarrollo: https://github.com/TercerPiso/paxarel-connect-releases/releases/download/dev/paxarel-connect-dev.zip
- Producción: https://github.com/TercerPiso/paxarel-connect-releases/releases/download/prod/paxarel-connect-prod.zip

En el dashboard, esas URL van en la variable `VITE_CONNECT_SCRIPT_URL` de Portainer: la de desarrollo en el ambiente dev y la de producción en el ambiente prod. Si la variable está vacía, el botón de Documentación no se muestra.
