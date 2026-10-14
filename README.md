# ArcadIA · Guion del taller

Web-guion del taller **ArcadIA: de jugar con la IA a construir la máquina** (RedeSTEAM, Madrid, 14–15 octubre 2026). Equipo FLU · Fab Lab Barcelona: Santi Fuentemilla, Julia Leirado y Xavi Domínguez.

## Estructura

```
index.html                     Guion del taller (agenda, módulos, enlaces, esquema del mando)
assets/canvas/*.pdf            Canvas para imprimir (autoevaluación, tipos y análisis forense, mapeo del juego)
assets/canvas/*.jpg            Previsualización de los canvas
assets/img/                    Fotos de referencia del mando
docs/                          Propuesta completa y agenda
.nojekyll                      Para que GitHub Pages sirva los archivos tal cual
```

## Publicar en GitHub Pages

1. Sube el contenido de esta carpeta a la raíz de un repositorio.
2. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
3. La web queda en `https://<usuario>.github.io/<repo>/`.

Para probar en local: `python3 -m http.server` dentro de la carpeta y abrir `http://localhost:8000`.

ArcadIA es una plataforma-taller diseñada e implementada por el equipo FLU (Santi, Julia y Xavi). La plataforma se ha desarrollado con el modelo Opus 5.5 de Claude, siempre bajo la supervisión y la revisión humana del equipo FLU.
