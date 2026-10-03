# Revisión editorial transversal — 2026-10-03

## Encargo y base

Revisión explícita del autor recibida el 2026-10-03 a las 16:25 UTC. El [documento íntegro](encargo-autor.md) rige sobre decisiones anteriores incompatibles. Base comprobada después de recuperar origin: `ed201198a9aed210429b4e66e417f5467db7d1f0`, coincidente con HEAD y origin/main, sin cambios externos detectados ni cambios locales de entrada. El original entregado se conserva sin alteraciones en ese archivo.

## Alcance

Los archivos canónicos son C1 definición, C2 propósitos, C3 comparación, C4 transformación y C5 práctica en `../../capitulos/`. Se leyeron las instrucciones, los acuerdos, el índice y los cinco capítulos completos con notas antes de la revisión integral. La numeración anterior del práctico como C4 es histórica. No se redactan Prólogo, Epílogo ni capítulos nuevos.

El manuscrito debe exponer su argumento positivo. Este expediente conserva la evaluación crítica, los criterios de inclusión/descarte y la comprobación de la revisión, sin reescribir las investigaciones ni auditorías anteriores. La omisión editorial de una fuente no demuestra que la práctica estudiada sea ineficaz. Las lecturas de fuentes realizadas en etapas anteriores conservan su fecha y alcance; no se presentan como consultas nuevas.

## Registro de pasadas

1. Criterios permanentes: actualizados `INSTRUCCIONES_PROYECTO.md`, `AGENTS.md` y `plan/decisiones-pendientes.md`; el registro bibliográfico distingue fuentes investigadas de fuentes actualmente citadas. Snapshot local `fc0922a2525a11e50fad5fda7e09c39e6a6a23e6`, posteriormente publicado con árbol idéntico; véase la correspondencia del cierre remoto.
2. Revisión por capítulos: completada, con informes de [C1/C5](capitulos-01-y-05.md), [C2](capitulo-02.md), [C3](capitulo-03.md) y [C4](capitulo-04.md). Snapshot local `765a2977b27c21644ab6b4c9ffead5d3e84d9223`. C1 queda idéntico; C5 conserva su cuerpo íntegro y ajusta notas 15/18; C2–C4 tienen recortes y transiciones documentados.
3. [Relectura integral y controles](auditoria-integral.md): completados sobre el conjunto editado, con resolución de las observaciones de notas y continuidad. Sin errores en notas, rutas, anclas o preservación histórica. [Informe breve para el autor](informe-autor.md).
4. Publicación y recuperación remota: completadas en `2fe2b5c95b1afd414779a969449e5a776ab30531`, con correspondencia de los tres checkpoints y comprobación de los 66 archivos. La constancia siguiente distingue los SHAs locales de los publicados.

No se ha realizado una auditoría humana externa ni prueba con lectores. La aprobación editorial del autor sigue pendiente.


## Historial del bloqueo y su resolución

El 2026-10-03, coordinación informó que el intento de actualizar main con el primer checkpoint quedó bloqueado por el control de permisos, que solicitó una confirmación adicional del autor. Se pidió esa confirmación y el trabajo editorial local continuó. La creación de un objeto de commit remoto no actualizó la rama: main seguía en `ed201198a9aed210429b4e66e417f5467db7d1f0` al informar este estado. En ese momento no se declaró publicación ni recuperación de la revisión actual.

Primer snapshot local: `fc0922a2525a11e50fad5fda7e09c39e6a6a23e6`, criterios permanentes y copia del encargo. Este identificador documenta el estado local, no un commit publicado en main. La comprobación posterior que se registra abajo recuperó el contenido y comparó el árbol final, además de confirmar el estado de main.


## Cierre editorial y publicación

Los criterios, los cinco manuscritos y sus fuentes están consistentes; las investigaciones y auditorías anteriores se preservaron. No apareció una nueva decisión editorial imprescindible. La aprobación final del autor sigue pendiente y es distinta de aprobar la publicación técnica.

La autorización adicional y la entrega remota quedaron verificadas como se detalla a continuación. Los SHAs locales conservan su función de snapshots; los SHAs publicados identifican el contenido real de main. El bloqueo anterior permanece como historia de esta revisión.


## Publicación y recuperación verificadas — 18:55–18:56 UTC

El autor respondió «Confirmo» el 2026-10-03 a las 18:51:28 UTC a la pregunta explícita sobre integrar en main esta revisión de los cinco capítulos y sus criterios editoriales. La publicación se completó después de esa respuesta.

| Etapa | Snapshot local | Commit publicado | Árbol coincidente |
|---|---|---|---|
| Criterios y encargo | `fc0922a2525a11e50fad5fda7e09c39e6a6a23e6` | `ea00987562b4bdd373726d8efbd15b1dbeb6d2d8` | `ee6bf7bfe8606e515fc675b4bf4aa899e7ba03e6` |
| Manuscritos e informes | `765a2977b27c21644ab6b4c9ffead5d3e84d9223` | `925fcfbfbb5c7adaf9b9d50abe30d74a9d7f3b95` | `62d9abf412fd3416d8ebef3f1551ad2785a57e67` |
| Cierre integral | `30763cd4c3200176af90f71dfa67c3c95c155f92` | `2fe2b5c95b1afd414779a969449e5a776ab30531` | `33aca81850f8d98df1b0ff1d7d4ea656a141fdaa` |

Se realizó una recuperación propia adicional mediante `git fetch origin`, posterior a la recuperación de coordinación. `origin/main` quedó en `2fe2b5c95b1afd414779a969449e5a776ab30531`. Se compararon los tres árboles y los 66 archivos de la revisión publicada con la versión local íntegramente releída: ninguna diferencia. El checkout estaba limpio y se alineó HEAD con origin/main sin modificar archivos.

El control completo volvió a pasar con cero errores: 427 enlaces relativos, 44 anclas, 96 notas, 100 llamadas y 48 archivos históricos idénticos a la base. No se modificaron fuentes, capítulos ni decisiones durante la recuperación. El [informe al autor](informe-autor.md) y la [auditoría integral](auditoria-integral.md) registran el cierre; los informes por capítulo conservan el estado de sus pasadas anteriores.

Esta constancia se guarda en un commit posterior al contenido comprobado. No se atribuye a `2fe2b5c…` una actualización de estado que aún no contenía, ni se confunde la comprobación técnica con la aprobación editorial del autor. No se creó PR porque la publicación autorizada fue directa a main.
