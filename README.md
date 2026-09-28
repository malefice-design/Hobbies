# Menú de Hobbies

Catálogo de hobbies clasificado por tipo, dedicación, esfuerzo, espacio y ánimo — con un generador que sugiere qué hacer según cómo estás, y una rueda de azar para cuando no quieres decidir.

## Uso

Es una sola página estática (`index.html`), sin build ni dependencias. Ábrela directo en el navegador o publícala con GitHub Pages (Settings → Pages → Deploy from branch → `main` / `root`).

Todo se guarda en el `localStorage` del navegador — no hay backend ni base de datos.

## Funciones

- **¿Qué hago?**: elige tu ánimo, tipo de actividad, dedicación y espacio disponible, y te sugiere un hobby de tu catálogo.
- **¡Sorpréndeme!**: una rueda de azar con todos tus hobbies.
- **Mi catálogo**: agrega, edita, filtra y elimina hobbies.
- **Configuración**: exporta/importa tu catálogo como CSV.

## Nota sobre exportar/importar CSV

Exportar e importar CSV funcionan en cualquier lugar donde corra esta página (aquí en GitHub Pages, o abierta localmente). Dentro de un Artifact de Claude, exportar usa además una función de descarga propia de ese entorno (`window.claude`); fuera de ahí, cae automáticamente a una descarga normal del navegador.
