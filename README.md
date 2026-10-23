# Mi Dinero 💰

Aplicación web sencilla para registrar ingresos y gastos, consultar movimientos por fecha y revisar el balance diario y acumulado. Está preparada para publicarse con GitHub Pages y puede instalarse como aplicación web en navegadores compatibles.

## Funciones

- Registrar ingresos y gastos con descripción e importe.
- Fecha del día seleccionada automáticamente al abrir la aplicación.
- Consultar los movimientos de una fecha desde el calendario mensual.
- Ver el balance diario y el saldo acumulado hasta la fecha seleccionada.
- Guardar los movimientos en el almacenamiento local del navegador.
- Diseño adaptable a celulares y computadoras.
- Caché básica para abrir la aplicación sin conexión después de la primera carga, en navegadores compatibles.

## Archivos

- `index.html`: interfaz y lógica principal.
- `manifest.json`: configuración para instalar la aplicación web.
- `sw.js`: caché y soporte básico sin conexión.
- `icon-192.png` y `icon-512.png`: iconos de la aplicación.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio. No subas solamente el README.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)` y guarda.
6. Espera a que termine la publicación y abre la dirección que GitHub Pages muestra.

## Datos y privacidad

Los movimientos se guardan en el almacenamiento local del navegador y no se envían a un servidor. Por eso, no se sincronizan automáticamente entre dispositivos o navegadores. Borrar los datos del sitio, usar otro navegador o cambiar de dispositivo puede hacer que no aparezcan los registros anteriores. Exportación o copia de seguridad automática no está incluida.

## Actualizaciones

Después de subir cambios, recarga la página. Si el navegador sigue mostrando una versión anterior por la caché, cierra la aplicación y vuelve a abrirla o borra la caché del sitio desde los ajustes del navegador.

## Licencia

Puedes adaptar este proyecto para uso personal.
