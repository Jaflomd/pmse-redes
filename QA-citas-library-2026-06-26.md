# QA de citas `[library]` — verificación de DOIs/PMIDs (2026-06-26)

> Verificación adversarial de los 18 identificadores heredados de dossiers, por panel de 3
> verificadores contra la base de artículos real (PubMed/PMC). **Resultado global: 0 citas
> fabricadas — los 18 resuelven a artículos REALES.** Las discrepancias son de metadata
> (autoría/año/framing), no de existencia.

## ✅ Confirmadas limpias (8)
| Cita | ID | Estado |
|---|---|---|
| Maness 2022 (Brain Res Bull) | doi:10.1016/j.brainresbull.2022.07.014 | ✓ todo coincide |
| Meyer 2024 (PNAS) | doi:10.1073/pnas.2214756121 | ✓ |
| Michelini 2021 (Clin Psychol Rev) | PMC8165014 | ✓ |
| Duque 2024 (J Psychosom Res) | PMC11006573 | ✓ |
| Liang 2025 (Psychol Med) | PMC12527541 | ✓ real (PMC alto pero válido, sept 2025) |
| Tsapakis 2023 (CNS Spectr) | PMID 36924179 | ✓ |
| Borbás 2026 (Commun Biol) | PMC12920907 | ✓ real (enero 2026, N=181) |
| Tsui 2025 (Eur Psychiatry) | PMC12816936 | ✓ real (dic 2025, 89 estudios) |

## 🔧 Corregidas (autoría/año)
| Cita | Problema | Corrección aplicada |
|---|---|---|
| Pintos Lobo | año 2023 → **2022** (Neurosci Biobehav Rev) | ✅ |
| Kirkpatrick et al. 2012 | primer autor es **Strauss** (Kirkpatrick = sénior) | ✅ → Strauss et al. 2012 |
| Walther & Heckers (NEJM 2023) | primer autor es **Heckers** | ✅ → Heckers & Walther |
| Berridge & Robinson | faltaba año/revista | ✅ → 2016 (Am Psychol) |

## ⚠️ Notas (no son errores — framing / epub-vs-print)
| Cita | Observación |
|---|---|
| Reimann 2025 (JAMA Psychiatry) | DOI correcto; sustrato real = ACC subgenual **+ amígdala/hipocampo** (no solo amígdala) |
| Baglioni 2016 (Psychol Bull) | real; título = meta-análisis PSG; el framing "factor de riesgo" es interpretación |
| McTeague 2016 (J Psychiatr Res) | es **revisión narrativa**, no estudio fMRI primario — ajustar si el texto implica datos nuevos |
| Goodkind 2015 (JAMA Psychiatry) | N real = **15,892** (el "~16,000" es aproximación válida) |
| Stein 2024 (Biol Psychiatry) | epub 2023 / print 2024; **FTD = formal thought disorder** (correcto en contexto), no dementia |
| Glenn (Depress Anxiety) | epub 2017 / print 2018 — ambos años circulan; no es error |

## Veredicto
**Integridad de citas: sólida.** Ninguna fabricación. Las 4 correcciones aplicadas son de
precisión de autoría/año. Las 6 notas son aclaraciones de framing para la redacción final.
