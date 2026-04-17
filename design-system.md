# Elenia | Design System Reference

> Drop this file as context when building any Elenia product: dashboards, apps, emails, social media, print, etc.

---

## Brand

| Property | Value |
|---|---|
| Name | **Elenia**: a warm, human name. She is the recepcionista: the friendly presence that answers, attends, and never sleeps. |
| Tagline | Tu recepcionista por WhatsApp |
| Position | La recepcionista #1 de Colombia por WhatsApp |
| Origin | Hecho con orgullo desde Pereira, el corazon del eje cafetero |
| Market | Local service businesses across Colombia (beauty, wellness, barber, professional) |
| Price | $99.000 COP/mes: fixed, all-inclusive, no hidden fees |
| Key rule | **Never say "AI", "IA", "inteligencia artificial", "bot", or "chatbot."** Always say "recepcionista", "recepcionista virtual", or "tu empleada". |

### Logo

- Icon: 💬 emoji on a rounded square (10px radius) with gradient background `linear-gradient(135deg, #25D366, #15803D)`
- Wordmark: "Elenia" in Inter Black (900 weight)
- Minimum icon size: 32px

---

## Colors

### Primary: Green (WhatsApp-aligned)

| Token | Hex | Usage |
|---|---|---|
| `--green-50` | `#ECFDF5` | Badge/tag backgrounds, icon backgrounds |
| `--green-100` | `#D1FAE5` | Subtle highlights |
| `--green-200` | `#A7F3D0` | Badge borders, card hover borders, step borders |
| `--green-400` | `#34D399` | Stat gradient start, dark-mode accent text |
| `--green-500` | `#25D366` | **Primary CTA background**, brand green |
| `--green-600` | `#1B9E4B` | **CTA hover state** |
| `--green-700` | `#15803D` | Tag text on light bg, logo gradient end |
| `--green-800` | `#166534` | Badge text |
| `--green-900` | `#14532D` | CTA section gradient start |

### Neutral: Gray

| Token | Hex | Usage |
|---|---|---|
| `--gray-50` | `#F9FAFB` | Alternate section backgrounds |
| `--gray-100` | `#F3F4F6` | Chevron/tag backgrounds |
| `--gray-200` | `#E5E7EB` | Borders, dividers |
| `--gray-300` | `#D1D5DB` | Secondary button border |
| `--gray-400` | `#9CA3AF` | Muted/meta text, footer headings |
| `--gray-500` | `#6B7280` | Secondary/body text, subtitles |
| `--gray-600` | `#4B5563` | Nav links |
| `--gray-700` | `#374151` | Bold inline text in paragraphs |
| `--gray-800` | `#1F2937` | Strong text, secondary button text |
| `--gray-900` | `#111827` | Body text, headings |
| `--gray-950` | `#030712` | Dark section backgrounds, hero headline |

### Accent (icon/category backgrounds only; always the 50 shade)

| Token | Hex |
|---|---|
| `--blue-50` | `#EFF6FF` |
| `--amber-50` | `#FFFBEB` |
| `--rose-50` | `#FFF1F2` |
| `--purple-50` | `#F5F3FF` |
| `--teal-50` | `#F0FDFA` |
| `--cyan` | `#0EA5E9` (gradient endpoint) |

---

## Typography

| Property | Value |
|---|---|
| Family | `Inter` |
| Fallback | `-apple-system, BlinkMacSystemFont, sans-serif` |
| Weights | 400, 500, 600, 700, 800, 900 |
| Rendering | `-webkit-font-smoothing: antialiased` |

### Type Scale

| Name | Size | Weight | Tracking | Line Height | Color |
|---|---|---|---|---|---|
| Hero headline | `clamp(36px, 5.5vw, 64px)` | 900 | -0.03em | 1.15 | gray-950 |
| Section title | `clamp(28px, 4vw, 44px)` | 800 | -0.03em | 1.15 | gray-900 |
| Card/subsection title | 18-19px | 700 | default | default | gray-900 |
| Body large (subtitle) | 17px | 400 | default | 1.7 | gray-500 |
| Body default | 15px | 400 | default | 1.65 | gray-500 |
| Nav/footer links | 14.5px | 500 | default | default | gray-600 |
| Meta/trust text | 14px | 400 | default | default | gray-400 |
| Section tag | 13px | 600 | 0.5px | default | green-700 (uppercase) |
| Footer heading | 13px | 700 | 0.5-1px | default | gray-400 (uppercase) |
| Detail tag | 11px | 600 | 0.3px | default | varies (uppercase) |

---

## Spacing & Layout

### Constraints

| Element | Max Width |
|---|---|
| Container / navbar | `1200px` |
| Card grids | `1100px` |
| Steps grid | `1000px` |
| Section headers / text | `640px` |
| FAQ list | `740px` |
| Pricing card | `520px` |
| Container horizontal padding | `24px` |

