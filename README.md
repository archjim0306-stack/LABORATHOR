# Laboratorio de aprendizaje

App web (PWA) para aprender SAP PP, Ingeniería Industrial, SolidWorks, Power BI, Lean Six Sigma, Inglés, Programación e Indicadores técnicos.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `laboratorio`.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. En el repositorio: **Settings > Pages > Build and deployment > Source: Deploy from a branch**, rama `main`, carpeta `/ (root)` y **Save**.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/laboratorio/`.

## Instalar como app

- **iPhone (Safari):** abre la dirección, toca Compartir y luego **Agregar a pantalla de inicio**.
- **Android (Chrome):** abre la dirección y toca **Instalar app** en el menú.

Funciona sin internet después de la primera visita.

## Actualizar

1. Reemplaza `index.html` con la versión nueva.
2. En `sw.js` cambia `VERSION` (por ejemplo, de `laboratorio-v1` a `laboratorio-v2`).
3. Sube los cambios. La app se actualiza al abrirla con conexión.

## Datos

El avance se guarda en el navegador de cada dispositivo (localStorage). No se sincroniza entre dispositivos. Borrar los datos del navegador borra el avance.
