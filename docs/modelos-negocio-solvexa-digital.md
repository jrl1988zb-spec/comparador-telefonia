# Modelos de negocio para SOLVEXA Digital con IA (Claude) — octubre 2026

> Informe de investigación. Las cifras de mercado proceden casi todas de webs de proveedores
> que venden estos servicios: son orientativas, no datos auditados. Donde no hay datos, se dice.

---

## 0. Lo incómodo primero: qué fallaría con el planteamiento tal cual

El encargo es "crear con todo el potencial de Claude y venderlo". Ese enfoque tiene tres fallos:

1. **El cliente no compra IA, compra un resultado.** Un fontanero de Granada no paga por "un agente
   con Claude"; paga por no perder llamadas o por tener más citas. Si el producto se define por la
   tecnología, compites en precio con software enlatado.
2. **La IA para pymes ya es commodity en España.** Hay recepcionistas de voz con IA desde
   ~29–199 €/mes (Telvia 89 €/mes, Agentiaia 199 €/mes ilimitado, Clinicbot por minuto) y agentes
   de WhatsApp desde 99 €/mes (Inter Linked). Cualquier cosa que construyas con Claude y que un
   cliente pueda comparar con eso, se comparará con eso.
3. **Eres una sola persona.** El cuello de botella no es lo que Claude sabe hacer, es cuántos
   clientes puedes vender, implantar y **mantener** tú. Un agente que atiende 24/7 genera
   incidencias 24/7. Cualquier modelo que exija soporte continuo por cliente se rompe hacia los
   15–25 clientes si no se estandariza.

**Lo que sí es una ventaja real y difícil de copiar** no es Claude (lo tiene todo el mundo), sino:

- Una cartera de clientes de SOLVEXA energía (autónomos y pymes de Granada) que **ya confían en ti**
  y a los que ya les has ahorrado dinero.
- Local físico, 5,0 en Google, trato directo: en una venta local eso pesa más que la tecnología.
- Ya vendes Ads, redes y webs: tienes la parte que genera leads. Lo que falta en casi todas las
  pymes es **qué pasa con el lead después**.

Claude sirve sobre todo para dos cosas: **bajar tu coste de producción** (contenido, informes,
webs, auditorías) y **construir los automatismos** que convierten leads en citas.

---

## 1. Contexto de mercado 2026 que condiciona las decisiones

| Hecho | Estado (oct 2026) | Implicación |
|---|---|---|
| Kit Digital | Sin convocatorias abiertas para solicitar; las últimas cerraron en 2025 | **No** construir el negocio sobre subvenciones |
| Bono de IA (Plan IA360, 600 M€) | Anunciado; sin bases ni convocatoria. Piloto previsto 1.º semestre 2027, general antes de fin de 2027. Excluye "mera suscripción a licencias" | No venderlo. Prepararse para cuando salga (servicios de implantación, no licencias) |
| AI Act art. 50 (transparencia) | En vigor desde 2/8/2026; el Ómnibus Digital aplazó alto riesgo, **no** el aviso de chatbot | Todo agente que montes debe avisar de que es IA. Es también argumento de venta ("te lo dejo legal") |
| Verifactu | Sociedades antes de 1/1/2027; autónomos antes de 1/7/2027 (RDL 15/2025) | Ventana de 9 meses en la que miles de autónomos tienen que cambiar de herramienta de facturación |
| Modo IA de Google | En España desde oct 2025 | La visibilidad en respuestas de IA importa, pero **no he encontrado datos fiables de su impacto en búsquedas locales en España** |

---

## 2. Modelos evaluados

Para cada uno: qué es, qué fallaría, datos disponibles y veredicto.

### 2.1 Recepcionista de voz con IA por nicho (clínicas, talleres, peluquerías, restaurantes)

**Qué es:** número de teléfono que atiende, responde dudas y agenda citas. Modelo de moda en EE. UU.
(retainers de 200–1.000 $/mes por cliente según blogs de plataformas como Trillet o MyVoiceAIConnect).

