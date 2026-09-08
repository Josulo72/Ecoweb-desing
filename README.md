<p align="center">
  <img src="assets/logo.png" alt="Ecoweb-desing" width="380" />
</p>

# Ecoweb-desing

Pack completo de skills de diseño frontend para Claude Code y otros agentes de IA.
Reúne en un solo repo lo mejor del ecosistema anti-slop — impeccable, taste-skill,
las skills de Emil Kowalski y las guías de Vercel — listo para instalar con un comando.

> **Este repo no contiene trabajo propio.** Es una recopilación de skills de terceros, empaquetadas juntas para poder instalarlas con un solo comando. Cada una conserva su licencia MIT y todo el crédito es de sus autores — ver [Licencias y atribución](#licencias-y-atribución) al final.

## Instalación

Todo el pack:

```bash
npx skills add Josulo72/Ecoweb-desing
```

Una skill concreta (por su install name):

```bash
npx skills add Josulo72/Ecoweb-desing --skill "impeccable"
```

Añade `-a claude-code -g` para instalación global en Claude Code.

## Qué incluye (19 skills)

### Núcleo — construir y auditar

| Skill | Origen | Qué hace |
|---|---|---|
| **design-skill** | [TudeOrangBiasa/design-skill](https://github.com/TudeOrangBiasa/design-skill) | Partner de diseño medido con evals: 10 tells de AI-slop, auditoría con puntuación, entrevista antes de construir. `detect`, `audit`, `deslop`, `shape`, `craft`. |
| **design-taste-frontend** | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) v2 | Dirección estética con diales `DESIGN_VARIANCE` / `MOTION_INTENSITY` / `VISUAL_DENSITY`. |
| **impeccable** | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | La skill insignia de calidad de diseño: polish, typeset, colorize, animate y ~20 disciplinas más. |
| **web-design-guidelines** | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | Guías de interfaces web de Vercel. |

### Motion — Emil Kowalski ([animations.dev](https://animations.dev))

| Skill | Qué hace |
|---|---|
| **emil-design-eng** | Filosofía de design engineering: pulir UI, componentes, animaciones. |
| **animate** | Construir animaciones web con criterio (React/Next.js). |
| **animation-vocabulary** | Vocabulario de motion: springs, easings, duraciones. |
| **find-animation-opportunities** | Detectar dónde una animación aporta (y dónde no). |
| **improve-animations** | Mejorar animaciones existentes. |
| **review-animations** | Auditar animaciones como lo haría Emil. |

### Direcciones visuales — taste-skill

| Skill | Qué hace |
|---|---|
| **soft-skill** | UI premium calmada: contraste suave, whitespace, spring motion. |
| **minimalist-skill** | UI editorial tipo Notion/Linear: paleta contenida, estructura nítida. |
| **brutalist-skill** | Lenguaje duro: tipografía suiza, contraste fuerte, layout experimental. |
| **redesign-skill** | Proyectos existentes: auditar primero, luego arreglar layout/jerarquía. |
| **output-skill** | Fuerza salida completa, sin placeholders. |

### Generación de imágenes — taste-skill

| Skill | Qué hace |
|---|---|
| **image-to-code-skill** | Pipeline imagen → análisis → código. |
| **imagegen-frontend-web** | Comps de webs: heros, landings, multi-sección. |
| **imagegen-frontend-mobile** | Pantallas y flujos móviles iOS/Android. |
| **brandkit** | Boards de identidad: logos, paletas, tipografía. |

## Cuándo usar cada una

- Auditar UI existente o matar slop → **design-skill** / **impeccable**
- Landing nueva con dirección clara → **design-taste-frontend** + una dirección visual
- Animaciones → las seis de **Emil Kowalski**
- Referencias visuales antes de codificar → **imagegen-\*** + **image-to-code-skill**

## Licencias y atribución

Cada skill conserva la licencia MIT de su repositorio original (ver `LICENSE` dentro
de cada carpeta). Todo el crédito del contenido es de sus autores:
[Paul Bakaus](https://github.com/pbakaus), [Emil Kowalski](https://github.com/emilkowalski),
[Leonxlnx](https://github.com/Leonxlnx), [TudeOrangBiasa](https://github.com/TudeOrangBiasa)
y [Vercel Labs](https://github.com/vercel-labs). Este repo solo las empaqueta juntas
para instalación conjunta.
