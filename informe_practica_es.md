# Evaluación humana de respuestas en español

Práctica para portafolio · 26 de septiembre de 2026

## Objetivo y método

Practicar la evaluación de exactitud, claridad y seguimiento de instrucciones usando Label Studio en Windows. Se anotaron 20 pares de pregunta y respuesta sintéticos, preparados con asistencia de IA, con una justificación escrita por tarea. Los temas incluyen cálculo, traducción, resumen, extracción, consejos y afirmaciones sin evidencia.

El participante realizó las anotaciones y recibió orientación y revisión de un asistente de IA. Algunas justificaciones se sustituyeron por redacciones sugeridas. Por ello, se presenta como práctica guiada, no como prueba independiente ni como trabajo realizado para Rise Data Labs.

## Integridad del archivo

Fuente: evaluaciones_es_final.json (exportación de Label Studio del 26 de septiembre de 2026 a las 13:14).

La exportación contiene 20 tareas, cada una con una anotación no cancelada, tres etiquetas y una justificación no vacía. Se verificaron las correcciones de los casos 2, 5, 9 y 11. El archivo original no se modificó.

## Distribución de etiquetas finales

| Dimensión | Etiqueta | Casos | Porcentaje |
|---|---|---:|---:|
| Exactitud | Correcta | 12 | 60 % |
| Exactitud | Parcialmente correcta | 3 | 15 % |
| Exactitud | Incorrecta | 3 | 15 % |
| Exactitud | No verificable | 2 | 10 % |
| Claridad | Clara | 19 | 95 % |
| Claridad | Algo confusa | 0 | 0 % |
| Claridad | Confusa | 1 | 5 % |
| Instrucciones | Cumple | 16 | 80 % |
| Instrucciones | Cumple parcialmente | 4 | 20 % |
| Instrucciones | No cumple | 0 | 0 % |

Estos porcentajes describen los ejemplos elegidos y sus etiquetas finales; no miden precisión del evaluador ni rendimiento de un modelo real.

## Revisión de la última ronda

Las etiquetas de los ocho casos finales son consistentes con la guía acordada.

| ID | Caso | Evidencia principal |
|---|---|---|
| 13 | Cambio de una compra | 50 − (3 × 12) = 14; la respuesta dice 24. |
| 14 | Código de pedido | Extrae AB-204 sin texto adicional. |
| 15 | Resumen de talleres | Conserva la cancelación, pero cambia 10:00 por 11:00. |
| 16 | Traducción | Invierte «pospuesta, no cancelada». |
| 17 | Videollamada | Ofrece tres recomendaciones en lugar de dos. |
| 18 | Batería | No hay acceso al dispositivo ni evidencia del 83 %. |
| 19 | Orden numérico | 3 < 11 < 18 y no añade explicaciones. |
| 20 | Fundación de empresa | Distingue la apertura de una segunda tienda del año de fundación. |

La exportación final incorpora las correcciones editoriales de los casos 16 y 19. Las etiquetas se mantienen.

## Aprendizajes observados

- Separar claridad de veracidad: una respuesta comprensible puede contener errores.
- Verificar cálculos y contrastar resúmenes con el texto original.
- Distinguir información falsa de información no verificable. Tras revisar el caso de los pedidos, se aplicó la etiqueta «No verificable» al caso de la batería.
- Reconocer que admitir la ausencia de un dato en un texto puede ser correcto.
- Aplicar restricciones de cantidad y formato sin confundirlas con exactitud.

## Limitaciones y presentación

Muestra pequeña, seleccionada para enseñanza y con errores introducidos deliberadamente. Un participante humano y revisión asistida por IA; no hubo segundo anotador humano independiente, referencia externa validada ni medición de acuerdo entre anotadores. La guía evolucionó durante la práctica. No se infiere preparación laboral certificada ni afiliación a una empresa.

Descripción sugerida para el portafolio: «Práctica guiada de evaluación de 20 respuestas sintéticas en español mediante Label Studio. Apliqué una rúbrica de exactitud, claridad y seguimiento de instrucciones, redacté justificaciones y revisé la consistencia de las anotaciones con asistencia de IA».


