---
title: Sitio Data Evolution — Fase 1 / Site v1.0
category: marketing
owner: Marketing / Estrategia
status: draft
last_updated: 2026-09-16
source: contexto_plan_fase_1_sitio_data_evolution.md
release: Site v1.0
---

> **Nota de alineación con la base de conocimiento (2026-09-16):** este documento conserva el contexto consolidado de Fase 1. La fuente canónica de cada solución/servicio vive en `02_portfolio/`, `03_products/` o `01_company/`. Las decisiones abiertas del portafolio no deben bloquear Site v1.0. La ruta futura de Commissioning mostrada en la sección de Fase 2 bajo Consultoría se considera **provisional/histórica** y no una URL aprobada; la arquitectura canónica actual clasifica Commissioning dentro de Implementación / Puesta en marcha. Cursos y Certificaciones permanecen como hubs independientes.

# Contexto consolidado — Fase 1 del nuevo sitio de Data Evolution

## Proyecto
**Nuevo sitio web Data Evolution 2026**

## Release
**Fase 1 — Site v1.0**

---

# 1. Qué es la Fase 1

La **Fase 1** está definida como el primer release completo del nuevo sitio de Data Evolution.

No debe entenderse únicamente como un conjunto de páginas con prioridad P1, sino como un **release fundacional** que establece la arquitectura, contenido, SEO, GEO, conversión, localización bilingüe, automatización, routing y medición sobre los que evolucionará el sitio entre 2026 y 2028.

El objetivo de `Site v1.0` es construir los hubs, rutas comerciales y capacidades fundamentales sin intentar publicar desde el inicio todas las subpáginas del sitemap estratégico.

El sitio debe funcionar como un **centro de decisión técnica y comercial**, no como un brochure corporativo.

Cada página debe ayudar al usuario a:

- Entender un problema.
- Identificar una solución.
- Comparar caminos posibles.
- Validar un criterio técnico.
- Reducir incertidumbre.
- Solicitar una acción comercial clara.

---

# 2. Principio metodológico

La metodología oficial del proyecto queda organizada bajo la siguiente secuencia:

```text
Mercado
↓
Buyer Persona
↓
JTBD
↓
Problema
↓
Outcome esperado
↓
Entidad GEO
↓
Keyword
↓
Intención
↓
URL
↓
Variante lingüística
↓
Colateral / recurso
↓
CTA
↓
Canal de conversión
↓
Conversión
↓
Routing
↓
Medición
```

Esta secuencia debe respetarse en la definición de cualquier página, brief, CTA, formulario, flujo de WhatsApp/Wati, colateral o nueva URL.

La arquitectura debe construirse desde los problemas y decisiones del usuario, no desde el organigrama interno de Data Evolution.

---

# 3. Alcance oficial de Fase 1

La Fase 1 publica:

- **16 entidades de página**
- **32 variantes URL**
- **16 ES**
- **16 EN**

## 3.1 Páginas de Fase 1

| Page ID | Página | URL ES | URL EN |
|---|---|---|---|
| PAGE-01 | Home | `/` | `/en/` |
| PAGE-02 | Soluciones | `/soluciones/` | `/en/solutions/` |
| PAGE-03 | Consultoría para Data Centers | `/soluciones/consultoria-data-centers/` | `/en/solutions/data-center-consulting/` |
| PAGE-04 | Implementación de Centros de Datos | `/soluciones/centros-de-datos/` | `/en/solutions/data-centers/` |
| PAGE-05 | Liquid Cooling para Data Centers | `/soluciones/centros-de-datos/liquid-cooling/` | `/en/solutions/data-centers/liquid-cooling/` |
| PAGE-06 | Soluciones Digitales | `/soluciones/digitales/` | `/en/solutions/digital/` |
| PAGE-07 | Gemelo Digital Data Center | `/soluciones/digitales/gemelo-digital-data-center/` | `/en/solutions/digital/data-center-digital-twin/` |
| PAGE-08 | Industrias | `/industrias/` | `/en/industries/` |
| PAGE-09 | Knowledge Hub | `/knowledge-hub/` | `/en/knowledge-hub/` |
| PAGE-10 | Cursos | `/cursos/` | `/en/courses/` |
| PAGE-11 | Certificaciones | `/certificaciones/` | `/en/certifications/` |
| PAGE-12 | Alianzas | `/alianzas/` | `/en/technology-partners/` |
| PAGE-13 | Nosotros | `/nosotros/` | `/en/about/` |
| PAGE-14 | Contacto | `/contacto/` | `/en/contact/` |
| PAGE-15 | Política de privacidad | `/politica-de-privacidad/` | `/en/privacy-policy/` |
| PAGE-16 | Términos y condiciones | `/terminos-y-condiciones/` | `/en/terms-and-conditions/` |

