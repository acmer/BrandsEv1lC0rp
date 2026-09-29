# 📐 Guía de Identidad y Manual de Estilo Visual

Este documento detalla las normativas de composición, márgenes de seguridad, tamaños mínimos de reproducción y lineamientos de aplicación técnica para **ev1lc0rp**, **APUQuantix CORE** y **SkadNex**.

---

## 1. ev1lc0rp (Matriz Corporativa)

### 1.1 Composición y Geometría
El isotipo se basa en un cubo isométrico desfragmentado en trazos modulares de circuito PCB con terminaciones redondeadas a $45^\circ$ y $90^\circ$.

* **Grosor del Trazo ($w$):** Constante e indeformable en toda la red interior.
* **Separación entre módulos:** Equidistante, equivalente al $100\%$ del grosor del trazo ($1w$).

### 1.2 Área de Protección (Clear Space)
El espacio de seguridad mínimo alrededor del cubo equivale a la mitad de su radio exterior ($R/2$):
```
       +-----------------------+
       |         R / 2         |
       |     +-----------+     |
 R / 2 |     |  [CUBO]   |     | R / 2
       |     +-----------+     |
       |         R / 2         |
       +-----------------------+
```

### 1.3 Tamaños Mínimos
* **Impresión:** $15\text{ mm}$ de altura.
* **Pantalla / Digital:** $32 \times 32\text{ px}$ (Favicon / Avatar).

### 1.4 Reglas de Uso
- ✅ **Permitido:** Rojo Carmesí (`#FF1E1E`) sobre fondo blanco absoluto (`#FFFFFF`) o fondo negro carbón (`#0A0A0A`).
- ❌ **Prohibido:** Modificar el grosor de los trazos, rellenar los espacios huecos del cubo o aplicarle sombras difusas.

---

## 2. APUQuantix CORE

### 2.1 Arquitectura del Bloque Horizontal
El logotipo se divide en dos módulos separados por una línea vertical divisoria:
1. **Módulo Simbólico (Izquierda):** Composición integrada de letra `A`, barra de calibrador mecánico en la base, hexágono de cálculo y barras estadísticas superiores.
2. **Divisor:** Línea vertical con grosor de $1.5\text{ px}$ en `#CBD5E1`.
3. **Módulo Tipográfico (Derecha):** 
   * Línea 1: `APUQuantix` (Bold / Semi-bold, `#0C4A6E`).
   * Línea 2: `CORE` (Medium, espaciado kerning abierto +15%, `#475569`).

### 2.2 Tamaños Mínimos
* **Logotipo Completo Horizontal:** $180\text{ px}$ de ancho.
* **Isotipo Aislado (Mark):** $40 \times 40\text{ px}$.

### 2.3 Reglas de Uso
- ✅ **Permitido:** Fondos claros, neutros o tarjetas blancas con bordes sutiles.
- ❌ **Prohibido:** Separar el calibrador vernier de la base de la letra `A`.
- ❌ **Prohibido:** Colocar el texto `CORE` del mismo color o mayor tamaño que `APUQuantix`.

---

## 3. SkadNex

### 3.1 Anatomía del Cyber-Fox HUD
* **Orientación:** Frontal con ligero balance de nodos hacia la periferia.
* **Componentes Críticos:**
  * Nodo reticular ocular en el ojo derecho (geolocalización).
  * Prompt de consola superior `>>> _` y badge lateral `[admin#]`.
  * Red de conectividad telecom en los costados simulando arquitectura de servidores y antenas.

### 3.2 Restricciones de Contraste y Fondos
SkadNex está formulado estrictamente como una identidad para entornos oscuros (**Dark Mode Native**):
* **Fondo Obligatorio:** Fondo negro sólido (`#000000`) o gris muy oscuro terminal (`#0B0E14`).
* ❌ **Prohibido terminantemente:** Utilizar el isotipo del Cyber-Fox sobre fondo blanco o fondos pastel, ya que los nodos cian (`#00F0FF`) y verde neón (`#39FF14`) pierden luminosidad y contraste técnico.

### 3.3 Tamaños Mínimos
* **Logotipo Completo con Subtítulo:** $240\text{ px}$ de ancho.
* **Avatar / Badge Cyber-Fox:** $64 \times 64\text{ px}$.

---

## 4. Matriz de Errores Críticos (Don'ts Generales)

| Acción Prohibida | Impacto en la Marca |
| :--- | :--- |
| Escalar elementos de manera no proporcional (estirar vertical u horizontalmente) | Deforma las proporciones de precisión técnica. |
| Invertir colores no autorizados en SkadNex | Invalida la estética hacker/terminal OSINT. |
| Eliminar los badges `[admin#]` en el logo SkadNex | Pierde su contexto de plataforma de explotación y ciberinteligencia. |
| Colocar sombras o biseles 3D realistas | Rompe el principio de diseño plano vectorial (Flat Vector HUD). |