**Qué fallaría:**
- Competencia directa con SaaS españoles de 29–199 €/mes. No puedes cobrar 400 €/mes por lo mismo.
- La voz falla en lo difícil: precios, seguros, casos raros, acentos, clientes enfadados. Los propios
  proveedores lo reconocen y recomiendan escalado a humano.
- Clínicas = datos de salud (categoría especial RGPD). Un error aquí es un problema serio para un
  autónomo.
- Soporte: si se cae el agente un sábado, el cliente te llama a ti.
- Los ingresos que publican estos blogs ("3.000–15.000 $/mes en 12–18 meses") son de vendedores de
  la plataforma. No los tomaría como referencia.

**Veredicto:** ❌ como producto independiente. ✅ solo como pieza dentro de una oferta mayor (2.2),
y empezando por **WhatsApp/texto**, no voz.

### 2.2 "Ningún lead se pierde": Ads + respuesta inmediata + seguimiento automático ⭐

**Qué es:** extender lo que ya vendes. Hoy haces campañas que generan leads; el paquete añade:
respuesta automática en minutos por WhatsApp/formulario, cualificación con preguntas, agenda de cita,
recordatorios, seguimiento a los que no contestan y petición de reseña tras el servicio.
Informe mensual: leads → contactados → citas → clientes.

**Por qué encaja:**
- Se vende con el resultado que el cliente entiende (citas), no con la tecnología.
- Encaja en tus tramos actuales (300–600 y 600–1.000 €/mes) sin bajar a guerra de precios: no se
  compara con un SaaS de 99 €, se compara con "una agencia que solo pone anuncios".
- Hace medibles tus Ads, que es tu diferenciador declarado ("resultados medibles con datos reales").
- Claude cubre la parte de redacción de respuestas, clasificación de leads y generación de informes.

**Qué fallaría:**
- Depende de que el negocio **atienda** las citas. Si el cliente no coge el teléfono o no tiene
  agenda organizada, el sistema no arregla eso y el cliente culpará al sistema.
- Integraciones con agendas/software de cada sector consumen horas. Hay que elegir **un nicho** y
  una pila de herramientas fija, o cada cliente será un proyecto a medida.
- Coste de WhatsApp Business API por conversación (céntimos, según Javadex) y de plataformas: hay
  que repercutirlo, no comérselo.

**Veredicto:** ✅ **Es la mejor opción.** Es una evolución de lo que ya vendes, no un negocio nuevo.

### 2.3 Visibilidad local: Ficha de Google + reseñas + "aparecer en las respuestas de IA" (GEO)

**Qué es:** optimizar ficha de Google, captar y responder reseñas con IA, datos estructurados en la
web, y contenido pensado para que ChatGPT/Google IA te citen.

**Qué fallaría:**
- Los precios de GEO que circulan (1.500–5.000 $/mes) son de EE. UU. y para marcas; no se trasladan
  a una peluquería de Granada.
- **Medir "aparecer en IA" es poco fiable** y no hay datos de impacto local en España. Venderlo como
  producto estrella es arriesgarse a vender humo, algo contrario a tu posicionamiento.

**Veredicto:** ✅ como componente fijo del paquete (sobre todo reseñas automatizadas y ficha). ❌ como
producto "GEO" caro y separado.

### 2.4 Contenido de redes producido con IA

**Qué es:** ya lo haces. Claude reduce horas por cliente (calendario, copys, variaciones, informes).

**Qué fallaría:** si el cliente nota contenido genérico, deja de valorarlo; y él mismo puede usar
ChatGPT. La IA aquí **mejora tu margen, no tu precio**.

**Veredicto:** ✅ para ganar margen y capacidad. No es un modelo nuevo que vender.

### 2.5 Ventana Verifactu: migración de facturación + automatización administrativa

**Qué es:** entre ahora y julio de 2027 muchos autónomos tienen que pasar a un software de facturación
adaptado. Oferta: elegir y dar de alta un software certificado, importar clientes/productos, y
automatizar lo de alrededor (presupuestos, recordatorios de cobro, envío de facturas a la gestoría).

