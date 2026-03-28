# Spec: Landing Page — Grano a Grano Bakery

## Objetivo
Landing page para Grano a Grano Bakery (panadería artesanal en Ciudad Real). 
Objetivo de conversión: **pedidos por WhatsApp** (658 54 20 68) con 48h de antelación.

## Stack
- **Astro** + **Tailwind CSS v4**
- HTML semántico, CSS puro para animaciones
- Desplegable en Cloudflare Pages
- Mobile-first, responsive

## Identidad visual

### Paleta de colores (tonos artesanales/rústicos)
- **Primario:** Marrón cálido dorado (corteza de pan) — #C4956A o similar
- **Secundario:** Crema/trigo claro (interior de hogaza) — #F5E6D0 o similar
- **Acento:** Verde oliva suave (ingredientes naturales) — #7A8B6F o similar
- **Fondo:** Off-white cálido — #FAF6F0 o similar
- **Texto:** Marrón oscuro — #3D2B1F o similar
- DaVinci DEBE extraer la paleta REAL del Instagram/web existente. Estos son sugeridos.

### Tipografía
- **Headlines:** Serif elegante (Playfair Display o Cormorant Garamond) — transmite artesanía
- **Body:** Sans-serif limpia (DM Sans o Inter) — legibilidad
- Combinar para contraste visual

### Estilo fotográfico
- Imágenes de Unsplash de pan artesanal, masa madre, obradores
- Tonos cálidos, iluminación natural, texturas de corteza y miga
- Overlay con gradiente para legibilidad del texto sobre hero

## Estructura de secciones

### 1. Hero
- **Headline:** "Pan de verdad. Hecho como se hacía antes."
- **Subheadline:** "Masa madre de cultivo propio, fermentación lenta de 24 horas y solo tres ingredientes: harina, agua y sal."
- **CTA:** "Reserva tu Pan" → link a WhatsApp (https://wa.me/34658542068)
- **Hero image:** pan artesanal de masa madre con corteza crujiente
- **Badge:** "⭐ 4.9/5 en Google — Ciudad Real"

### 2. Social Proof
- 4.9 estrellas Google
- "Desde 2021 — nacidos durante el confinamiento"
- "8 tipos de hogazas artesanales"
- "Solo harina, agua y sal"

### 3. Nuestra historia (el problema que resuelven)
- "En un mundo de pan industrial, decidimos volver a lo auténtico"
- Historia de Esther y Carlos: cocineros, UK, vuelta a España, confinamiento → obrador
- Foto del obrador / fundadores (usar Unsplash como placeholder)

### 4. Productos (Features)
- Grid/cards con los 3 tipos principales:
  1. **Pan de Masa Madre** — 8 variedades de hogazas (destacar Hogaza de la Casa, Semillas, Manchego)
  2. **Bollería Artesana** — Cruasanes, Cinnamon Rolls, Chelsea Buns
  3. **Pan de Levadura** — Chapatas, Pan Inglés, Burger Buns
- Imágenes de cada tipo con descripción corta

### 5. Cómo funciona (3 pasos)
1. 📱 **Haz tu pedido** — Escríbenos por WhatsApp con 48h de antelación
2. 🌙 **Horneamos de noche** — Elaboración nocturna con masa madre e ingredientes naturales
3. 🚗 **Recógelo o te lo llevamos** — En obrador (C. Socuéllamos) o a domicilio en Ciudad Real y Miguelturra

### 6. Testimonios
- Extraer 2-3 reseñas reales de Google (4.9/5)
- "Un obrador que ha revolucionado el pan en Ciudad Real"
- Nombres y estrellas

### 7. Dónde estamos
- Dos ubicaciones:
  - **Obrador Grano a Grano:** C. Socuéllamos, 14, nave 12 (Polígono Larache)
  - **Carapan:** C. Caballeros esquina C. Feria (centro)
- Horarios: Mar-Vie 9:00-14:30 / Sáb 9:00-13:00 / Dom-Lun cerrado
- Mapa embed de Google Maps
- Teléfono clicable: 658 54 20 68

### 8. FAQ
- ¿Cómo hago un pedido? → WhatsApp con 48h antelación
- ¿Hacéis envíos a domicilio? → Sí, Ciudad Real capital y Miguelturra
- ¿Vuestro pan lleva conservantes? → No. Solo harina, agua y sal.
- ¿Qué es la masa madre? → Cultivo propio, fermentación 24-30h, sin levadura comercial
- ¿Puedo ir directamente a comprar? → Sí, en Carapan (centro) en horario de tienda

### 9. CTA Final
- "Tu pan artesanal te espera"
- CTA: "Reserva por WhatsApp" → wa.me/34658542068
- Horario rápido + dirección

### 10. Footer
- Logo / nombre
- Dirección + teléfono
- Instagram: @granoagranobakery
- Links legales (Aviso Legal, Privacidad)
- © 2026 Grano a Grano Bakery

## SEO
- Title: "Grano a Grano Bakery — Pan Artesanal de Masa Madre en Ciudad Real"
- Description: "Panadería artesana en Ciudad Real. Pan de masa madre de cultivo propio, fermentación lenta, sin aditivos. Hogaza de la Casa, bollería artesana y más. Pedidos por WhatsApp."
- JSON-LD: LocalBusiness + Bakery schema
- Keywords en headings naturalmente

## RGPD
- Cookie banner mínimo (no hay tracking, solo analytics básico)
- /legal y /privacidad

## Mobile
- CTA sticky bottom "Pedir por WhatsApp" con icono WA
- Font mínimo 16px
- Hero adaptado (imagen recortada vertical)

## Entregable
- Código completo en PR a `main`
- Desplegable con `wrangler pages deploy dist --project-name granoagrano-landing`