### Section Padding

| Section | Padding |
|---|---|
| Standard section | `100px` top/bottom |
| Hero | `160px` top, `100px` bottom |
| Stats bar | `40px` top/bottom |
| Footer | `64px` top, `32px` bottom |
| Navbar height | `72px` (64px mobile) |
| Section header to content gap | `64px` margin-bottom |

### Grid Gaps

| Grid | Gap | Columns (desktop → mobile) |
|---|---|---|
| Feature cards | 24px | 3 → 2 → 1 |
| Business cards | 20px | 3 → 2 → 1 |
| Detail features | 20px | 2 → 1 |
| Steps | 40px | 3 → 1 |
| Stats | 32px | 4 → 2 |
| Footer | 48px | 2fr 1fr 1fr 1fr → 1fr |
| Testimonial track | 24px | continuous horizontal |

---

## Border Radius

| Token | Value | Usage |
|---|---|---|
| `--radius-sm` | `8px` | Tags, code blocks, small elements |
| `--radius-md` | `12px` | Inputs, highlight blocks |
| `--radius-lg` | `16px` | Feature cards, testimonial cards |
| `--radius-xl` | `24px` | Pricing card, modals |
| `--radius-full` | `9999px` | Buttons, badges, pills, avatars |

---

## Shadows

| Token | Value | Usage |
|---|---|---|
| `--shadow-sm` | `0 1px 2px rgba(0,0,0,0.05)` | Subtle elevation |
| `--shadow-md` | `0 4px 6px -1px rgba(0,0,0,0.07), 0 2px 4px -2px rgba(0,0,0,0.05)` | Navbar on scroll, steps |
| `--shadow-lg` | `0 10px 15px -3px rgba(0,0,0,0.08), 0 4px 6px -4px rgba(0,0,0,0.04)` | Card hover, testimonial hover |
| `--shadow-xl` | `0 20px 25px -5px rgba(0,0,0,0.08), 0 8px 10px -6px rgba(0,0,0,0.04)` | Feature card hover |
| `--shadow-2xl` | `0 25px 50px -12px rgba(0,0,0,0.15)` | Phone mockup frames |
| CTA glow | `0 4px 14px rgba(37,211,102,0.35)` | Primary button resting state |
| CTA glow hover | `0 6px 20px rgba(37,211,102,0.4)` | Primary button hover |

---

## Gradients

| Name | CSS | Usage |
|---|---|---|
| Brand | `linear-gradient(135deg, #25D366, #0EA5E9)` | Gradient text, card top-border reveal |
| Stat | `linear-gradient(135deg, #34D399, #67E8F9)` | Stats numbers (background-clip: text) |
| Logo | `linear-gradient(135deg, #25D366, #15803D)` | Logo icon background |
| CTA section | `linear-gradient(135deg, #14532D, #030712)` | Final CTA dark background |
| Hero bg | `linear-gradient(180deg, #F0FDF8 0%, #ECFDF5 30%, #FFF 100%)` | Hero section |
| CTA glow | `radial-gradient(circle at 30% 50%, rgba(37,211,102,0.12) 0%, transparent 60%)` | CTA section overlay |

---

## Components

### Buttons

**Primary (Green CTA)**
- Background: green-500 → green-600 on hover
- Text: white, 700 weight
- Sizes: SM `10px 22px / 14px` | Default `16px 32px / 16px` | LG `18px 40px / 18px`
- Radius: 9999px (pill)
- Shadow: green glow `0 4px 14px rgba(37,211,102,0.35)`
- Hover: translateY(-2px), stronger shadow
- Transition: all 0.25s ease

**Secondary (Outlined)**
- Background: white → gray-50 on hover
- Border: 1.5px solid gray-300 → gray-400 on hover
- Text: gray-800, 600 weight
- Hover: translateY(-2px)

### Badges

**Hero badge:** green-50 bg, green-200 border, green-800 text, pill shape, with animated pulsing green dot (scale 1→1.3, opacity 1→0.6, 2s infinite)

**Section tag:** 13px uppercase, 0.5px letter-spacing, pill. Light: green-50/green-700. Dark: rgba(37,211,102,0.15)/green-400.

**Detail tag:** 11px uppercase, 4px radius. "Auto" = green-50/green-700. "Panel" = blue-50/blue-600.

### Cards

**Feature card (light bg):**
- White bg, gray-200 border, 16px radius, 32px/28px padding
- Hover: translateY(-4px), shadow-xl, green-200 border
- Top gradient bar: scaleX(0→1) on hover, brand gradient, 3px height

**Business card (dark bg):**
- rgba(255,255,255,0.06) bg, rgba(255,255,255,0.1) border
- Hover: bg to 0.1, border to rgba(37,211,102,0.3), translateY(-2px)
- Bold text: green-400

