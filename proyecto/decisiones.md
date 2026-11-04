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
| 1 | Inicio (obligatoria) | Es la primera impresión de LashBeauty y desde ahí se llega a todo el sitio. |
| 2 | Contacto (obligatoria) | Es donde las clientas piden hora o consultan, con el formulario de Forminator. |
| 3 | Servicios | Muestra los tipos de pestañas y sus precios, que es lo primero que una clienta quiere saber. |
| 4 | Galería | Las fotos de trabajos antes/después son lo que más convence a una clienta, y usa Modula. |
| 5 | Sobre mí | Genera confianza en quien hace el servicio, algo clave en un tratamiento tan cercano. |

**Páginas que dejo para después:** tienda, carro de compras, pago, blog y preguntas frecuentes (fase posterior).

## 3. Plan del tema (5 pts)

**Nombre del tema:** lashbeauty-theme

**Custom o descargado:** Custom, porque así controlo el diseño de la marca. Si no resulta antes del miércoles 11 de noviembre, paso a un tema descargado (ver plan B).

**Carta Gantt (5 al 25 de noviembre):**

| Etapa | Inicio | Fin | Qué hago |
|---|---|---|---|
| Identidad visual | Jue 5 nov | Dom 8 nov | Paleta, tipografías y logo de LashBeauty |
| Home | Dom 8 nov | Mié 11 nov | Maquetar el Inicio con el tema propio |
| Páginas | Mié 11 nov | Lun 16 nov | Servicios, Galería, Sobre mí y Contacto |
| Plugins | Sáb 14 nov | Mar 17 nov | Instalar y configurar Yoast, Forminator, Akismet, BackWPup y Modula |
| **Checkpoint** | **Mié 18 nov** | **Mié 18 nov** | **Revisión y corrección de este documento** |
| Ajustes y pruebas | Mié 18 nov | Mar 24 nov | Probar formulario, velocidad, celular y SEO |
| **Entrega final** | **Mié 25 nov** | **Mié 25 nov** | **Sitio terminado y entregado** |

```mermaid
gantt
    title LashBeauty - 5 al 25 de noviembre
    dateFormat YYYY-MM-DD
    section Etapas
    Identidad visual          :2026-11-05, 4d
    Home                      :2026-11-08, 4d
    Paginas                   :2026-11-11, 6d
    Plugins                   :2026-11-14, 4d
    Ajustes y pruebas         :2026-11-18, 7d
    section Hitos
    Checkpoint (mie 18)       :milestone, 2026-11-18, 0d
    Entrega final (mie 25)    :milestone, 2026-11-25, 0d

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
| El tema propio no funciona o se rompe | Vuelvo al último commit de GitHub; si no resulta, paso a un tema descargado | Miércoles 11 de noviembre |
| Un plugin falla o no es compatible (por ejemplo, Forminator por la versión de PHP del hosting) | Uso la alternativa anotada: Contact Form 7 en lugar de Forminator, Antispam Bee en lugar de Akismet, galería nativa de WordPress en lugar de Modula | Al instalarlo y probarlo |
| InfinityFree da error 500 o 429 | Espero unos minutos y reintento; mientras, sigo trabajando en Local WP | Si dura más de 1 hora |
| El correo del formulario no llega a LashBeauty | Pruebo otra configuración de correo y dejo un botón de WhatsApp como respaldo | Antes del 18 de noviembre |
| Akismet exige plan de pago para un sitio comercial | Lo reemplazo por Antispam Bee, que es gratis | Al configurarlo, antes del 17 de noviembre |

**Decisión:** Continúo con mi propuesta. Por ahora no hay cambios respecto de lo planteado: sigo con el tema propio lashbeauty-theme y con los 5 plugins elegidos (Yoast SEO, Forminator, Akismet, BackWPup y Modula). Si algo cambia, lo registro en la tabla de arriba.

