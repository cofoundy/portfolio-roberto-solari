# Propuesta de Diseño: Dr. Roberto Solari Diaz

## Identidad
Cirujano con doble especialidad — plástica y bariátrica — que transforma vidas desde dos frentes: la estética y la salud. 13+ años entre hospitales públicos, clínicas privadas y su propia Clínica Solari con dos sedes en Lima. Su diferenciador: un cirujano que entiende el cuerpo completo, no solo una parte.

## Audiencia
- **Pacientes potenciales** buscando cirugía plástica o bariátrica en Lima → necesitan confianza, credenciales, testimonios
- **Médicos referentes** → credenciales académicas, sociedades profesionales
- **Pacientes existentes** verificando al doctor antes de agendar

## Metáfora Visual
Precisión quirúrgica: limpio, estructurado, confiable. Azul médico profundo que transmite autoridad sin frialdad. El sitio debe sentirse como entrar a una clínica premium — todo en su lugar, todo inspira confianza.

## Secciones Propuestas (en orden)

1. **Hero** — Foto profesional full con nombre, título dual, CMP/RNSE badges, CTA "Agendar Consulta"
   - 2-col: texto izq + foto der (bata blanca, brazos cruzados = confianza)
   - Stats row: 13+ años | 2 Especialidades | 2 Sedes

2. **Especialidades** — DOS cards grandes side-by-side (efecto ÚNICO)
   - Izq: Cirugía Plástica (lista de procedimientos con iconos)
   - Der: Cirugía Bariátrica (manga gástrica, bypass)
   - Hover: card se eleva con sombra azul, icono anima
   - Mobile: stack vertical

3. **Trayectoria** — Timeline vertical interactivo (efecto ÚNICO)
   - 2007: SERUMS Amazonas → 2010-2013: Residencia Cirugía General →
   - 2016-2018: Residencia Cirugía Plástica → 2018-actual: Hospital PNP →
   - Clínica propia con dos sedes
   - Cada nodo con institución + logo/badge + descripción breve
   - Línea animada que se dibuja al scrollear

4. **Formación** — Grid académico con badges
   - UNFV: Doble residencia (General + Plástica)
   - UNMSM: Maestría Fisiología Humana
   - USMP: Médico Cirujano
   - Sociedades: SPCE, SCGP, SPCP
   - Rotaciones internacionales: Ecuador, Colombia

5. **Testimonios** — Carousel con 3 testimonios reales (5 estrellas)
   - Reina Rios, Catherine Ezquerre, Camila Trujillo
   - Quote grande + nombre + estrellas
   - Auto-rotate con dots

6. **Clínica** — Dos sedes con info de contacto
   - Av. Brasil 831, Jesús María
   - Av. Del Pinar 124, Of. 303
   - WhatsApp + teléfonos + horarios
   - CTA: "Agenda tu consulta"

7. **Footer** — Links sociales + credenciales + CTA final

## Secciones que NO incluir
- **Skills pills** — no aplica para un cirujano
- **Projects grid** — no es freelancer/developer
- **Education cards genéricas** — reemplazado por Formación custom
- **About genérico** — la identidad está en Hero + Especialidades
- **Blog** — no tiene contenido escrito

## Paleta (6 colores — monocromático frío, azul médico)
- primaryDark: #0c2340 — navy profundo, autoridad médica, headings
- primary: #1a5276 — azul médico, bordes, nav
- primaryLight: #5dade2 — azul claro, shimmer, acentos suaves
- accent: #2980b9 — azul brillante, CTAs, stats, badges
- surface: #eaf2f8 — ice blue, fondos de sección
- surfaceLight: #f8fbfd — casi blanco, hero bg

## Tipografía
- **Headings:** DM Serif Display — autoridad médica, serif elegante
- **Body:** Source Sans 3 — limpio, legible, médico

## Efecto Visual Único
1. **Timeline animado** — línea que se dibuja al scroll con nodos que aparecen
2. **Specialty Split** — dos cards que revelan procedimientos al hover con glow azul
3. **Counter stats** — números que cuentan desde 0 (13+ años, 2 especialidades, etc.)

## ASCII Layout — Mobile (375px)

```
┌─────────────────────┐
│  DR. ROBERTO SOLARI  │
│  Cirujano Plástico   │
│  y Bariátrico        │
│                      │
│  [    FOTO 3/4     ] │
│  [   bata blanca   ] │
│                      │
│  CMP 48888 │ RNSE 108│
│                      │
│  [Agendar Consulta]  │
│                      │
│  13+    2      2     │
│  años  espec  sedes  │
├─────────────────────┤
│  ESPECIALIDADES      │
│  ┌─────────────────┐ │
│  │ 🔬 Cir. Plástica│ │
│  │ • Rinoplastia   │ │
│  │ • Liposucción   │ │
│  │ • Abdominoplast.│ │
│  │ • Mamoplastia   │ │
│  └─────────────────┘ │
│  ┌─────────────────┐ │
│  │ ⚕️ Cir. Bariátr.│ │
│  │ • Manga Gástrica│ │
│  │ • Bypass        │ │
│  │ • Cir. General  │ │
│  └─────────────────┘ │
├─────────────────────┤
│  TRAYECTORIA         │
│  ●─ 2007 SERUMS      │
│  │  Amazonas          │
│  ●─ 2010 Resid. Gral │
│  │  UNFV              │
│  ●─ 2016 Resid. Plás.│
│  │  UNFV              │
│  ●─ 2018 Hosp. PNP   │
│  │  Nivel IV          │
│  ●─ Clínica Solari   │
│     2 sedes Lima      │
├─────────────────────┤
│  FORMACIÓN           │
│  [UNFV badge]        │
│  [UNMSM badge]       │
│  [USMP badge]        │
│  [Sociedades]        │
├─────────────────────┤
│  TESTIMONIOS         │
│  "El Dr. Solari es   │
│   muy profesional..."│
│  — Reina Rios ⭐⭐⭐⭐⭐│
│  ● ○ ○               │
├─────────────────────┤
│  CLÍNICA SOLARI      │
│  📍 Sede 1: Jesús M. │
│  📍 Sede 2: Of. 303  │
│  📞 983 385 522       │
│  [Agendar Consulta]  │
├─────────────────────┤
│  Footer + socials    │
└─────────────────────┘
```
