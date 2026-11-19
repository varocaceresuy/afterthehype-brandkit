# After the Hype — Guía de marca para IA

Identidad **Lima y Azul** · v1.2 · Identidad by Alvaro Cáceres · 2026

> Usa este documento como contexto para crear cualquier pieza de After the Hype: presentaciones, webs, apps, newsletters, redes sociales o documentos. Sigue estas reglas siempre; si algo no está definido aquí, elige la opción más sobria y con mejor contraste. Valores exactos en `AfterTheHype_tokens.json`.

## 1. Principios

- Midnight Navy (`#111827`) es el color principal. Electric Lime (`#DBFF00`) es el acento.
- **Botones y controles (action):** en Dark van en Electric Lime con texto Midnight Navy; en Light van en Midnight Navy con texto Cloud White. Electric Lime nunca lleva texto blanco.
- En Light, Electric Lime solo se usa en chips, badges, etiquetas y destacados, siempre con texto Midnight Navy. Nunca como color de texto sobre fondos claros.
- Todo espaciado, radio y tamaño en múltiplos de 8 px (4 px solo para ajustes finos, como icono-texto).
- Usa tokens semánticos, no HEX sueltos, para que todo funcione en Light y Dark.
- Fondo de página: Midnight Navy 950 en Dark, Midnight Navy 100 en Light.
- Tipografía única: Inter.

## 2. Logo

- **Versiones:** horizontal (principal), vertical e isotipo (símbolo AH solo).
- **Colores aprobados del logo:** Navy `#111827`, Black `#000000`, White `#F7FAFC`. Nunca Lima ni otros colores.
- **Combinaciones aprobadas:**
  - Black sobre Cloud White
  - Navy sobre Electric Lime
  - White sobre Midnight Navy
  - Navy sobre Sky
- **Área de respeto:** como mínimo, la altura del isotipo alrededor del logo.
- **No:** deformar, recolorear, rotar, aplicar sombras, degradados o efectos, ni usarlo con bajo contraste.
- **Archivos:** `assets/01_Logo-Horizontal`, `02_Logo-Vertical`, `03_Isotipo` (SVG, PDF, PNG, JPG) y `04_Favicon-AppIcon`.

## 3. Color

### Paleta primaria

| Nombre | Token | HEX | RGB | CMYK |
| --- | --- | --- | --- | --- |
| Cloud White | `cloud-white` | `#F7FAFC` | 247, 250, 252 | 2, 1, 0, 1 |
| Electric Lime | `electric-lime` | `#DBFF00` | 219, 255, 0 | 14, 0, 100, 0 |
| Midnight Navy | `midnight-navy` | `#111827` | 17, 24, 39 | 56, 38, 0, 85 |
| Sky Blue | `sky` | `#59C1F2` | 89, 193, 242 | 63, 20, 0, 5 |

Color secundario de apoyo para links en Light: Deep Sky `#1E6E96`.

### Escala Midnight Navy (base de la interfaz)

| Paso | HEX |
| --- | --- |
| `midnight-navy/100` | `#FFFFFF` |
| `midnight-navy/200` | `#F9FAFB` |
| `midnight-navy/250` | `#F3F4F6` |
| `midnight-navy/300` | `#E5E7EB` |
| `midnight-navy/400` | `#9CA3AF` |
| `midnight-navy/500` | `#6B7280` |
| `midnight-navy/600` | `#4B5563` |
| `midnight-navy/700` | `#374151` |
| `midnight-navy/800` | `#1F2937` |
| `midnight-navy/900` (Primary 03) | `#111827` |
| `midnight-navy/950` | `#0C111B` |

### Escala Zinc (superficies secundarias, divisores, deshabilitado)

| Paso | HEX |
| --- | --- |
| `zinc/100` | `#F4F4F8` |
| `zinc/200` | `#E4E4E7` |
| `zinc/300` | `#D4D4D8` |
| `zinc/400` | `#A1A1AA` |
| `zinc/500` | `#71717A` |
| `zinc/600` | `#52525B` |
| `zinc/700` | `#3F3F46` |
| `zinc/800` | `#27272A` |
| `zinc/900` | `#18181B` |

### Tokens semánticos

