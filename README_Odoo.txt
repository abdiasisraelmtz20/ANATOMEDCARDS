MEDSTUDENTS · MEDCARDS ANATOMÍA · 1ER PARCIAL
=================================================

App construida a partir del PDF proporcionado.
Total integrado: 108 páginas = 105 MEDCARDS + 3 portadas

Bloques:
- Dorso: páginas 1-35
- Extremidad superior: páginas 36-75
- Extremidad inferior: páginas 76-108

Incluye:
- Logo MEDSTUDENTS real
- Navegación anterior / siguiente
- Selector por bloque
- Barra de progreso
- Modo aleatorio
- Pantalla completa
- Teclado ← →
- Swipe en celular
- Pre-carga de tarjeta anterior/siguiente
- Imágenes WebP optimizadas para web
- Diseño responsive para iframe en Odoo

PARA PUBLICAR:
Sube TODA esta carpeta a un hosting HTTPS manteniendo la estructura.

IFRAME RECOMENDADO EN ODOO:

<iframe
  src="https://TU-DOMINIO/RUTA/index.html"
  width="100%"
  height="900"
  style="border:0; border-radius:20px; overflow:hidden;"
  allow="fullscreen"
  loading="lazy">
</iframe>

IMPORTANTE:
No subas únicamente index.html: también deben conservarse las carpetas:
assets/cards/
assets/brand/


NUEVA FUNCIÓN: MARCAR PARA REPASAR
----------------------------------
- El alumno puede pulsar "☆ Marcar para repasar".
- Las MEDCARDS marcadas se guardan en el navegador mediante localStorage.
- En el selector puede elegir "⭐ Mis marcadas" y ver solamente sus favoritas.
- Puede desmarcarlas cuando ya las haya repasado.
- Las marcas son personales para ese navegador/dispositivo.


AJUSTE DE VISUALIZACIÓN COMPLETA
--------------------------------
Se ajustó el visor para que la MEDCARD use todo el alto disponible dentro del iframe
y se vea completa con object-fit: contain.

Altura recomendada del iframe en Odoo:
- Escritorio: 1100 a 1150 px
- Si todavía la ves apretada en tu página, usa 1200 px
