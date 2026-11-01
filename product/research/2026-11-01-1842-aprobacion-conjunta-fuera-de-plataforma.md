---
source: secondary
method: web
date: 2026-11-01
question: Qué exige la normativa sobre firma conjunta, cómo resuelven la aprobación conjunta bancos y competidores, qué hacen las pymes hoy y si el mercado cobra el multifirma
opportunity: aprobacion-conjunta-fuera-de-plataforma
---

# Research: Aprobación conjunta fuera de la plataforma

La firma conjunta ya existe en canales bancarios argentinos, así que es probable que las farmacias tengan una alternativa, y hay que entender por qué no pagan por ahí cuando la necesitan. En Payway, Mercado Pago y Fiserv no encontré multifirma, lo que es una posible diferencia pero no prueba que no lo tengan ni que el mercado lo pida. No encontré ninguna norma del BCRA que exija firma conjunta en cuentas de pago, y tampoco puedo descartarla: es el dato más urgente para pedirle a compliance.

## Método y límites

- Búsqueda web y lectura de páginas, en secuencia, sin subagentes. Todas las consultas son del 2026-11-01.
- **Los PDF del BCRA no se pudieron leer** en este entorno. Lo que se cita de ellos viene de extractos de búsqueda, sin lectura del texto completo ni confirmación de vigencia.
- **La ayuda de Mercado Pago bloqueó la lectura directa** (HTTP 403). Lo que se cita viene de extractos de búsqueda.
- Tampoco se pudieron leer directamente el instructivo de alta de Interbanking y el PDF de Banco Ciudad: se citan por extractos, marcados como tales.
- El buscador opera desde EE. UU., así que puede haber menos fuentes argentinas.
- "No aparece" significa que no lo encontré, no que el producto no lo tenga.
- "Firsev" se interpretó como Fiserv. "Procesadores de bancos" se cubrió con Interbanking y los canales de empresas de los bancos.

## Competidores directos y canales bancarios

| Actor | Firma conjunta | App o celular | Costo |
|---|---|---|---|
| Interbanking | Sí: esquema de firmas, con límites; el banco lo valida. Tope de 3 firmantes por confirmar | Autoriza transferencias y mantiene el esquema de firmas | Operadores adicionales sin costo, según un extracto |
| Macro | Sí: cada firmante autoriza con su token | Token en el celular; no confirma si se autoriza desde la app | Desconocido |
| BBVA | "Pendiente de firmas"; sin detalle del esquema | Desconocido | Desconocido |
| Banco Ciudad | Sí: distingue firma indistinta y conjunta (2, 3 o más), según un extracto | Firmantes con app de token, según un extracto | Desconocido |
| Payway | No aparece: Owner, Administrador, Operador | Desconocido | Desconocido |
| Mercado Pago | No aparece: colaboradores con permisos | Desconocido | Desconocido |
| Fiserv | No aparece: el portal se describe para ver ventas y liquidaciones | Desconocido | Desconocido |

**Interbanking**