**Detail card:**
- gray-50 bg, gray-200 border, 16px radius
- Flex row with 44px icon + text content
- Hover: shadow-lg, green-200 border, translateY(-2px)

### Pricing Card
- Max-width 520px, centered
- Border: 2px solid green-200, radius 24px
- Shadow: `0 8px 40px rgba(37,211,102,0.1)`
- "Precio unico" badge: absolute top center, green-500 bg, white text, pill
- Price: currency 24px/700 gray-700, value clamp(48-64px)/900 gray-950, period 16px/500 gray-500
- Feature checks: 24px circle, green-50 bg, green-600 check
- CTA: full-width primary button

### Navbar
- Fixed, frosted glass: `rgba(255,255,255,0.85)` + `backdrop-filter: blur(16px) saturate(180%)`
- Border-bottom: 1px solid gray-200
- Gains shadow-md on scroll (JS class toggle at 20px scroll)
- Height: 72px desktop, 64px mobile
- Logo left, nav links + CTA right, hamburger on mobile

### FAQ Accordion
- Questions: 17px/600 gray-900, 22px vertical padding, gray-200 borders
- Hover: text turns green-700
- Chevron: 24px circle, gray-100 bg → green-50 bg + rotate(180deg) when open
- Answer: max-height 0→300px over 0.35s ease, 15.5px/gray-500/1.7 line-height
- Behavior: only one open at a time

### Steps
- 80px circle, white bg, 3px green-200 border, shadow-md
- Number: 32px/800 green-600
- Connected by gradient line at top:40px (green-200→green-400→green-200)
- Line hidden on mobile

### Avatars (Testimonials)
- 44px circle, white text 18px/700
- Each person gets a unique 135deg gradient pair
- Palette: pink, indigo, emerald, amber, rose, violet, orange, cyan, lime, fuchsia

---

## Background Effects

**Dot grid (hero):**
```css
background-image: radial-gradient(circle at 1px 1px, #E5E7EB 1px, transparent 0);
background-size: 40px 40px;
opacity: 0.5;
mask-image: radial-gradient(ellipse 80% 70% at 50% 30%, black 30%, transparent 70%);
```

**Frosted glass (navbar):**
```css
background: rgba(255,255,255,0.85);
backdrop-filter: blur(16px) saturate(180%);
```

**Radial glow (CTA section):**
```css
background: radial-gradient(circle at 30% 50%, rgba(37,211,102,0.12) 0%, transparent 60%);
/* Applied as ::before, oversized at 200% width/height */
```

---

## Testimonial Carousel

- Two rows scrolling in opposite directions, full-width
- Row 1: `scroll-left 45s linear infinite` (translateX 0 → -50%)
- Row 2: `scroll-right 50s linear infinite` (translateX -50% → 0), 24px margin-top
- Pauses on hover (`animation-play-state: paused`)
- Edge fade: 200px wide (60px mobile), linear-gradient from bg color to transparent on both sides, z-index 2, pointer-events none
- Seamless loop: cards duplicated 2x, animation moves exactly -50%
- Card: 380px wide (320px mobile), white bg, gray-200 border, 16px radius

---

## Animations

### Hero Entry (staggered)

| Element | Animation | Delay |
|---|---|---|
| Badge | fadeInDown 0.6s ease | 0s |
| Headline | fadeInUp 0.6s ease | 0.1s |
| Subtitle | fadeInUp 0.6s ease | 0.2s |
| Buttons | fadeInUp 0.6s ease | 0.3s |
| Trust line | fadeInUp 0.6s ease | 0.4s |

```css
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
@keyframes fadeInDown {
  from { opacity: 0; transform: translateY(-10px); }
  to { opacity: 1; transform: translateY(0); }
}
```

### Transitions

| Component | Property | Duration |
|---|---|---|
| Buttons | all | 0.25s ease |
| Cards | all | 0.3s ease |
| Card top-bar | transform (scaleX) | 0.3s ease |
| Nav links | color | 0.2s |
| Navbar shadow | box-shadow | 0.3s ease |
| FAQ chevron | all (rotate) | 0.3s ease |
| FAQ answer | max-height | 0.35s ease |

---

## Responsive Breakpoints

| Breakpoint | Width | Key Changes |
|---|---|---|
| Desktop | > 1024px | Full layout, 3-col grids, side-by-side demo, full nav |
| Tablet | <= 1024px | Demo stacks vertically, grids to 2 columns |
| Mobile | <= 768px | Nav → hamburger, grids to 1 col, buttons full-width, carousel fade to 60px |
| Small mobile | <= 480px | Tighter type, phone mockup 260px, footer single column |

---

## Section Background Pattern

Sections alternate to create visual rhythm:

