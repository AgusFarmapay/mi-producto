---
status: framed
segment: Farmacias personas jurídicas cuyo esquema exige firma conjunta, de cualquier tamaño, empezando por las grandes cadenas
personas: graciela-ferreyra, martin-sosa, ruben-quiroga, carolina-mendez, lucia-paz
---

# Opportunity: Aprobación conjunta fuera de la plataforma

En las farmacias con firma conjunta, solo el primer representante legal onboardeado puede ejecutar operaciones en Farmapay, y la decisión entre firmantes ocurre fuera de la plataforma: no deja evidencia y depende de poder ubicar a cada persona; importa ahora porque las grandes cadenas lo plantean y la firma conjunta se informa como exigencia del BCRA y de auditorías.

## Segment and personas

- Graciela Ferreyra (primary) — suffers it
- Martín Sosa (primary) — suffers it
- Rubén Quiroga (secondary) — suffers it, con menos intensidad
- Carolina Méndez (tertiary) — suffers it, por el lado de la evidencia; es quien mejor responde la viabilidad
- Lucía Paz (negative) — does not suffer it
- Missing: quien prepara las operaciones (administración o tesorería)

Tamaño del segmento: desconocido. Las ≈923 personas jurídicas tienen esquema de firmas, pero no sabemos cuántas exigen firma conjunta.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| Solo el primer representante legal onboardeado puede ejecutar operaciones | real | Funcionamiento actual del portal, informado por el equipo |
| ≈923 personas jurídicas con esquema de firmas (25% de 3693) | real | Bases y reportes de onboarding; sin archivo en el repo |
| El titular consulta a los demás firmantes por fuera antes de aprobar | real | Reuniones y confirmaciones de las farmacias; sin notas en el repo |
| Las grandes cadenas (≈20% de las personas jurídicas) piden el multifirma | unverified | Charlas entre ejecutivos comerciales y gerencias; sin pedido formal, 20% estimado |
| La firma conjunta es exigencia del BCRA y de auditorías internas y externas | unverified | Informado por el equipo; falta citar la norma |
| Las personas que sufren el problema y cómo lo viven | synthetic | product/personas/ |

Hallazgo: no hay señales sobre el costo del problema (demoras, observaciones de auditoría, fraudes, reclamos o bajas).

## Business outcome

Retener a las farmacias con firma conjunta y aumentar el volumen que operan en Farmapay. Falta la línea de base de retención y volumen de este segmento.

## Constraints

- Normativa: la firma conjunta es exigencia del BCRA y de auditorías internas y externas. Falta citar la norma y saber a quién obliga.
- Seguridad: el token/OTP actual no se puede modificar.
- Fricción: no duplicar procesos de alta ni agregar fricción a quienes prefieren el portal.
- Operaciones alcanzadas: transferencias, préstamos, pagos a droguerías, seguros y otras. Falta confirmar si la exigencia cubre todas por igual.
- Fechas: no hay plazos ni exigencias que fijen una fecha — informado por el equipo.

## Beliefs

Referencias a product/overview.md:

- [opportunity: aprobacion-conjunta-fuera-de-plataforma] [value] La mayoría de las farmacias con firma conjunta tuvo, en los últimos 6 meses, al menos una operación demorada por no poder ubicar a un firmante o una observación de auditoría por falta de evidencia de la decisión conjunta.
- [product] [viability] Se ofrece sin costo y se paga con retención y volumen: las grandes cadenas que lo pidieron operarían más, o dejarían de considerar irse.
- [product] [viability] Mientras no exista el multifirma, las farmacias con firma conjunta reciben observaciones de sus auditorías que las llevan a limitar su operación en Farmapay o a considerar irse.
- [product] [value] La necesidad va más allá de las grandes cadenas (alcance).

Para la comparación de soluciones: las creencias sobre la app como reemplazo de la llamada y sobre la convivencia con el portal.

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| Exigencia normativa (restricción) | Consulta a legal o compliance: norma, a quién obliga y operaciones cubiertas | Si el resultado pasa a ser evitar un riesgo regulatorio | Antes de la encuesta |
| Alcance (más allá de las cadenas) | Consulta a las bases de onboarding: cuántas exigen firma conjunta, por tamaño | Tamaño del segmento y si conviene limitarlo a las cadenas | Antes de la encuesta |
| Sin costo, se paga con retención y volumen | Datos propios: retención y volumen del segmento, bajas | Línea de base, y si el resultado de negocio se sostiene | Antes de /explore-solutions |
| La mayoría sufrió demoras u observaciones | Tickets de soporte y luego encuesta a las farmacias del segmento | Avanzar a /explore-solutions o descartar la oportunidad | Antes de /explore-solutions |
| Las observaciones llevan a limitar la operación o irse | Entrevistas a responsables de compliance y a titulares, entre quienes aceptaron en la encuesta | Si el problema amenaza la retención o es solo una molestia | Antes de /explore-solutions |

## Candidate ideas (not evaluated)

- App de Farmapay como canal alternativo de acceso, que reutiliza las credenciales y la validación de dispositivos del Portal.
- Esquema de firmas N de M para aprobar operaciones, disponible en el Portal y en la app, que convive con el token/OTP.