- Según un manual de suscripción, cada esquema admite hasta tres firmantes y cada cuenta puede tener varios esquemas. [verificado: https://interbanking.bank/manualesSIB/Suscripcion_Cliente_v2_0_20190325.pdf — extracto de búsqueda, 2026-11-01; manual de 2019. Ese dominio no es el del sitio argentino (interbanking.com.ar) y no confirmé que describa el servicio en Argentina, así que el tope de 3 firmantes queda por confirmar]
- La app permite autorizar y enviar transferencias, da acceso al token digital y dice mantener el esquema de firmas. [verificado: https://apps.apple.com/vg/app/interbanking/id1633468860 — 2026-11-01]
- Si la empresa tiene autorización conjunta, un segundo administrador debe autorizar el alta; luego se pueden sumar operadores, cuentas y bancos sin costo. [verificado: https://www.ca.gob.ar/legacy/descargar/sircar/Instructivo_Alta_PagosBtoB_Interbanking.pdf — extracto de búsqueda, 2026-11-01]
- El banco debe habilitar el esquema creado, y se pueden fijar límites por importe y tipo de transferencia. El resumen de búsqueda atribuye esto a una "fuente argentina" sin nombrarla; lo más probable es que sea este instructivo de Bancor, cuyo texto no pude leer. [verificado: https://www.bancor.com.ar/downloads/empresas/ACT-Instructivo-Esquema-de-Firmas.pdf — extracto de búsqueda, 2026-11-01; archivo de 2022; atribución por confirmar]

**Bancos**

- Macro: cada firmante debe tener el token activo en su celular y autoriza desde "Autorizaciones" de Banca Internet Empresas. La página no dice que se autorice desde la app. [verificado: https://www.macro.com.ar/empresas/cobros-y-pagos/pagos/transferencias — 2026-11-01]
- BBVA: permite aprobar transferencias desde "Pendiente de firmas", sin detallar el esquema. [verificado: https://www.bbva.com.ar/empresas/productos/cobros-pagos/pagos/transferencias.html — extracto de búsqueda, 2026-11-01]
- Banco Ciudad: distingue firma indistinta y conjunta (2, 3 o más firmantes); los operadores cargan datos y los firmantes firman con la app Link Token Empresas. [verificado: https://www.bancociudad.com.ar/cms/recursos/institucional/carpetarecurso/BEE%203.0/CanalesDeContacto/01.BEE_-_Realizar_Transferencias_Inmediatas_-_Primera_transferencia_por_APP_Token.pdf — extracto de búsqueda, 2026-11-01]
- Galicia y Banco Nación: no encontré información. Desconocido.

**Competidores que nombró el equipo**

- Payway: Owner, Administrador y Operador, con autorizaciones descritas de forma individual. La página no menciona firma conjunta. [verificado: https://ayuda.payway.com.ar/cuenta-payway/perfiles — 2026-11-01]
- Mercado Pago: colaboradores por invitación, con perfiles como Cajero o Administrador y permisos manuales. Para crear una cuenta empresa se requiere autorización legal. No encontré un permiso de aprobación de transferencias. [verificado: https://www.mercadopago.com.ar/ayuda/crear-y-administrar-colaboradores_4026 y https://www.mercadopago.com.ar/developers/es/docs/collaborators — extractos de búsqueda, 2026-11-01]
- Fiserv: la web de comercios se describe para ver ventas, cupones y liquidaciones, en una nota de marca. No encontré usuarios adicionales ni firmantes para Argentina. [verificado: https://www.iprofesional.com/contenido-brandeado/369450-posnet-la-terminal-mas-elegida-por-comercios-para-pagos-agiles — extracto de búsqueda, 2026-11-01]

**Qué prueba y qué no:** que los bancos lo ofrezcan muestra que el mecanismo existe para empresas en Argentina. No prueba que tu segmento lo use, ni que vaya a usarlo en Farmapay. No encontrarlo en los competidores tampoco prueba que el espacio esté libre ni que haya demanda.

## Normativa

No encontré una norma que exija firma conjunta para operar una cuenta de pago. No se puede descartar: los PDF no se leyeron completos. Lo más cercano:

- A 8444 (04/06/2026): identificar a representantes legales o apoderados y presentar copia certificada del estatuto o contrato social. [verificado: https://www.bcra.gob.ar/archivos/Pdfs/comytexord/A8444.pdf — extracto de búsqueda, 2026-11-01]
- A 7783 (02/06/2023): autenticación multifactor en acciones críticas. Vigencia no confirmada. [verificado: https://www.bcra.gob.ar/archivos/Pdfs/comytexord/A7783.pdf — extracto de búsqueda, 2026-11-01]
- A 4063 (cuenta corriente): en cuentas a orden conjunta, el banco solo acepta cheques firmados por todos los titulares. Es sobre cheques en cuenta corriente, no sobre cuentas de pago. [verificado: https://www.bcra.gob.ar/archivos/Pdfs/texord/texcomp/A4063n-cc.pdf — extracto de búsqueda, 2026-11-01]
- A 8454 (14/07/2026): actualiza el texto ordenado de proveedores de servicios de pago y remite la verificación de identidad al punto 5.5.2.1 del texto de Sistema Nacional de Pagos. No revisé ese punto. [verificado: https://www.bcra.gob.ar/archivos/Pdfs/comytexord/A8454.pdf — extracto de búsqueda, 2026-11-01]
- Circular RUNOR 1-1952, "Firmas Autorizadas ante el BCRA" (30/03/2026): por su título parece referirse a firmas ante el BCRA, no a firmas de clientes; no confirmado. [verificado: https://www.adeba.com.ar/a-8414 — 2026-11-01]

**Para legal o compliance:**

- A 8471 (27/08/2026): trata riesgo de fraude y fija obligaciones desde el 01/01/2027 para ciertos proveedores de pago. No sé si afecta a Farmapay ni si se relaciona con firmas; vale revisarla porque el equipo informó que no hay plazos. [verificado: https://www.bcra.gob.ar/archivos/Pdfs/comytexord/A8471.pdf — extracto de búsqueda, 2026-11-01]
- Una nota de prensa de 2024 dice que los fondos se acreditan en una cuenta CVU de cada farmacia. Eso sugiere, sin confirmarlo, que Farmapay opera con cuentas de pago, y por eso busqué normas de ese régimen. [verificado: https://www.ambito.com/negocios/lanzan-plataforma-fintech-unica-su-segmento-potenciar-la-industria-farmaceutica-n6079898 — 2026-11-01]

## Alternativas y no consumo

Casi no hay nada documentado sobre cómo coordinan la firma conjunta las pymes. No encontré fuentes sobre llamadas, WhatsApp o usuarios compartidos para aprobar pagos.

- Aparecieron casos sueltos de fraude por WhatsApp, como comprobantes falsos de transferencias en Misiones. No tratan de aprobación entre firmantes: son una señal débil del riesgo del canal. [verificado: https://www.canal12misiones.com/?p=663393 — extracto de búsqueda, 2026-11-01]
- La alternativa más concreta es el propio banco, con el esquema de firmas de la tabla. Falta saber si las farmacias lo usan para estos pagos.

## Precios y modelos de negocio

- EE. UU., según un blog de un competidor (Slash, 28/10/2026): Mercury, Brex y Rho incluirían aprobaciones en su plan de $0; Brex, solo con un segundo administrador. Ramp incluye flujos configurables gratis y cobra la aprobación de liberación de pagos. La información de Relay es contradictoria. [verificado: https://www.slash.com/blog/business-bank-accounts-multi-step-approvals — 2026-11-01]
- Argentina: desconocido. Solo apareció que Interbanking permite sumar operadores sin costo, según un extracto; eso no es el precio del servicio.

## Posicionamiento

Según lo encontrado, hay dos grupos: los canales bancarios y multibanco, donde el esquema de firmas es parte del servicio, y los adquirentes y billeteras, donde aparecen perfiles y permisos individuales. No encontré a nadie que combine pagos del sector farmacéutico con firma conjunta, pero esta búsqueda no alcanza para afirmar que no exista.

## Tendencias y tamaño de mercado

No se investigó el tamaño de mercado: no cambia ninguna decisión de esta oportunidad. Solo como orden de magnitud, una nota de prensa de 2024 menciona alrededor de 14.000 farmacias en Argentina. [verificado: https://www.ambito.com/negocios/lanzan-plataforma-fintech-unica-su-segmento-potenciar-la-industria-farmaceutica-n6079898 — 2026-11-01]

## Impacto en creencias

Revisado con el equipo. La numeración es la de `product/overview.md` a esta fecha. Los veredictos no modifican el overview: lo decide `/review-evidence`.

| Creencia (de overview.md)                                                                                   | Veredicto                           | Evidencia                                                                                     |
| ----------------------------------------------------------------------------------------------------------- | ----------------------------------- | --------------------------------------------------------------------------------------------- |
| 1. [opportunity: aprobacion-conjunta-fuera-de-plataforma] [value] La mayoría sufrió demoras u observaciones | no dice nada                        | Es sobre las usuarias de Farmapay                                                             |
| 2. [product] [value] Se llaman por falta de canal                                                           | no dice nada                        | Que exista la app no muestra que dejen de llamarse                                            |
| 3. [product] [viability] Las auditorías llevan a limitar la operación o irse                                | no dice nada                        | Sin evidencia de auditorías ni bajas; la norma sigue sin citarse                              |
| 4. [product] [value] La necesidad va más allá de las cadenas                                                | apoya, débilmente                   | Bancos de distinto tamaño ofrecen firma conjunta a empresas; no muestra adopción en farmacias |
| 5. [product] [viability] Sin costo, se paga con retención y volumen                                         | apoya, débilmente, solo "sin costo" | Referencia de EE. UU. (Slash); nada sobre retención                                           |
| 6. [product] [value] Parte de los firmantes prefiere el portal                                              | no dice nada                        | Web y app conviven en bancos, pero eso no indica preferencia                                  |

Restricción normativa del brief: sigue sin confirmar. Esta investigación no encontró la norma, y eso no la contradice.

## Qué sigue necesitando research primario

**Consulta interna, antes de la encuesta**

- Legal o compliance: norma exacta, a quién obliga, qué operaciones cubre, y si la A 8471 afecta a Farmapay.

**Encuesta (cuántas, con qué frecuencia)**

- Creencia 1: cuántas farmacias tuvieron demoras u observaciones de auditoría.
- Creencia 4: cuántas exigen firma conjunta, más allá de las grandes cadenas.
- Cuántas ya usan firma conjunta en su banco para estos mismos pagos.

**Entrevistas (por qué, qué hacen hoy)**

- Creencia 2: si se llaman por falta de canal o porque necesitan conversar la decisión.
- Creencia 3: qué pasa cuando una auditoría observa el esquema.
- Creencia 5: si esto retendría a las cadenas o aumentaría su volumen.
- Creencia 6: quiénes preferirían seguir en el portal, y por qué.
- Por qué siguen pagando por Farmapay si el banco ya resuelve la firma conjunta.
