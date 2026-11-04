# Plantilla: `decisiones.md`

Copia este contenido en un archivo `decisiones.md` en la carpeta `proyecto/` de tu repo y complétalo. Es la **Sumativa 2** (25 pts), y en el checkpoint (18 nov) lo corriges. Sin informe largo.

---

# Decisiones de mi sitio

**Emprendimiento:** Brote
**Fecha:** 25 de noviembre · **Última corrección:** (fecha)

## 1. Plugins (10 pts)

Al menos **5 plugins**, cada uno vale 2 pts. **SEO** y **contacto** son obligatorios; los otros 3 los eliges según lo que necesita tu sitio (parte de `docs/03-funcionalidades.md`). Guía: `guia-investigar-plugins.md`.

| # | Funcionalidad | Plugin | Gratis o de pago | Qué incluye la versión gratis | Probado hasta (WP) | Requiere PHP | ¿Funciona con tema propio? | Enlace a la ficha |
|---|---|---|---|---|---|---|---|---|
| 1 | Aparecer en Google ("pestañas Valparaíso") | Yoast SEO (obligatorio) | Gratis, con Premium opcional | Análisis SEO y de legibilidad por página, títulos y meta descripciones, sitemap XML y datos de schema. Lo de pago (Premium) añade redirecciones, sugerencias de enlaces internos y herramientas de IA. | 7.1.4 | 7.4 o superior | Sí, si el tema llama a wp_head() | https://wordpress.org/plugins/wordpress-seo/ |
| 2 | Formulario para que las clientas pidan hora o consulten | Forminator Forms – Contact Form, Payment Form & Custom Form Builder (obligatorio) | Gratis, con versión Pro de pago | Formularios con editor de arrastrar y soltar, plantillas, encuestas, calculadoras y más de 1000 integraciones. Pro añade campos y extensiones extra (PDF, suscripciones con Stripe). En la fase 1 solo uso el formulario de contacto. | 7.0.1 | 7.4 o superior | Sí, si el tema llama a wp_footer() | https://wordpress.org/plugins/forminator/ |
| 3 | Bloquear spam en el formulario y los comentarios | Akismet Anti-spam: Spam Protection | Gratis solo para uso personal; un negocio probablemente necesita plan de pago | Revisa los envíos y comentarios contra una base global de spam y filtra los sospechosos. | 7.1.4 | 7.2 o superior | Sí | https://wordpress.org/plugins/akismet/ |
| 4 | Copia de seguridad del sitio por si algo se rompe | BackWPup – Plugin de copia de seguridad y restauración de WordPress | Gratis, con versión Pro de pago | Copias automáticas programadas de archivos y base de datos, con envío a destinos como Dropbox o S3. Pro añade más funciones. | 7.1.4 | 7.4 o superior | Sí | https://wordpress.org/plugins/backwpup/ |
| 5 | Mostrar la galería de trabajos y fotos antes/después | Modula Image Gallery – Photo Grid & Video Gallery | Gratis, con extensiones de pago | Galería de fotos en cuadrícula y soporte de video. Las extensiones avanzadas son de pago. | 7.0 | 5.6 o superior | Sí | https://wordpress.org/plugins/modula-best-grid-gallery/ |

## 2. Páginas de la fase 1 (5 pts)

**5 páginas**, 1 pt cada una. **Inicio** y **Contacto** son obligatorias; las otras 3 las eliges (no pueden ser del carro de compras).

| # | Página | Por qué la elijo (una línea) |
|---|---|---|
| 1 | Inicio (obligatoria) | |
| 2 | Contacto (obligatoria) | |
| 3 | | |
| 4 | | |
| 5 | | |

**Páginas que dejo para después:** (lista corta)

## 3. Plan del tema (5 pts)

- **Nombre del tema:**
- **Custom o descargado:** (y por qué, en una línea)
- **Carta Gantt** del desarrollo del sitio (5 al 25 de noviembre). Puedes usar esta tabla o un diagrama Mermaid.

| Etapa | Desde | Hasta | Notas |
|---|---|---|---|
| Identidad visual | | | |
| Home | | | |
| Páginas | | | |
| Plugins | | | |
| **Checkpoint (18 nov)** | | 18 nov | |
| Ajustes y formulario | | | |
| **Entrega final (25 nov)** | | 25 nov | |

Ejemplo con Mermaid (GitHub lo muestra como gráfico):

````
```mermaid
gantt
    dateFormat YYYY-MM-DD
    title Plan de mi sitio
    section Tema
    Identidad visual :2026-11-05, 4d
    Home             :2026-11-09, 4d
    section Contenido
    Páginas          :2026-11-12, 5d
    Plugins          :2026-11-14, 4d
    Checkpoint           :milestone, 2026-11-18, 0d
    Ajustes          :2026-11-19, 6d
    Entrega final    :milestone, 2026-11-25, 0d
```
````

## 4. Plan B (5 pts)

Qué hago si algo no funciona. **Al menos 3 riesgos**, cada uno con su mitigación y cuándo se activa.

| Riesgo | Qué hago | Cuándo se activa (fecha o señal) |
|---|---|---|
| El tema propio no funciona o se rompe | | |
| Un plugin falla o no es compatible | | |
| | | |

## Cambios respecto de la Sumativa 2 (solo en el checkpoint del 18 nov)

| Qué cambié | Qué había antes | Por qué | Evidencia (captura o commit) |
|---|---|---|---|
| | | | |

**Decisión:** (continúo con mi propuesta / pivoteo, y por qué)