| Token | Light | Dark | Uso |
| --- | --- | --- | --- |
| `bg/page` | `midnight-navy/100` #FFFFFF | `midnight-navy/950` #0C111B | Fondo de página |
| `bg/subtle` | `midnight-navy/200` #F9FAFB | `midnight-navy/900` #111827 | Secciones alternas, sidebars |
| `bg/surface` | `midnight-navy/100` #FFFFFF | `midnight-navy/900` #111827 | Cards, modales, popovers (con borde) |
| `bg/muted` | `midnight-navy/250` #F3F4F6 | `midnight-navy/800` #1F2937 | Inputs, hover de filas, chips |
| `bg/disabled` | `zinc/200` #E4E4E7 | `zinc/800` #27272A | Controles deshabilitados |
| `border/default` | `midnight-navy/300` #E5E7EB | `midnight-navy/800` #1F2937 | Bordes y divisores |
| `border/strong` | `midnight-navy/400` #9CA3AF | `midnight-navy/700` #374151 | Bordes de inputs, separadores marcados |
| `text/primary` | `midnight-navy/900` #111827 | `cloud-white` #F7FAFC | Títulos y texto principal |
| `text/secondary` | `midnight-navy/600` #4B5563 | `midnight-navy/400` #9CA3AF | Texto de apoyo |
| `text/muted` | `midnight-navy/500` #6B7280 | `midnight-navy/500` #6B7280 | Placeholders, metadatos |
| `text/disabled` | `zinc/400` #A1A1AA | `zinc/600` #52525B | Texto deshabilitado |
| `action/bg` | `midnight-navy/900` #111827 | `electric-lime` #DBFF00 | Botón principal, controles activos, barras y progreso |
| `action/fg` | `cloud-white` #F7FAFC | `midnight-navy/900` #111827 | Texto e iconos sobre action/bg |
| `highlight/bg` | `electric-lime` #DBFF00 | `electric-lime` #DBFF00 | Chips, badges, etiquetas y destacados (nunca botones en Light) |
| `highlight/fg` | `midnight-navy/900` #111827 | `midnight-navy/900` #111827 | Texto sobre highlight/bg |
| `link` | `deep-sky` #1E6E96 | `sky` #59C1F2 | Enlaces e información |
| `focus/ring` | `sky` #59C1F2 | `sky` #59C1F2 | Anillo de foco (2 px, offset 2 px) |

## 4. Tipografía

- **Familia:** Inter (gratuita, licencia SIL Open Font License). Google Fonts: https://fonts.google.com/specimen/Inter
- **Font stack:** `"Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif`
- **Pesos:** Light 300, Regular 400, Medium 500, Semi Bold 600, Bold 700. Títulos en Semi Bold, texto en Regular, labels y botones en Medium.

### Escala UI

| Estilo | Tamaño | Interlineado | Peso | Tracking | Uso |
| --- | --- | --- | --- | --- | --- |
| `display` | 56 px | 64 px | 600 | -0.02em | Hero y portadas |
| `h1` | 40 px | 48 px | 600 | -0.02em | Título de página |
| `h2` | 32 px | 40 px | 600 | -0.01em | Título de sección |
| `h3` | 24 px | 32 px | 600 | -0.01em | Título de card o bloque |
| `h4` | 20 px | 28 px | 600 | 0 | Subtítulo |
| `body-lg` | 18 px | 28 px | 400 | 0 | Intro, texto destacado |
| `body` | 16 px | 24 px | 400 | 0 | Texto base |
| `body-sm` | 14 px | 20 px | 400 | 0 | Texto secundario, tablas |
| `label` | 14 px | 16 px | 500 | 0 | Botones, labels de formulario |
| `caption` | 12 px | 16 px | 500 | 0.01em | Metadatos, ayudas |

## 5. Espaciado y grid

| Token | Valor | Uso |
| --- | --- | --- |
| `space-0` | 0 px | Sin espacio |
| `space-0.5` | 4 px | Solo ajustes finos (icono-texto) |
| `space-1` | 8 px | Separación mínima |
| `space-2` | 16 px | Padding de controles, gap de listas |
| `space-3` | 24 px | Padding de cards |
| `space-4` | 32 px | Separación entre bloques |
| `space-5` | 40 px | Separación entre grupos |
| `space-6` | 48 px | Padding de secciones (móvil) |
| `space-8` | 64 px | Padding de secciones (desktop) |
| `space-10` | 80 px | Separación entre secciones |
| `space-12` | 96 px | Hero y portadas |
| `space-16` | 128 px | Grandes respiros |

Contenedor máximo: 1280 px.

| Breakpoint | Ancho | Columnas | Gutter | Margen |
| --- | --- | --- | --- | --- |
| sm | ≥ 640 px | 4 | 16 px | 16 px |
| md | ≥ 768 px | 8 | 24 px | 32 px |
| lg | ≥ 1024 px | 12 | 24 px | 48 px |
| xl | ≥ 1280 px | 12 | 32 px | 64 px |

## 6. Radios y elevación

| Token | Valor | Uso |
| --- | --- | --- |
| `radius-none` | 0 px | Tablas, imágenes a sangre |
| `radius-sm` | 8 px | Botones, inputs, chips |
| `radius-md` | 16 px | Cards, menús, popovers |
| `radius-lg` | 24 px | Modales, paneles |
| `radius-xl` | 32 px | Bloques hero, secciones destacadas |
| `radius-full` | 9999 px (full) | Pills, avatares, toggles |

| Sombra | Valor | Uso |
| --- | --- | --- |
| `shadow-e1` | `0 1px 2px rgba(17,24,39,.06), 0 1px 1px rgba(17,24,39,.04)` | Cards en reposo |
| `shadow-e2` | `0 4px 16px rgba(17,24,39,.08)` | Hover, menús, popovers |
| `shadow-e3` | `0 16px 48px rgba(17,24,39,.14)` | Modales, diálogos |