---

# 4. Reglas estructurales ya cerradas

## 4.1 Soluciones como hub principal

`/soluciones/` se mantiene como el hub comercial principal del sitio.

Debe orientar al usuario según problema, necesidad o etapa del ciclo de vida de la infraestructura crítica.

## 4.2 Namespace oficial de Soluciones Digitales

El namespace oficial del cluster digital es:

```text
/soluciones/digitales/
```

No debe utilizarse:

```text
/soluciones/soluciones-digitales/
```

La ruta oficial del Gemelo Digital es:

```text
/soluciones/digitales/gemelo-digital-data-center/
```

## 4.3 Cursos y Certificaciones permanecen separados

Las páginas:

```text
/cursos/
/certificaciones/
```

son hubs independientes.

No deben fusionarse en una sola URL.

---

# 5. Arquitectura bilingüe

La versión en inglés forma parte de la Fase 1.

```text
Español = raíz
Inglés  = /en/
```

Cada entidad conserva un solo `Page ID`, pero tiene variantes lingüísticas independientes.

Ejemplo:

```text
PAGE-06
├── ES v1.0
└── EN v1.0
```

La localización debe controlar por variante:

- URL.
- H1.
- Keyword principal y secundarias.
- Meta title.
- Meta description.
- UX Writing.
- CTAs.
- Colaterales.
- Mensajes de formulario.
- Mensajes conversacionales.
- Internal linking.
- Canonical.
- `hreflang`.

Regla técnica:

```text
es-MX → URL ES
en    → URL EN
x-default → variante por defecto definida
```

El idioma es un atributo.

No se debe crear una taxonomía comercial distinta para inglés.

---

# 6. Filosofía de contenido

La experiencia del sitio debe construirse bajo un enfoque **Content First**.

Contenido y flujo deben diseñarse juntos.

Los briefs no deben quedarse en instrucciones como:

> “Aquí explicar beneficios.”

Deben bajar contenido publicable y especificar la arquitectura real de la página:

- H1.
- H2.
- Párrafos.
- Cards.
- Bullets.
- FAQs.
- CTAs.
- Microcopy.
- Anclas.
- URLs destino.
- Internal linking.
- Colaterales.
- Formularios.
- Wati.
- Conversión.
- Medición.

Cada página debe partir de una historia clara del usuario:

```text
Situación inicial
↓
Problema
↓
Decisión que necesita tomar
↓
Información necesaria
↓
Ruta de solución
↓
Acción siguiente
```

---

# 7. Conversión en Fase 1

La conversión forma parte del diseño del sitio desde Fase 1.

No debe añadirse al final.

El journey general es:

```text
Problema
↓
Intención
↓
CTA
↓
Canal
↓
Formulario / WhatsApp
↓
Conversión
↓
Routing
↓
CRM
↓
Seguimiento
↓
Analytics
```

---

# 8. Sistema de formularios

Fase 1 utiliza seis arquetipos principales.

| Form ID | Intención | Función |
|---|---|---|
| F01 | Informativa | Acceso a recurso |
| F02 | Técnica | Assessment / workshop / diagnóstico |
| F03 | Comercial | Hablar con especialista |
| F04 | Transaccional | Proyecto / cotización / propuesta |
| F05 | Demo | Evaluación de plataforma / PoC |
| F06 | Formación | Cursos / certificaciones |

`F07 — Business Case / ROI` queda documentado para fases posteriores y no bloquea `Site v1.0`.

No se debe crear un formulario diferente por solución.

Los mismos arquetipos deben reutilizarse y recibir contexto mediante campos ocultos.

---

# 9. Mapeo de formularios por página

