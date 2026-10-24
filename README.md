# NuevoHub - canal publico de actualizaciones

Este repositorio solo contiene **archivos compilados** y el manifiesto `updates.json`.
No hay codigo fuente aqui.

- `updates.json`: version disponible, archivo y SHA-256 de cada equipo.
- `assets/`: firmware del hub (por variante de hardware) y APK de la app.

La app lee `updates.json`, verifica el SHA-256 y descarga el archivo que corresponde.
El repositorio del proyecto es privado; este canal existe solo para distribuir binarios.
