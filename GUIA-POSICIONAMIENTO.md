# Guía de posicionamiento · Rare Nail It

La web ya tiene SEO técnico, datos estructurados (NailSalon + FAQ), `llms.txt` para asistentes de IA, `robots.txt` y `sitemap.xml`. Lo que sigue se hace **con tus cuentas** y es lo que más mueve el posicionamiento local.

## 0. Antes de empezar (5 min)
Edita en `index.html`, dentro del bloque `CONFIG` al final:
- `whatsapp`: el número real con 51 delante (ej. `51987654321`).
- `googleReviewUrl`: el enlace de reseñas (lo obtienes en el paso 2).

Revisa también precios, distritos y horario: están en el HTML, en el JSON-LD (arriba en `<head>`) y en `llms.txt`. **Tienen que coincidir en los tres sitios.**

## 1. Perfil de Empresa en Google — el factor nº 1 en búsquedas locales
1. Entra a https://business.google.com y crea "Rare Nail It".
2. Categoría principal: **Salón de manicura y pedicura**. Secundarias: *Servicio de uñas*, *Salón de belleza*.
3. Elige **"Visito a mis clientes"**: oculta la dirección y añade como **áreas de servicio** los mismos distritos de la web.
4. Rellena todo: horario, teléfono/WhatsApp, web (`https://caro2870.github.io/rare-nail-it/`), descripción (usa la primera frase de la web), y **cada servicio con su precio**.
5. Sube fotos reales (mínimo 10) y luego **1–2 fotos nuevas por semana**.
6. Publica una "novedad" cada semana o cada dos (diseño nuevo, promo, disponibilidad).

## 2. Reseñas — lo que más pesa después del perfil
- En el Perfil de Google: *Pedir reseñas* → copia el enlace → pégalo en `googleReviewUrl`.
- Después de **cada** cita, manda por WhatsApp: *"¡Gracias por venir! Si te gustaron tus uñas, me ayudarías muchísimo con una reseña ✨ [enlace]"*.
- Responde todas las reseñas (mencionando la técnica y el distrito de forma natural, ej. "¡Gracias! Me encantó hacerte el poly gel en Surco").
- Lo que más cuenta es que **lleguen seguido** (recencia), no tener muchas de golpe.

## 3. NAP consistente (Nombre, Zona, Teléfono)
Usa exactamente **"Rare Nail It"**, "Lima, Perú – a domicilio" y el mismo WhatsApp en:
Instagram (y pon el link de la web en la bio) · TikTok · Facebook · Bing Places (https://www.bingplaces.com, importa desde Google) · Apple Business Connect.

## 4. Menciones externas (autoridad para Google y para las IAs)
- Directorios de belleza y servicios de Lima (listados gratis).
- Colaboraciones con cuentas de Lima (maquilladoras, fotógrafas, novias) que enlacen la web.
- Cada vez que alguien te etiquete, que salga "Rare Nail It" escrito igual.

## 5. Medir
1. **Google Search Console** (https://search.google.com/search-console): añade la propiedad con la URL de la web, verifica y envía `sitemap.xml`.
2. **Bing Webmaster Tools**: importa desde Search Console (Bing alimenta a ChatGPT Search).
3. Cada mes, pregunta en ChatGPT, Perplexity, Gemini y Google (modo IA): *"¿dónde hacen uñas acrílicas a domicilio en Lima?"*, *"soft gel a domicilio en Miraflores"*. Anota si aparece Rare Nail It.

## 6. Mantener la web fresca (cada 1–3 meses)
- Cambia o añade fotos a la galería (mismo formato: nombre descriptivo con "lima", WebP + JPG).
- Actualiza precios si cambian (HTML + JSON-LD + `llms.txt`).
- Cambia la fecha `dateModified` en el JSON-LD, la fecha del pie y `lastmod` en `sitemap.xml`.
- Añade preguntas nuevas al FAQ con las dudas reales que te hacen por WhatsApp.

## 7. Siguiente nivel (opcional)
- **Dominio propio** (ej. `rarenailit.pe` o `.com`, ~S/ 50–150/año) apuntado a GitHub Pages: da más confianza y autoridad.
- Si lo haces, cambia la URL en `index.html` (canonical, og:url, JSON-LD), `sitemap.xml`, `robots.txt` y `llms.txt`.
