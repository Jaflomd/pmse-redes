# Auditoría de distribución AMDP / DSM-5 → nodos pMSE (2026-06-26)

> Revisión crítica de las asignaciones producidas por los subagentes de mapeo.
> Método: detección programática de constructos partidos (mismo fenómeno en nodos
> distintos entre AMDP y DSM) + juicio clínico sobre cada caso. Todos los cambios abajo
> se APLICARON al reporte y a `CROSSWALK-dsm5-sintomas-por-nodo.md`.

## 🔴 Hallazgo mayor — Mentalización (R9) sobrecargada de Antagonismo

**Síntoma de la auditoría:** Mentalización recibía 17 síntomas DSM pero 0 ítems AMDP. La asimetría delató el error: el agente confundió *Teoría de la Mente* con *uso antisocial de la ToM*.

**Corrección (Mentalización 17 → 3):**
- **11 → Dominancia (R3)** [= PID-5 Antagonism]: mentir (ZMQRF_441, 442), inventar historias (525), trampa (526), usar a otros (527), distorsionar verdad (528), manipular (533), halagos instrumentales (534), engañar (535), aprovecharse (536), promesas falsas (542).
- **3 → Amenaza (R4)** [suspicacia/resentimiento]: creencias negativas sobre otros (374), vigilancia ante engaño (508), sentirse tratado injustamente (509).
- **Quedan 3 en Mentalización** [callousness real / déficit de empatía]: indiferencia ante daño (167), ante sentimientos ajenos (523), ante problemas de otros (524).

## 🟡 Inconsistencias AMDP vs DSM resueltas

| Constructo | Antes | Ahora | Síntoma |
|---|---|---|---|
| Despersonalización | DSM en Experiencia vivida | **Experiencia del yo (R9)** (alinea con AMDP 054) | ZMQRF_351 |
| Imagen corporal | DSM en Contenido (R7) | **Autoevaluación (R9)** (alinea con AMDP ZP08) | ZMQRF_405 |
| Autoestima ligada al peso | DSM en Contenido (R7) | **Autoevaluación (R9)** | ZMQRF_553 |
| Suspicacia no-delirante | DSM en Contenido (R7) | **Amenaza (R4)** | ZMQRF_510 |
| Obsesión intrusiva | DSM en Contenido (R7) | **Monitoreo del error (R8)** (unifica con AMDP 030) | ZMQRF_92 |

## 🟢 Menores

| Cambio | Razón | Síntoma |
|---|---|---|
| Impulsividad → Approach-evitación (R10) | alinear con AMDP ZP07 | ZMQRF_194 |
| Distanciamiento, preferir soledad, rechazo de romance → Afiliación (R3) | son desapego (Detachment), no evitación ansiosa | ZMQRF_511, 506, 637 |

## Asimetría dejada a propósito (NO es error)
- **Pensamiento enlentecido → Velocidad psicomotriz (R6)** vs **acelerado → Experiencia del pensamiento (R9)**: justificado por fuente de dato — el enlentecido es observable (bradipsiquia motora), el acelerado es subjetivo (taquipsiquia vivida).
- **Síntomas de conversión → Integración sensorial (R7)**: disociación sensoriomotora; defendible.

## Impacto en conteos DSM-5
Mentalización 17→3 · Dominancia 6→17 · Amenaza 36→40 · Contenido 17→13 · Autoevaluación 8→10 · Monitoreo del error 0→1 · Approach-evitación 20→18 · Afiliación 11→14 · Riesgo 21→20 · Experiencia del yo 2→3 · Experiencia vivida 3→2. **Total 313 intacto.**

## Control de calidad positivo (sin cambios)
Delirios → Contenido · alucinaciones → Integración sensorial · suicidio/agresión → Riesgo · sueño/apetito/libido → R2 · motor → R6 · somático → Interocepción/Nocicepción: consistentes en AMDP y DSM.
