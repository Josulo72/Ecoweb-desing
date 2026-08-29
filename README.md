# Ecoweb-desing

Pack unificado de skills de diseño frontend para Claude Code y otros agentes de IA.
Combina en un solo repo las dos mejores skills anti-slop del ecosistema, listas para
instalar juntas con un comando.

## Qué incluye

| Skill | Origen | Qué hace |
|---|---|---|
| **design-skill** | [TudeOrangBiasa/design-skill](https://github.com/TudeOrangBiasa/design-skill) | Partner de diseño medido con evals: detecta 10 "tells" de AI-slop, audita con puntuación /24, entrevista antes de construir. Comandos: `detect`, `audit`, `deslop`, `shape`, `craft`. Fusiona el routing de [pbakaus/impeccable](https://github.com/pbakaus/impeccable) con la filosofía de motion de [Emil Kowalski](https://animations.dev). |
| **design-taste-frontend** | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) (v2) | Dirección estética con tres diales configurables 1-10: `DESIGN_VARIANCE`, `MOTION_INTENSITY`, `VISUAL_DENSITY`. Infiere el lenguaje de diseño desde el brief y evita interfaces con aspecto de plantilla. |

## Instalación

Todo el pack:

```bash
npx skills add Josulo72/Ecoweb-desing
```

Una skill concreta:

```bash
npx skills add Josulo72/Ecoweb-desing --skill "design-skill"
npx skills add Josulo72/Ecoweb-desing --skill "design-taste-frontend"
```

Añade `-a claude-code -g` para instalación global en Claude Code.

## Cuándo usar cada una

- **design-skill** — auditar UI existente ("esto parece hecho por una IA"), matar slop
  con alternativas positivas, o construir desde cero con entrevista previa.
- **design-taste-frontend** — landings, portfolios y rediseños donde ya sabes la
  dirección y quieres regular experimentación de layout, motion y densidad.

## Licencias y atribución

Cada skill conserva la licencia MIT de su repositorio original (ver `LICENSE` dentro
de cada carpeta). Todo el crédito del contenido de las skills es de sus autores:
[TudeOrangBiasa](https://github.com/TudeOrangBiasa), [Leonxlnx](https://github.com/Leonxlnx),
[Paul Bakaus](https://github.com/pbakaus) y [Emil Kowalski](https://github.com/emilkowalski).
Este repo solo las empaqueta juntas para instalación conjunta.