Las sombras solo se usan en Light. En Dark la profundidad se resuelve con el siguiente tono de superficie y un borde de 1 px (`border/default`).

## 7. Imágenes

**Tagline:** “Delivery obsessed, Human powered.”

**Fotografía** (referencia: `assets/05_Imagery/ATH_Foto_Delivery-Obsessed.jpg`)

- Personas reales trabajando, en momentos espontáneos. Nada de poses de banco de imágenes.
- Luz natural o de escena, con contraste y sombras; tonos neutros y fríos.
- Un solo acento de color de la marca en la escena (Sky, Electric Lime o Midnight Navy).
- Aire para el tagline o un mensaje corto, en Inter y en blanco sobre zonas oscuras.

**Fondos abstractos** (`ATH_Gradiente_Radial.jpg`, `ATH_Gradiente_Grano.jpg`)

- Gama Electric Lime, verde y Sky, sobre Cloud White o Midnight Navy.
- Desenfocados, con grano sutil o con formas de vidrio translúcido; sin bordes duros ni ilustraciones planas.
- Texto en Midnight Navy sobre zonas claras; blanco o Electric Lime sobre zonas oscuras.
- Para portadas, aperturas de slides, heroes web, fondos de redes y video. Nunca detrás de textos largos.

**Video** (`ATH_Gradiente_Animado.mp4`): gradiente animado en loop y sin sonido para heroes web, pantallas de evento, stories y reels. Encima solo el logo o una frase corta. MP4 H.264 con imagen de respaldo.

**Aplicaciones:** isotipo grande y recortado en merch y señalética; lockup horizontal en papelería y pantallas; logo Black o Navy en soportes claros y White en oscuros.

## 8. Iconografía

- **Librería:** Lucide (https://lucide.dev), gratuita, licencia ISC. Plugin de Figma “Lucide Icons”; paquetes `lucide-react`, `lucide-vue-next`, `lucide`.
- **Trazo:** 1.5 px, esquinas redondeadas, sin rellenos.
- **Tamaños:** 16, 20 y 24 px sobre grilla de 24 px.
- **Color:** hereda el del texto (`text/secondary` en reposo, `text/primary` activo, `action/fg` sobre `action/bg`).
- **Etiquetas:** Inter Medium; separación ícono-texto 8 px (4 px en botones pequeños).
- **Alternativas:** Phosphor (Regular) o Heroicons (Outline) si falta un ícono.

## 9. Componentes base (criterio)

- **Botón principal:** fondo `action/bg`, texto `action/fg`, `radius-sm` (8 px), alto 40–48 px, padding horizontal 16–24 px, estilo `label`.
- **Botón secundario:** transparente, borde 1 px `border/strong`, texto `text/primary`.
- **Input:** fondo `bg/muted`, borde `border/strong`, `radius-sm`, alto 40–48 px; foco con anillo `focus/ring` de 2 px.
- **Card:** fondo `bg/surface`, borde `border/default`, `radius-md` (16 px), padding `space-3` (24 px); en Light, `shadow-e1`.
- **Chip o badge:** `highlight/bg` con texto `highlight/fg`, `radius-full`, estilo `caption`.

## 10. Uso correcto

**Sí**

- Logo White sobre Midnight Navy: La versión principal en fondos oscuros.
- Logo Navy sobre Electric Lime: Para piezas de impacto y destacados.
- Respetar el área de respeto: Mínimo la altura del isotipo alrededor del logo.
- Logo Navy sobre Sky: Las cuatro combinaciones aprobadas, siempre con contraste alto.
- Botones según el tema: Dark: Lima con texto Navy. Light: Navy con texto Cloud White.
- Lima como acento en Light: Chips, badges y destacados, con texto Midnight Navy.

**No**

- No deformar: Nunca estirar ni cambiar las proporciones.
- No recolorear: Solo Navy, Black o White. Nunca Lima ni colores externos.
- No aplicar efectos: Sin sombras, degradados, contornos ni brillos.
- No usar con bajo contraste: Navy sobre fondos oscuros pierde lectura.
- No rotar: El logo siempre va horizontal.
- No Lima con texto blanco ni como texto: No cumple contraste. En Light, los botones van en Navy.

## 11. Recursos

- **Brand Kit online:** https://afterthehype-brandkit.vercel.app
- **Figma (presentación de marca):** https://www.figma.com/design/ZnUQJS15lSAZGtDVNkWWzd/Brand-Guidelines-AfterTheHype?node-id=175-4408&t=JAXqKjfrsKxNGAOW-1
- **Tokens:** `AfterTheHype_tokens.json`

## 12. Cómo pedirle algo a una IA

```
Usa la guía de marca de After the Hype adjunta (AfterTheHype_brand.md y AfterTheHype_tokens.json).
Crea [pieza: landing / slide / post / newsletter] en modo [Dark / Light] para [objetivo].
Respeta los tokens semánticos, Inter, la escala de 8 px, íconos Lucide y la regla de botones según el tema.
```
