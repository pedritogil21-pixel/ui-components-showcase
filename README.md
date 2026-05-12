# UI Components Showcase

Showcase de componentes UI animados, pensados para ser grabados en video vertical (9:16) y publicados en redes sociales (TikTok, Reels, Shorts).

Cada componente vive en su propia carpeta y se ejecuta como una página HTML autocontenida — sin frameworks, sin build step, solo HTML + CSS + JavaScript vanilla. Lo único externo permitido son fuentes de Google Fonts cuando hacen falta.

## Componentes

### Loaders

- **[Liquid Orb Constellation Loader](./loaders/liquid-orb-constellation/)** — Orbe central con glassmorphism, tres partículas orbitando en planos 3D distintos y líneas de conexión SVG que se actualizan en tiempo real. Ciclo cromático de 8s entre púrpura, magenta y cyan.

## Cómo previsualizar

Con GitHub Pages activado en este repositorio, cada componente queda disponible en:

```
https://<usuario>.github.io/ui-components-showcase/<categoría>/<componente>/
```

Por ejemplo: `https://pedritogil21-pixel.github.io/ui-components-showcase/loaders/liquid-orb-constellation/`

## Filosofía

- Un archivo `index.html` por componente, con CSS y JS embebidos.
- Cero librerías externas (excepto fuentes).
- Variables CSS al inicio para que cualquier paleta o timing sea fácil de tunear.
- Solo `transform` y `opacity` en las animaciones pesadas para mantener 60 fps.
- Optimizado para verse impecable en pantalla móvil vertical.
