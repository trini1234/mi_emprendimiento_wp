# Plantilla: `plan-de-continuidad.md`

Copia este contenido en un archivo `plan-de-continuidad.md` en la carpeta `proyecto/` de tu repo y complétalo. Vale **8 puntos** en la Entrega final.

---

# Plan de continuidad · Etapa 2 de mi sitio

**Emprendimiento:** (nombre)
**Sitio de la etapa 1:** (URL)
**Fecha:** (fecha)

## 1. Qué quedó fuera de la etapa 1 y por qué (3 pts)

Lista las funcionalidades que quisiste hacer y no pudiste. Para cada una, la razón.

| Funcionalidad | Por qué quedó fuera (tiempo, recursos, costo, conocimientos) | Qué aporta a mi emprendimiento |
|---|---|---|
| Formulario de contacto que envíe los mensajes a mi correo | Lo hice, pero los mensajes solo llegan al panel de WordPress y no a mi correo. Al parecer el hosting gratuito no permite enviar correos bien, y tampoco pude hacer que el diseño del formulario se guardara | Me avisaría apenas una clienta escribe, sin tener que entrar a WordPress |
| Agenda online con calendario (que la clienta vea horas libres y reserve sola) | Hoy se agenda por WhatsApp e Instagram, que es manual. No tuve tiempo de probar un plugin de reservas y mi hosting tiene límites | Evitaría el ir y venir de mensajes para cuadrar horarios y ayudaría a ordenar mi agenda |
| Tienda con WooCommerce para vender productos de cuidado de pestañas | Es un plugin pesado, mi hosting gratuito no lo soporta bien y no tengo un medio de pago seguro | Sería un ingreso extra además de los servicios |
| Sección de reseñas de clientas | No alcancé a incluirla ni sabía bien cómo pedir y mostrar testimonios | Daría confianza a clientas nuevas |

## 2. Recursos que necesito (2 pts)

| Funcionalidad | Plugin o herramienta | Gratis o de pago | Costo aproximado | Qué tendría que aprender |
|---|---|---|---|---|
| Que el formulario envíe correos | Un hosting de pago y/o el plugin WP Mail SMTP | El plugin tiene versión gratis, el hosting es de pago | Plugin $0. El hosting hay que cotizarlo | Configurar el envío de correos y probar que lleguen |
| Agenda online | Bookly o Amelia | Versión gratis con funciones limitadas y versión de pago | $0 la gratis (Pro: aprox. US$29 al año en oferta, normalmente US$99)| Configurar servicios, horarios y avisos por correo |
| Tienda online | WooCommerce | El plugin es gratis, pero los medios de pago cobran comisión | $0 el plugin, más comisión por venta | Crear productos, envíos y medios de pago |
| Reseñas | Bloque de testimonios del mismo editor de WordPress | Gratis | $0 | Pedir reseñas a mis clientas y publicarlas |

**Servidor:** (qué hosting necesitaría para la etapa 2 y por qué: espacio, PHP, base de datos, certificado SSL).

## 3. Priorización y cronograma (2 pts)

Ordena lo que harías primero y en cuánto tiempo. Puedes usar una tabla o un diagrama Gantt.
| Prioridad | Qué hago | Cuándo (mes o semana) | Resultado esperado |
|---|---|---|---|
| 1 | Arreglar el formulario de contacto para que los mensajes lleguen a mi correo y el diseño se guarde bien | Semana 1 | Recibir los mensajes de las clientas en mi correo sin entrar a WordPress |
| 2 | Cambiar a un hosting de pago e instalar Bookly (empezando con la versión gratis) | Semanas 2 y 3 | Que las clientas reserven su hora online y me lleguen los avisos |
| 3 | Agregar una sección de reseñas de clientas y, después, la tienda con WooCommerce | Mes 2 | Más confianza en el sitio y un ingreso extra vendiendo productos de pestañas |

## 4. Riesgos y mitigación (1 pt)

| Riesgo | Qué haría | Cuándo se activa |
|---|---|---|
| Los correos del formulario seguirían sin llegar aunque cambiara de hosting | Probaría un plugin de correo (SMTP) como WP Mail SMTP y dejaría WhatsApp e Instagram como respaldo para no perder clientas | Si después de configurarlo no me llegaran los mensajes de prueba |
| El hosting de pago sería más caro de lo que podría pagar | Empezaría con el plan más barato y subiría de plan solo si el negocio lo necesitara | Cuando cotizara y viera el precio real |
| Bookly o el plugin de pagos costarían más de lo previsto (la oferta de Black Friday termina el 1 de diciembre) | Me quedaría con la versión gratis de Bookly y pasaría a Pro solo si la necesitara | Cuando viera el precio final antes de instalarlo |
| El sitio se pondría lento al agregar plugins | Volvería a medir con PageSpeed y desactivaría lo que no fuera necesario | Si el puntaje de Rendimiento bajara de 90 |
| No tendría tiempo para hacer todo en las fechas del cronograma | Cumpliría primero las prioridades 1 y 2 y dejaría la tienda para más adelante | Si en la semana 3 todavía no hubiera terminado el hosting y la agenda |