**Qué fallaría:**
- No eres gestoría ni fabricante de software: no debes asumir responsabilidad fiscal. Si algo sale
  mal en una factura, el problema es serio.
- Es un ingreso **puntual** con fecha de caducidad (julio 2027), no recurrente.
- Las gestorías y los propios fabricantes (Holded, etc.) ya están moviendo este mercado.

**Veredicto:** 🟡 solo como **puerta de entrada**, y mejor **aliado con una o dos gestorías** de
Granada (ellas tienen los autónomos; tú haces la parte técnica). No como línea principal.

### 2.6 Auditoría gratuita automatizada como captación (energía + digital) ⭐

**Qué es:** ya regalas auditoría y estudio energético. Con Claude puedes generar en minutos un informe
de presencia digital de cualquier negocio (web, ficha de Google, reseñas, redes, competencia local) y
presentarlo de viva voz. Y a tus clientes de energía ofrecérselo como "segunda revisión gratuita".

**Qué fallaría:** si el informe es genérico, no convence. Tiene que mostrar 3 problemas concretos de
**ese** negocio con datos verificables. Y no hay que inventar proyecciones de resultados.

**Veredicto:** ✅ No es un producto que se cobre, pero probablemente es el mejor uso de Claude para
**vender** el 2.2. Reduce tu coste por propuesta.

### 2.7 Formación / talleres de IA para pymes

**Qué fallaría:** ticket bajo, no recurrente, mucha competencia gratuita, y la tentación de colgarlo del
Bono de IA, que **no existe todavía**. Cualquiera que hoy "tramite" ese bono vende algo inexistente.

**Veredicto:** 🟡 solo como herramienta de marketing (charla en asociaciones de comerciantes, cámara
de comercio), no como línea de ingresos.

### 2.8 SaaS propio o reventa marca blanca (GoHighLevel y similares)

**Qué fallaría:** costes en dólares (planes de 97–497 $/mes, la reventa SaaS en el plan alto, más
cargos por SMS/llamadas/ubicación), soporte de un producto completo siendo una persona, RGPD con
servidores fuera de la UE, y competencia con herramientas mejor financiadas.

**Veredicto:** ❌ ahora. Quizá como herramienta **interna** para entregar 2.2, no como producto que
vendas tú.

---

## 3. Resumen

| Modelo | Encaje con lo que ya haces | Recurrente | Riesgo | Veredicto |
|---|---|---|---|---|
| 2.2 Ads + respuesta inmediata + seguimiento | Muy alto | Sí | Medio (integraciones) | ⭐ Prioridad |
| 2.6 Auditoría automatizada (captación) | Muy alto | — | Bajo | ⭐ Prioridad (para vender) |
| 2.3 Ficha + reseñas + IA local | Alto | Sí | Bajo si no se sobrevende | Incluir en 2.2 |
| 2.4 Contenido con IA | Ya existe | Sí | Bajo | Margen, no producto |
| 2.5 Verifactu con gestorías | Medio | No | Medio-alto (fiscal) | Puerta de entrada, con aliado |
| 2.7 Formación IA | Bajo | No | Bajo | Solo marketing |
| 2.1 Recepcionista de voz suelta | Bajo | Sí | Alto | No, salvo como pieza de 2.2 |
| 2.8 SaaS / marca blanca | Bajo | Sí | Alto | No, ahora |

---

## 4. Plan propuesto (90 días) y criterios para abandonarlo

1. **Elegir un único nicho** de Granada donde una cita perdida cueste dinero y no haya datos de salud
   de por medio (p. ej., talleres, reformas, academias, estética). Decisión tuya: depende de qué
   clientes tienes ya en la cartera de energía.
2. **Montar el sistema 2.2 una vez**, con una pila fija, y el aviso de IA del AI Act incluido.
3. **Piloto con 3 clientes** de tu cartera actual, a precio reducido a cambio de datos y testimonio.
4. **Medir**: tiempo de respuesta, % de leads contactados, citas, horas de mantenimiento al mes por
   cliente.
5. **Construir la auditoría automatizada (2.6)** con lo aprendido y salir a vender.

