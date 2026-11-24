---
name: "Entreno"
description: "Sistema de diseño atlético, preciso y accesible para análisis de rendimiento deportivo, carga de entrenamiento y metas con soporte nativo para tema claro y oscuro."
---

## Overview

**Entreno** es una plataforma de análisis deportivo y seguimiento de condición física con estética **Sport-Tech moderna, gráfica y vibrante**. Combina telemetría visual inmediata (anillos de preparación, espectros de zonas de pulso, barras animadas) con iconografía expresiva y explicaciones claras de cada métrica.

El estilo visual sigue un enfoque **Moderno / Gráfico con acentos vibrantes**: superficies limpias con alto contraste, tarjetas con presencia visual y micro-interacciones fluidas, y un diseño **mobile-first** que escala con naturalidad a escritorio.

## Colors

La paleta combina un **Esmeralda Deportivo** (`#006450` / `#007F66`) con un **Coral Energía** (`#B02E00` / `#FC5929`) y un **Azul Telemetría** (`#005C8E` / `#2075AE`), además de acentos gráficos (`accent-mint`, `accent-coral`, `accent-sky`, `accent-amber`) para anillos de progreso, zonas de frecuencia cardíaca y gráficas animadas.

- **Primary:** Acciones principales, estado de forma óptimo, anillos de preparación y navegación activa.
- **Secondary:** Carga aguda, picos de intensidad, zonas altas y eventos objetivo.
- **Tertiary:** Métricas de ritmo, resistencia aeróbica y guías de sincronización.
- **Surface & Containers:** Jerarquía por elevación tonal (`surface` → `surface-container-low` → `surface-container` → `surface-container-high`) tanto en modo claro como en modo oscuro.
- **Status:** `success`, `warning` e `info` comunican estado fisiológico o de sincronización; nunca se usan como decoración.

```yaml
colors:
  success: "#15803D"
  warning: "#B45309"
  info: "#0369A1"
  accent-mint: "#10B981"
  accent-coral: "#FF5722"
  accent-sky: "#0EA5E9"
  accent-amber: "#F59E0B"
  light:
    primary: "#006450"
    on-primary: "#FFFFFF"
    primary-container: "#007F66"
    on-primary-container: "#D0FFED"
    secondary: "#B02E00"
    on-secondary: "#FFFFFF"
    secondary-container: "#FC5929"
    on-secondary-container: "#541100"
    tertiary: "#005C8E"
    on-tertiary: "#FFFFFF"
    tertiary-container: "#2075AE"
    on-tertiary-container: "#EEF5FF"
    error: "#BA1A1A"
    on-error: "#FFFFFF"
    error-container: "#FFDAD6"
    on-error-container: "#93000A"
    background: "#F6FAF6"
    on-background: "#181D1B"
    surface: "#F6FAF6"
    surface-dim: "#D6DBD7"
    surface-bright: "#F6FAF6"
    surface-container-lowest: "#FFFFFF"
    surface-container-low: "#F0F5F1"
    surface-container: "#EAEFEB"
    surface-container-high: "#E5E9E5"
    surface-container-highest: "#DFE4E0"
    on-surface: "#181D1B"
    surface-variant: "#D9E5DF"
    on-surface-variant: "#3E4945"
    outline: "#6E7A74"
    outline-variant: "#BDC9C3"
    inverse-surface: "#2C322F"
    inverse-on-surface: "#EDF2EE"
    inverse-primary: "#76D8BB"
  dark:
    primary: "#76D8BB"
    on-primary: "#00382B"
    primary-container: "#007F66"
    on-primary-container: "#D0FFED"
    secondary: "#FFB5A0"
    on-secondary: "#601500"
    secondary-container: "#CA3701"
    on-secondary-container: "#FFECE7"
    tertiary: "#94CCFF"
    on-tertiary: "#003352"
    tertiary-container: "#2075AE"
    on-tertiary-container: "#EEF5FF"
    error: "#FFB4AB"
    on-error: "#690005"
    error-container: "#93000A"
    on-error-container: "#FFDAD6"
    background: "#0F1412"
    on-background: "#DFE4E0"
    surface: "#0F1412"
    surface-dim: "#0F1412"
    surface-bright: "#353A38"
    surface-container-lowest: "#0A0F0D"
    surface-container-low: "#181D1B"
    surface-container: "#1C211F"
    surface-container-high: "#262B29"
    surface-container-highest: "#313633"
    on-surface: "#DFE4E0"
    surface-variant: "#3E4945"
    on-surface-variant: "#BDC9C3"
    outline: "#87938E"
    outline-variant: "#3E4945"
    inverse-surface: "#DFE4E0"
    inverse-on-surface: "#2C322F"
    inverse-primary: "#006B56"
```

## Typography

