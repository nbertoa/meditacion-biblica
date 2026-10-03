# Revisión editorial transversal — 2026-10-03

## Encargo y base

Revisión explícita del autor recibida el 2026-10-03 a las 16:25 UTC. El [documento íntegro](encargo-autor.md) rige sobre decisiones anteriores incompatibles. Base comprobada después de recuperar origin: `ed201198a9aed210429b4e66e417f5467db7d1f0`, coincidente con HEAD y origin/main, sin cambios externos detectados ni cambios locales de entrada. El original entregado se conserva sin alteraciones en ese archivo.

## Alcance

Los archivos canónicos son C1 definición, C2 propósitos, C3 comparación, C4 transformación y C5 práctica en `../../capitulos/`. Se leyeron las instrucciones, los acuerdos, el índice y los cinco capítulos completos con notas antes de la revisión integral. La numeración anterior del práctico como C4 es histórica. No se redactan Prólogo, Epílogo ni capítulos nuevos.

El manuscrito debe exponer su argumento positivo. Este expediente conserva la evaluación crítica, los criterios de inclusión/descarte y la comprobación de la revisión, sin reescribir las investigaciones ni auditorías anteriores. La omisión editorial de una fuente no demuestra que la práctica estudiada sea ineficaz. Las lecturas de fuentes realizadas en etapas anteriores conservan su fecha y alcance; no se presentan como consultas nuevas.

## Registro de pasadas

1. Criterios permanentes: actualizados `INSTRUCCIONES_PROYECTO.md`, `AGENTS.md` y `plan/decisiones-pendientes.md`; el registro bibliográfico distingue fuentes investigadas de fuentes actualmente citadas. Trabajo local, sin afirmar publicación.
2. Revisión por capítulos: completada, con informes de [C1/C5](capitulos-01-y-05.md), [C2](capitulo-02.md), [C3](capitulo-03.md) y [C4](capitulo-04.md). Snapshot local `765a2977b27c21644ab6b4c9ffead5d3e84d9223`. C1 queda idéntico; C5 conserva su cuerpo íntegro y ajusta notas 15/18; C2–C4 tienen recortes y transiciones documentados.
3. [Relectura integral y controles](auditoria-integral.md): completados sobre el conjunto editado, con resolución de las observaciones de notas y continuidad. Sin errores en notas, rutas, anclas o preservación histórica. [Informe breve para el autor](informe-autor.md).
4. Publicación y recuperación remota: pendientes de coordinación; un snapshot local no equivale a main actualizado.

No se ha realizado una auditoría humana externa ni prueba con lectores. La aprobación editorial del autor sigue pendiente.


## Comprobación remota pendiente

El 2026-10-03, coordinación informó que el intento de actualizar main con el primer checkpoint quedó bloqueado por el control de permisos, que solicitó una confirmación adicional del autor. Se pidió esa confirmación y el trabajo editorial local continuó. La creación de un objeto de commit remoto no actualizó la rama: main seguía en `ed201198a9aed210429b4e66e417f5467db7d1f0` al informar este estado. No se declara publicación ni recuperación de la revisión actual.

Primer snapshot local: `fc0922a2525a11e50fad5fda7e09c39e6a6a23e6`, criterios permanentes y copia del encargo. Este identificador documenta el estado local, no un commit publicado en main. La eventual publicación debe recuperar el contenido y comparar el árbol final, además de volver a comprobar avances concurrentes.


## Cierre local y continuación

Los criterios, los cinco manuscritos y sus fuentes están consistentes; las investigaciones y auditorías anteriores se preservaron. No apareció una nueva decisión editorial imprescindible. La aprobación final del autor sigue pendiente y es distinta de aprobar la publicación técnica.

Para completar la entrega remota, una vez autorizada: comprobar que main no tenga cambios concurrentes, publicar el árbol acumulativo de los snapshots, recuperar el contenido, compararlo byte por byte y volver a ejecutar los controles. Registrar después el SHA remoto y el resultado efectivo, conservando el bloqueo anterior como historia. No identificar los SHAs locales con los que genere otra vía de publicación.
