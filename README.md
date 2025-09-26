# HeroQuiz (contenido)
Este repositorio guarda el **contenido** del juego (imágenes y niveles) para cargarlos dinámicamente desde la app.

## Estructura
```
/images        -> Imágenes de los niveles
/levels        -> Archivos JSON por nivel (001.json, 002.json, ...)
levels.json    -> Índice que lista los niveles y sus rutas
```
### Ejemplo de `levels/001.json`
```json
{
  "id": 1,
  "image": "images/green_hero.png",
  "answer": "Hulk"
}
```

> Nota legal: reemplaza las imágenes por arte propio o con permisos. Evita usar IP con copyright sin autorización.
