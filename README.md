🏴‍☠️ ev1lc0rp — Brand Assets & Design System

Repositorio centralizado de identidad corporativa, activos vectoriales, logotipos, iconografía y manuales de estilo para la firma matriz **ev1lc0rp** y sus plataformas operativas.

---

## 📂 Estructura del Repositorio

```text
ev1lc0rp-branding/
│
├── core/                         # Identidad corporativa ev1lc0rp
│   ├── logos/                    # Versiones horizontal y vertical
│   ├── icon/                     # Isotipo del cubo isométrico / circuitos
│   └── svg/                      # Archivos vectoriales limpios
│
├── platforms/                    # Ecosistema de productos y plataformas
│   │
│   ├── apuquantix-core/          # Plataforma analítica de costos unitarios
│   │   ├── horizontal/           # Isotipo 'A' técnica + "APUQuantix CORE"
│   │   ├── mark/                 # Símbolo aislado (A modular + calibrador)
│   │   └── exports/              # PNG (transparente), SVG, WebP
│   │
│   └── skadnex/                  # Plataforma de ciberinteligencia & OSINT
│       ├── horizontal-dark/      # Cyber-fox + tipografía sobre fondo negro
│       ├── avatar-badge/         # Emblema del zorro cibernético aislado
│       └── exports/              # SVG vector, PNG Hi-Res
│
├── tokens/                       # Paletas de color (HEX, RGB, CSS vars)
└── guidelines/                   # Especificaciones técnicas y márgenes
```

---

## 🏢 Identidades y Plataformas

### 1. ev1lc0rp (Matriz Corporativa)

> Identidad principal: Núcleo de desarrollo, ciberseguridad e infraestructura.

- **Isotipo / Símbolo:** Cubo isométrico tridimensional delimitado por trazos modulares y circuitos integrados continuos que convergen en perspectiva isométrica.
- **Estética:** Minimalista, trazo limpio y geométrico, alto impacto vectorial.
- **Paleta oficial:**
  - **Crimson Red:** `#FF1E1E` (Color primario de contraste e identidad)
  - **Solid White:** `#FFFFFF` (Fondo de exhibición) / **Pitch Black:** `#000000` (Modo oscuro)

---

### 2. APUQuantix CORE

> Plataforma especializada en análisis de costos unitarios (APU), cubicación y presupuestos de obra.

- **Isotipo / Símbolo:**
  - Estructura de letra **A** monumental estilizada con remate angular.
  - Base integrada por calibradores de precisión (vernier / pie de rey).
  - En el núcleo inferior, un hexágono con circuitos y flecha de tendencia alcista.
  - En el fondo, gráficos de barras ascendentes y nodos de almacenamiento de datos.
- **Tipografía:**
  - `APUQuantix` en negrita con corte técnico y terminaciones en semicírculo en la letra Q.
  - `CORE` en caja alta, color gris neutro, otorgando jerarquía secundaria.
- **Paleta oficial:**
  - **Deep Industrial Blue:** `#0C4A6E` (Tipografía y estructura A)
  - **Cyan / Teal:** `#06B6D4` / `#0D9488` (Curvas de flujo, nodos y métricas)
  - **Steel Gray:** `#475569` (Subtítulo CORE y piezas mecánicas)

---

### 3. SkadNex

> Plataforma de ciberinteligencia, análisis geoespacial, telecomunicaciones y rastreo OSINT.

- **Isotipo / Símbolo:**
  - Cabeza de zorro cibernético (*Cyber-Fox*) con interfaz HUD y arquitectura de nodos.
  - Ojo biónico derecho con nodo reticular de rastreo geoespacial y telecomunicaciones.
  - Marcadores de terminal interactiva: prompt `[admin#]`, flecha de ejecución `>>> _` y flujos de código binario (`0101`).
  - Nodos periféricos interconectados simulando topología de redes y servidores.
- **Tipografía:**
  - `SkadNex` con remates afilados y modernos en tono violeta oscuro/índigo nocturno.
  - Subtítulo: `FORENSIC INTELLIGENCE | GEOSPATIAL ANALYSIS | OSINT PLATFORM`.
- **Fondo y modo de uso:** Diseñado primordialmente para **fondo oscuro / Dark UI (`#000000` o `#0B0E14`)**.
- **Paleta oficial:**
  - **Electric Cyan:** `#00F0FF` (Líneas de datos y terminal)
  - **Neon Green:** `#39FF14` (Acentos de consola y rastreo activo)
  - **Deep Indigo / Midnight Purple:** `#1E1B4B` (Cuerpo tipográfico y volumen)
  - **Terminal Black:** `#000000` (Fondo base de alto contraste)

---

## 🎨 Tabla Resumen de Tokens de Color

| Marca / Plataforma | Nombre Token | Hexadecimal | Función Principal |
| --- | --- | --- | --- |
| **ev1lc0rp** | `ev1l-red` | `#FF1E1E` | Isotipo cubo de circuitos / Matriz |
| **ev1lc0rp** | `ev1l-white` | `#FFFFFF` | Fondo primario en versión light |
| **APUQuantix CORE** | `apu-deep-blue` | `#0C4A6E` | Nombre principal `APUQuantix` |
| **APUQuantix CORE** | `apu-cyan` | `#06B6D4` | Métricas, flechas e isotipo |
| **APUQuantix CORE** | `apu-core-gray` | `#475569` | Texto `CORE` y soporte técnico |
| **SkadNex** | `skad-bg` | `#000000` | Fondo terminal oscuro |
| **SkadNex** | `skad-cyan` | `#00F0FF` | Red de nodos, ojos HUD y pistas OSINT |
| **SkadNex** | `skad-neon-green` | `#39FF14` | Acentos de prompt e interfaz hacker |
| **SkadNex** | `skad-indigo` | `#1E1B4B` | Logotipo tipográfico `SkadNex` |

---

## 📐 Reglas de Uso y Proporciones

1. **Fondo de aplicación:**
  - **ev1lc0rp**: Fondos neutros sólidos (blanco absoluto o negro absoluto) para mantener la legibilidad de las líneas del cubo.
  - **APUQuantix CORE**: Fondo blanco o fondos grises claros (`#F8FAFC`).
  - **SkadNex**: Fondos oscuros (`#000000` o `#0B0F17`) para que resalten las iluminaciones de nodos cian y verde neón.
2. **Restricciones:**
  - No deformar la relación de aspecto del isotipo del zorro ni del cubo de ev1lc0rp.
  - No remover los corchetes ni el indicador de terminal `[admin#]` en las versiones completas de SkadNex.
  - Mantener el espaciado divisor vertical entre el isotipo y el texto en el logotipo de APUQuantix CORE.

---

## ⚖️ Licencia y Derechos

Todos los derechos de diseño, nombres comerciales y logotipos son propiedad intelectual de **ev1lc0rp**. Prohibida su reproducción o uso no autorizado en plataformas externas al ecosistema.