1. Hero: green gradient + dot grid
2. Stats bar: gray-950 (dark)
3. Features: white
4. Demo: gray-50 → white gradient
5. How it works: white
6. Business types: gray-950 (dark)
7. Pricing: white
8. Detail features: white
9. Testimonials: gray-50
10. FAQ: gray-50
11. Final CTA: green-900 → gray-950 gradient + radial glow
12. Footer: gray-950 (dark)

---

## Voice & Tone

| Principle | Do | Don't |
|---|---|---|
| Direct & warm | "Tus clientes reciben respuesta en segundos" | "Nuestra plataforma proporciona respuestas automatizadas" |
| Colombian Spanish | "por la tardecita", "le queda bien", "porfa" | Spain Spanish or overly formal |
| Results over features | "Te levantas con citas nuevas agendadas" | "Sistema de agendamiento con notificaciones push" |
| Concrete numbers | "Las inasistencias bajan hasta un 45%" | "Reduce significativamente las inasistencias" |
| Second person | "Tu negocio", "Esto es para usted" | "Los usuarios pueden..." |
| Never say AI | "recepcionista", "recepcionista virtual" | "IA", "AI", "bot", "chatbot", "inteligencia artificial" |

### Headline Formulas

- Outcome + "sin" + friction → "Tu negocio atendido 24/7, sin contratar a nadie"
- Action + timeframe → "Activalo hoy, esta noche ya esta atendiendo"
- Conditional → "Si agenda citas y le escriben por WhatsApp, esto es para usted"
- Comparison → "Una empleada 24/7 por menos de lo que imagina"

### Key Reusable Phrases

- "Noches, domingos y festivos"
- "Sin contratos, sin sorpresas"
- "$99.000/mes, precio fijo"
- "Cero mensajes sin leer"
- "Te levantas con citas agendadas"
- "No requiere tarjeta de credito"
- "Hecho con orgullo desde Pereira, el corazon del eje cafetero"

### CTA Copy

| Context | Text |
|---|---|
| Primary hero/final | "Empezar prueba gratis →" or "Probar 7 dias gratis →" |
| Secondary | "Ver demo en vivo" |
| Navbar | "Empezar gratis →" |
| Pricing | "Empezar 7 dias gratis →" |

---

## Colombian Identity Rules

| Element | Rule |
|---|---|
| Currency | Colombian pesos with period separator: **$99.000**, **$45.000** |
| Holidays | Say "festivos", reference Semana Santa, Navidad |
| Time | 12-hour: "2:00 p.m.", "9:47 p.m." |
| Address | Mix "usted" (respect) and "tu" (casual) naturally |
| Legal | "Tratamiento de datos" (per Ley 1581) |
| Flag | 🇨🇴 sparingly: footer and origin badge only |
| Cities | Medellin, Bogota, Cali, Barranquilla, Pereira, Bucaramanga, Envigado, Armenia, Manizales, Cartagena, Santa Marta |

---

## CSS Tokens (copy-paste)

```css
:root {
  /* Primary: Green */
  --green-50:  #ECFDF5;
  --green-100: #D1FAE5;
  --green-200: #A7F3D0;
  --green-400: #34D399;
  --green-500: #25D366;
  --green-600: #1B9E4B;
  --green-700: #15803D;
  --green-800: #166534;
  --green-900: #14532D;

  /* Neutral: Gray */
  --gray-50:  #F9FAFB;
  --gray-100: #F3F4F6;
  --gray-200: #E5E7EB;
  --gray-300: #D1D5DB;
  --gray-400: #9CA3AF;
  --gray-500: #6B7280;
  --gray-600: #4B5563;
  --gray-700: #374151;
  --gray-800: #1F2937;
  --gray-900: #111827;
  --gray-950: #030712;

  /* Accent */
  --blue-50:   #EFF6FF;
  --amber-50:  #FFFBEB;
  --rose-50:   #FFF1F2;
  --purple-50: #F5F3FF;
  --teal-50:   #F0FDFA;
  --cyan:      #0EA5E9;

  /* Semantic */
  --white: #FFFFFF;

  /* Border Radius */
  --radius-sm:   8px;
  --radius-md:   12px;
  --radius-lg:   16px;
  --radius-xl:   24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm:  0 1px 2px rgba(0,0,0,0.05);
  --shadow-md:  0 4px 6px -1px rgba(0,0,0,0.07), 0 2px 4px -2px rgba(0,0,0,0.05);
  --shadow-lg:  0 10px 15px -3px rgba(0,0,0,0.08), 0 4px 6px -4px rgba(0,0,0,0.04);
  --shadow-xl:  0 20px 25px -5px rgba(0,0,0,0.08), 0 8px 10px -6px rgba(0,0,0,0.04);
  --shadow-2xl: 0 25px 50px -12px rgba(0,0,0,0.15);
}
```
