# valeva

**Vale, va.** Dos sábados al mes, un bar de Valencia —cada vez uno distinto— reservado solo para solteros cristianos en el mismo momento vital: abiertos a encontrar a alguien con quien construir un proyecto de vida.

Sin actividades, sin presentaciones, sin presión. Vas con tus amigos, te sientas en tu mesa y te tomas algo. El bar se desvela por email o WhatsApp a las 18:30 del mismo sábado y la noche empieza a las 21:30.

## Qué hay aquí

| Ruta | Contenido |
| --- | --- |
| `index.html` | La web completa en un solo archivo (HTML, CSS y JavaScript sin dependencias) |
| `img/` | Fotografías de la web |
| `assets/valeva-simbolo.svg` | Símbolo de la marca (también se usa como favicon) |
| `aviso-legal.html`, `privacidad.html`, `condiciones.html`, `cookies.html` | Textos legales. Los datos marcados en amarillo (titular, NIF, domicilio…) están pendientes de completar |

## Estado

- Las fechas, plazas libres y estadísticas anónimas por sexo y edad se leen de la base de datos (Supabase, proyecto «Eventos»).
- Al pulsar **Pagar** se crea la reserva y el cliente paga en la pasarela de **Stripe**. Al volver, la web muestra la entrada con su código QR (un QR por reserva, válido para todo el grupo).
- Las noches se crean y editan en la tabla `events` de Supabase.

## Publicarla con GitHub Pages

1. En el repositorio, ve a **Settings → Pages**.
2. En **Source**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
3. Guarda. En uno o dos minutos la web estará en `https://estebancalvobayarri.github.io/valeva/`.

Para usar un dominio propio (por ejemplo, `valeva.es`), añádelo en la misma pantalla de Pages y configura el DNS del dominio según indica GitHub.

## Identidad

- Colores: azul burbuja `#2A5BD7`, tinta `#16181D`, gris texto `#6B7079`, gris línea `#E9EAEE`, gris fondo `#F5F6F8`.
- Tipografía: [Manrope](https://fonts.google.com/specimen/Manrope).
- El logotipo es la burbuja con el doble check y la palabra «vale» en tinta + «va» en azul.
