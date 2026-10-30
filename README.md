# Clínica EMT Tijuana · Sitio español v2

Copia independiente del sitio español, con diseño aprobado y citas por teléfono: +52 664 635 1809.

## Publicación
HTML estático sin compilación. Publicar la raíz del repositorio. Conserva CNAME y la conexión existente del dominio de producción. Antes de conectar dominio, revisar metadatos, canonical y sitemap. Los previews deben mantenerse fuera del índice de buscadores.

## Integraciones
- WhatsApp y Google Maps conservan los destinos del sitio original.
- Los enlaces al formulario de Jotform se sustituyeron por llamadas.
- La agenda ahora dirige a atención telefónica.
- Asistente de Jotform integrado en todas las páginas. Google Tag: GTM-GTMW5XTZNQ en todas las páginas. La carga y las conversiones se comprobarán al publicar.
- El código registra clics solo si gtag o dataLayer ya están disponibles; esto no verifica medición ni conversiones reales.

## Alcance
Todas las páginas comparten el diseño nuevo. Contenido informativo, blog y textos legales conservados. La agenda es telefónica; los enlaces históricos de solicitud en el blog se conservan para revisión. Revisar contenido clínico y legal antes de publicar. SEO/AEO no garantiza posiciones ni leads.


## Reglas de revisión de Camila
- Actualizar la previsualización cada tres cambios importantes.
- Revisar la versión final española en Sites antes de su aprobación.
- Crear la copia inglesa únicamente después de aprobar el español.
- Etiqueta de regreso: español «Volver al menú»; inglés «Back».
- Sábado: 9:00–14:00. Agenda exclusivamente telefónica, sin calendario.
- Todas las páginas deben incluir Google Tag y estar en sitemap.xml.


## Respaldo y reversión
Código anterior conservado en la rama `respaldo-sitio-anterior-2026-10-30`, commit `bd2397c888889341226cb0eb3fa29310e6f5e4c4`. La rama `respaldo-sitio-anterior-2026-10-29` también se conserva.
Fuente del código aprobado: `emt-tijuana-web-v2-ESP`, commit `f2de09cca39ce58c11d8524fb48af4e4334735bd`.
El reemplazo conserva el historial y CNAME; para volver al diseño anterior, revertir el commit de migración y publicar de nuevo.