| Página | Formulario principal | Secundarios |
|---|---|---|
| Home | F03 | F02 / F05 |
| Soluciones | F03 | F02 |
| Consultoría | F02 | F04 |
| Centros de Datos | F04 | F02 |
| Liquid Cooling | F02 | F01 |
| Soluciones Digitales | F02 | F01 / F05 |
| Gemelo Digital | F02 | F01 |
| Industrias | F03 | F02 |
| Knowledge Hub | No aplica como formulario principal | F03 solo cuando exista intención comercial |
| Cursos | F06 | — |
| Certificaciones | F06 | — |
| Alianzas | F03 | — |
| Nosotros | F03 | F01 opcional |
| Contacto | Router | F02 / F03 / F04 / F05 / F06 |
| Política de privacidad | No aplica | — |
| Términos y condiciones | No aplica | — |

---

# 10. Contexto heredado de formularios

Todos los formularios deben recibir automáticamente:

```text
form_id
form_intent
form_name
cta_text
source_url
source_page
page_type
solution
subsolution
industry
language
referrer
utm_source
utm_medium
utm_campaign
utm_content
utm_term
campaign_id
```

Cuando aplique:

```text
event
webinar
partner
resource
course
product
```

Principio:

> El usuario no debe responder información que el sitio ya conoce.

---

# 11. WhatsApp / Wati

WhatsApp es una ruta de conversión paralela a formularios.

No debe funcionar únicamente como botón genérico.

El modelo es:

```text
Página
↓
Contexto + intención
↓
CTA
↓
Canal
├── Formulario
└── WhatsApp / Wati
      ↓
Captura y clasificación
↓
Zoho CRM
↓
Owner
↓
Marketing Automation
↓
Analytics
```

## 11.1 Widget global

El widget global de WhatsApp se implementa mediante Google Tag Manager.

Su función es atender sesiones donde todavía no existe suficiente contexto.

```text
GTM
↓
Widget WhatsApp
↓
Wati
↓
Menú principal / diagnóstico guiado
```

## 11.2 CTAs contextuales

Cuando una página ya conoce la solución, industria, curso, recurso o necesidad del usuario, el CTA debe pasar ese contexto directamente a Wati.

```text
Página específica
↓
CTA contextual
↓
WhatsApp
↓
Wati Flow
↓
Preguntas únicamente faltantes
```

Contextos principales:

### Global

```text
source
language
utm_source
utm_medium
utm_campaign
utm_content
utm_term
campaign_id
```

### Página

```text
page_id
page_origin
page_type
language_variant
```

### Negocio

```text
business_line
solution_interest
subsolution
industry
partner
course
resource
```

### Intención

```text
cta_id
cta_text
intent
content_interest
expected_conversion
wati_flow_id
```

---

# 12. Colaterales de Fase 1

Los colaterales deben ayudar al usuario a avanzar una decisión.

No deben convertirse en una biblioteca de PDFs bloqueados.

El modelo es:

```text
JTBD
↓
Pregunta / incertidumbre
↓
Colateral
↓
Valor entregado
↓
CTA
↓
Siguiente nivel de intención
```

## 12.1 Plan de colaterales

| Página | Colateral / recurso | Tipo |
|---|---|---|
| Home | Mapa del portafolio por ciclo de vida | Orientador / one-pager |
| Soluciones | Guía rápida: encuentra la solución correcta | Guía / orientador |
| Consultoría | Checklist: ¿Tu data center está preparado para crecer? | Checklist |
| Centros de Datos | Checklist AI-ready data center | Checklist técnico |
| Liquid Cooling | Checklist: ¿Tu data center necesita Liquid Cooling? | Checklist técnico |
| Soluciones Digitales | Assessment: nivel de inteligencia operativa | Assessment |
| Soluciones Digitales | Checklist: ¿tu operación está lista para IA? | Checklist |
| Soluciones Digitales | Guía DCIM vs BMS vs Gemelo Digital | Comparativo |
| Soluciones Digitales | Checklist para reducir alarm fatigue | Checklist operativo |
| Gemelo Digital | Comparativa: DCIM complejo vs gemelo accionable | Comparativo |
| Industrias | Matriz de retos de infraestructura crítica por industria | Orientador |
| Knowledge Hub | No aplica como colateral obligatorio | Hub editorial |
| Cursos | Calendario de cursos Data Evolution | Calendario |
| Certificaciones | Guía de certificaciones data center | Guía comparativa |
| Alianzas | Ficha / mapa de alianzas tecnológicas | One-pager / mapa |
| Nosotros | Portafolio de soluciones 2026 | Portafolio |
| Contacto | No aplica como colateral obligatorio | Router |
| Política de privacidad | No aplica | Legal |
| Términos y condiciones | No aplica | Legal |