**Abandonar o replantear si:** a los 90 días el mantenimiento supera unas pocas horas al mes por
cliente, o los pilotos no muestran más citas que antes. Con esos datos se fija el precio de verdad.

---

## 5. Lo que no sé y necesitaría para afinar

- Cuántos clientes activos tienes en SOLVEXA Digital y en energía, y de qué sectores.
- Cuántas horas a la semana puedes dedicar a entregar y mantener.
- Qué herramientas usas ya (CRM, agenda, WhatsApp Business, Make).
- Tu tasa actual de cierre tras la auditoría gratuita.

Sin esto, cualquier cifra de ingresos que te diera sería inventada.

---

## Fuentes

- Agentes IA y precios en España: [Javadex](https://www.javadex.es/blog/agentes-ia-atencion-cliente-pymes-espana-precios-2026), [Inter Linked](https://interlinkedai.es/precio-agente-ia-empresa/), [BECAI](https://becai.eu/precios-agencia-ia/), [Automatizator](https://automatizator.es/ia-para-empresas/agentes-ia/agentes-ia-precio/), [Anunzi](https://anunzi.net/blog/precios-agentes-virtuales/), [Laudem Media](https://www.laudemmedia.com/mejores-agencias-automatizacion-ia-espana/)
- Recepcionistas de voz IA en España: [Clinicbot](https://clinicbot.es/cuanto-cuesta-recepcionista-con-ia/), [Telvia](https://telvia.pro/blog/mejores-recepcionistas-virtuales-ia-espana/), [mejorsoftware.org](https://mejorsoftware.org/centralita-virtual-ia-clinicas/), [Agentiaia](https://agentiaia.com/), [Rubitec](https://rubitec.co/insights/recepcionista-virtual-ia-vs-recepcionista)
- Modelo de agencia de voz (EE. UU., fuentes de vendedores): [Trillet](https://trillet.ai/blogs/building-sustainable-ai-voice-agency-2026), [MyVoiceAIConnect](https://www.myvoiceaiconnect.com/blog/how-much-do-ai-receptionist-agencies-make), [Vendasta](https://www.vendasta.com/blog/ai-agents-for-business/), [SchedulingKit](https://schedulingkit.com/statistics/ai-receptionist-statistics)
- Kit Digital y Bono IA: [Alquest](https://alquest.es/es/guias/kit-digital-kit-consulting-ia-2026/), [Aivy](https://aivy.es/guias/kit-digital-kit-consulting-ia-pymes/), [Índole](https://www.indole.es/bono-inteligencia-artificial/), [Hiberus Booster](https://www.hiberusbooster.com/guias/plan-ia360-bono-ia-empresas/)
- AI Act art. 50: [cumpleconia.es](https://cumpleconia.es/blog/digital-omnibus-ai-act-pymes), [Evicron](https://www.evicron.com/blog/transparencia-ia-agosto-2026/), [SIXE](https://sixe.eu/news/ai-act-august-2026-what-actually-applies)
- Verifactu: [Infoautónomos](https://www.infoautonomos.com/blog/verifactu-cuando-es-obligatorio-a-quien-afecta/), [Genbeta](https://www.genbeta.com/actualidad/gobierno-retrasa-pesadilla-para-empresas-autonomos-verifactu-no-sera-obligatorio-2027/amp)
- GEO: [RevvGrowth](https://www.revvgrowth.com/geo/geo-agency-pricing), [Icecube Digital](https://www.icecubedigital.com/blog/generative-engine-optimization-cost-2026/)
- Modo IA de Google en España: [Genbeta](https://www.genbeta.com/buscadores/nuevo-modo-ia-google-llega-a-espana-mayor-cambio-historia-buscador-llega-hoy)
- GoHighLevel: [SchedulingKit](https://schedulingkit.com/es/pricing-guides/gohighlevel-pricing), [SuiteDash](https://suitedash.com/gohighlevel-alternative-white-label.md)

Verificar en fuentes oficiales (BOE, Red.es, AEAT, DOUE) antes de tomar decisiones legales o fiscales.