La tipografía combina **Mona Sans** para titulares y cifras destacadas de rendimiento, **Commissioner** para lectura cómoda en explicaciones de métricas, formularios y guías paso a paso, y **Reddit Mono** para ritmos, frecuencias cardíacas, distancias y marcas de tiempo con alineación tabular (`tabular-nums`).

```yaml
typography:
  display-lg:
    fontFamily: "Mona Sans"
    fontSize: 40px
    fontWeight: 700
    lineHeight: 46px
    letterSpacing: -0.5px
  display-lg-mobile:
    fontFamily: "Mona Sans"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 36px
    letterSpacing: -0.25px
  headline-lg:
    fontFamily: "Mona Sans"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 34px
    letterSpacing: -0.25px
  headline-md:
    fontFamily: "Mona Sans"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 28px
    letterSpacing: 0px
  title-lg:
    fontFamily: "Mona Sans"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 24px
    letterSpacing: 0px
  title-md:
    fontFamily: "Commissioner"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 22px
    letterSpacing: 0px
  body-lg:
    fontFamily: "Commissioner"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0px
  body-md:
    fontFamily: "Commissioner"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 21px
    letterSpacing: 0px
  label-lg:
    fontFamily: "Commissioner"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 20px
    letterSpacing: 0.1px
  label-md:
    fontFamily: "Commissioner"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 16px
    letterSpacing: 0.2px
  mono-lg:
    fontFamily: "Reddit Mono"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 26px
    letterSpacing: 0px
  mono-md:
    fontFamily: "Reddit Mono"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 20px
    letterSpacing: 0px
```

## Layout & Spacing

El diseño es **mobile-first** con una cuadrícula fluida de 4 columnas en móvil (`390px`) y un contenedor centrado de hasta `1200px` con barra lateral de navegación en escritorio (`1280px`). Se utiliza una escala estricta de `4px` / `8px` para que tarjetas, métricas y controles mantengan alineación vertical y horizontal sin saturación visual.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section: 40px
  page-margin: 16px
```

## Elevation & Depth

La jerarquía visual se construye mediante **capas tonales** (`surface` → `surface-container-low` → `surface-container`) y bordes sutiles de `1px` en `outline-variant` cuando es necesario delimitar controles interactivos o tarjetas métricas. Se evitan sombras pesadas y desenfoques de vidrio (`backdrop-blur`), manteniendo una lectura nítida bajo luz solar exterior o en sesiones nocturnas.

## Shapes

Las esquinas redondeadas amplias refuerzan el carácter moderno y dinámico de la interfaz: botones e inputs usan `12px`, tarjetas métricas y paneles principales usan `20px` (`lg`), tarjetas héroe usan `28px` (`xl`), y etiquetas o barras de navegación usan `full`.

```yaml
rounded:
  sm: 8px
  DEFAULT: 12px
  md: 14px
  lg: 20px
  xl: 28px
  full: 9999px
```

## Motion & Micro-interaction

Las transiciones son rápidas y discretas para no retrasar la consulta de métricas. Los cambios de estado (tema claro/oscuro, pestañas, interruptores) duran `150ms`, y la apertura de paneles o modales dura `220ms` con desaceleración suave, respetando siempre `prefers-reduced-motion`.

```yaml
motion:
  state-change:
    duration: 150ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 220ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
  surface-exit:
    duration: 150ms
    delay: 0ms
    timingFunction: cubic-bezier(0.3, 0, 1, 1)
```

## Voice & Content Strategy

- **Tono:** Cercano, claro y objetivo. Explica el "qué significa para ti" de cada métrica (por ejemplo, carga aguda vs. crónica) en una frase llana, sin tecnicismos innecesarios.
- **Capitalización:** Tipo oración (*Sentence case*) en títulos, botones, pestañas y etiquetas.
- **Etiquetas de acción:** Verbos concretos que describen el resultado (`Conectar Strava`, `Subir archivo .FIT`, `Guardar meta deportiva`), nunca "Enviar" o "OK".
- **Privacidad explícita:** Cada dato médico incluye una etiqueta clara indicando que permanece exclusivamente en el dispositivo del usuario.
- **Unidades:** Sistema métrico (`km`, `m+`, `min/km`, `lpm`, `kg`, `cm`) con formato consistente y `tabular-nums`.

## Components

Component implementations live as individual HTML sticker sheet files in
`components/`. Each file contains the canonical, styled HTML components with
`<!-- COMPONENT: name -->` comment markers. Read each file before use.

- **Button** → `@components/button.html` — `button-primary`, `button-icon`, `button-with-icon`
- **Card** → `@components/card.html` — `card-elevated`, `card-action`, `card-interactive`, `card-interactive-2`
- **Input Field** → `@components/input-field.html` — `input-field-text`, `input-field-icon`
- **Tabs** → `@components/tabs.html` — `tabs-horizontal`, `tabs-with-icon`