## 12.2 Regla gated vs ungated

```text
Contenido necesario para entender la página
→ Visible sin formulario

Recurso con valor autónomo descargable
→ Puede utilizar F01

Evaluación que requiere información del usuario
→ F02 / F05 / F06 según intención
```

---

# 13. Knowledge Hub en Fase 1

`/knowledge-hub/` funciona como un hub editorial.

No requiere crear una URL propia para cada contenido desde Fase 1.

Arquitectura:

```text
/knowledge-hub/
│
├── The Data Revolution
│   ├── Inside Evolution
│   │   ├── TheDataRevolution.ai
│   │   └── Suscripción LinkedIn
│   │
│   └── The Data Revolution Podcast
│       ├── TheDataRevolution.ai
│       ├── YouTube
│       └── Spotify
│
├── Infraestructura 2030
│   └── Foro Infraestructura 2030
│
└── Participaciones y foros de industria
    └── DCD Talks LATAM
        ├── Liquid Cooling
        └── Del watt al impacto real
```

Estos elementos pueden funcionar como módulos dentro del hub.

La creación posterior de páginas independientes debe validarse mediante:

- Keyword Universe.
- Demanda.
- Autoridad.
- Volumen de contenido.
- Intención.
- Valor dentro del GEO Entity Graph.

## 13.1 Medición de Knowledge Hub

Las conversiones principales de Fase 1 son de engagement:

```text
content_click
newsletter_subscribe_click
podcast_platform_click
editorial_project_click
external_talk_click
```

Formularios y Wati únicamente deben intervenir cuando exista intención comercial explícita.

---

# 14. Qué queda fuera de Fase 1

Fase 1 no publica todas las URLs del sitemap estratégico 2026–2028.

Entre las páginas candidatas a Fase 2 se encuentran:

```text
/soluciones/consultoria-data-centers/commissioning/
/soluciones/consultoria-data-centers/gap-analysis/
/soluciones/consultoria-data-centers/cfd/

/soluciones/centros-de-datos/enfriamiento-precision/
/soluciones/centros-de-datos/sistema-electrico/
/soluciones/centros-de-datos/cableado-estructurado/
/soluciones/centros-de-datos/ai-factories/

/soluciones/digitales/coolbit-ai/
/soluciones/digitales/monitoreo-infraestructura-critica/
/soluciones/digitales/mantenimiento-predictivo/
/soluciones/digitales/rf-code/
/soluciones/digitales/mango-os/
/soluciones/digitales/ekkosense/
```

Por lo tanto:

**CoolBit AI no tiene URL propia en `Site v1.0`.**

Puede aparecer dentro de Soluciones Digitales y otras páginas relacionadas, pero su landing propia se contempla actualmente como expansión posterior.

Lo mismo aplica para Commissioning y otras subsoluciones.

---

# 15. Fase 2 — Site v2.0

Fase 2 tiene como objetivo profundizar los hubs creados en Fase 1.

Objetivos:

- Capturar búsquedas no branded más específicas.
- Desarrollar JTBD más concretos.
- Crear páginas con intención técnica o comercial propia.
- Ampliar entidades dentro del GEO Entity Graph.
- Incrementar rutas de conversión.
- Mantener el modelo de formularios, Wati, CRM y Analytics.

---

# 16. Fase 3 — Autoridad temática

Fase 3 fortalece la relación:

```text
Problema
↔
Industria
↔
Solución
↔
Conocimiento
↔
Caso de éxito
↔
Entidad
```

Aquí pueden comenzar a aparecer:

- Páginas individuales por industria.
- Clusters SEO del Knowledge Hub.
- Casos de éxito.
- Contenido de profundidad temática.
- Evidencia especializada por solución e industria.

---

# 17. Fase 4 — Conversión avanzada

