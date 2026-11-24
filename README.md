# DonaTrack - Imágenes de insignias

Imágenes públicas de las insignias de DonaTrack, usadas por el flujo de n8n
que publica los logros de los donantes en Discord.

La estructura replica la del frontend (`frontend/src/main/resources/static/img/Insignias/`),
así la ruta relativa que guarda la base (`/img/Insignias/racha_colaborador.png`)
sirve directo pegándole adelante la URL base:

```
https://cdn.jsdelivr.net/gh/LisandroCorrales/donatrack-insignias@main/img/Insignias/racha_colaborador.png
```

`img/Insignias/default.png` es la imagen genérica que se usa cuando una insignia
no tiene imagen o su link está roto.

Si se agrega o cambia una insignia en el frontend, subirla también acá con el mismo nombre.