Activos potenciales:

- Calculadoras ROI.
- Assessments interactivos.
- Comparativas técnicas.
- Benchmarks LATAM.
- Glosarios.
- Casos por industria.
- Webinars.
- Whitepapers.
- Landing pages de eventos.
- Playbooks.
- Configuradores.
- Diagnósticos digitales.

---

# 18. Definition of Done — Fase 1

Una página no se considera terminada únicamente porque contenido y diseño estén aprobados.

Debe cumplir:

- [ ] Page ID asignado.
- [ ] URL ES validada.
- [ ] URL EN validada.
- [ ] Keyword Universe validado.
- [ ] GEO Entity Graph validado.
- [ ] Content Brief aprobado.
- [ ] Contenido ES aprobado.
- [ ] Contenido EN localizado y aprobado.
- [ ] Metadata ES/EN validada.
- [ ] Canonical / hreflang validados.
- [ ] Internal linking ES/EN validado.
- [ ] Colateral producido o marcado `No aplica`.
- [ ] CTA principal definido.
- [ ] CTA secundario definido.
- [ ] Intención de cada CTA definida.
- [ ] Canal definido.
- [ ] Form ID asignado cuando aplique.
- [ ] Wati Flow ID asignado cuando aplique.
- [ ] Contexto heredado definido.
- [ ] Widget global validado vía GTM.
- [ ] Preguntas redundantes de Wati eliminadas.
- [ ] Routing definido.
- [ ] Owner definido.
- [ ] CRM Create / Update definido.
- [ ] Consentimiento y privacidad validados.
- [ ] Estado de confirmación definido.
- [ ] Marketing Automation definida cuando aplique.
- [ ] Analytics implementado.
- [ ] QA desktop completado.
- [ ] QA mobile completado.
- [ ] Journey completo probado hasta CRM.
- [ ] Versión registrada.
- [ ] Estado productivo registrado.

El cierre de esta etapa genera el:

```text
Baseline Site v1.0
```

---

# 19. Unidad operativa de Fase 1

Cada página debe poder representarse dentro de esta cadena:

```text
PAGE ID
↓
LANGUAGE
↓
URL
↓
CONTENT VERSION
↓
COLLATERAL ID
↓
CTA ID
↓
INTENT
↓
CHANNEL
├── FORM ID
└── WATI FLOW ID
↓
CONVERSION
↓
CRM CLASSIFICATION
↓
OWNER
↓
MARKETING AUTOMATION
↓
ANALYTICS
```

Este modelo conecta arquitectura, contenido, conversión y operación.

---

# 20. Implicación para los briefs

Los briefs anteriores identificados como `alineado` fueron construidos contra una versión previa de la metodología.

Por lo tanto, deben actualizarse a metodología v4.

Cada brief final de Fase 1 debe incluir:

1. Información general.
2. Fila del Keyword Universe.
3. Buyer.
4. JTBD.
5. Problema.
6. Outcome.
7. Entidad GEO.
8. Keywords.
9. Intención.
10. Arquitectura de página.
11. Contenido final publicable.
12. H1 / H2 / párrafos.
13. CTAs.
14. Anclas.
15. URLs destino.
16. Conversión multicanal.
17. Form ID.
18. Wati Flow ID.
19. Contexto heredado.
20. Routing.
21. Owner.
22. Colateral.
23. Variante ES.
24. Variante EN.
25. Metadata.
26. Canonical.
27. `hreflang`.
28. Internal linking.
29. Schema.
30. Analytics.
31. Criterios de aprobación.

---

# 21. Resumen ejecutivo

La Fase 1 del nuevo sitio de Data Evolution no consiste únicamente en publicar páginas.

Consiste en construir el primer sistema completo del producto digital:

```text
Arquitectura
+
Contenido
+
SEO
+
GEO
+
UX Writing
+
ES / EN
+
Colaterales
+
CTAs
+
Formularios
+
WhatsApp / Wati
+
CRM
+
Routing
+
Marketing Automation
+
Analytics
+
QA
=
Site v1.0
```

El resultado debe ser una base suficientemente sólida para ampliar el sitio durante las siguientes fases sin romper la arquitectura, la taxonomía, el modelo de conversión ni la estructura semántica.
