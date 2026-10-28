# FinanSeeds 🌱

Pequeñas semillas, grandes decisiones.

Un "Duolingo de finanzas": eliges tu nivel, completas lecciones cortas, respondes preguntas y superas retos. Cada respuesta correcta te da semillas.

**Pruébalo:** https://oposity19.github.io/finanseeds/

## Cómo se ganan las semillas

La idea es premiar entender el tema, no solo entrar a la plataforma.

| Acción | Semillas |
|---|---|
| Entrar a la plataforma (1 vez al día) | +1 |
| Respuesta correcta al primer intento | +5 |
| Respuesta correcta al segundo intento | +2 |
| Completar una lección | +10 |
| Lección perfecta (sin errores) | +10 |
| Respuesta correcta en un reto | +8 |
| Superar un reto | +30 |
| Repasar lecciones o retos ya superados | +1 a +3 |

Si sales a mitad de una lección pierdes las semillas de esa lección, y repetir lo ya completado da muy pocas, para que no se puedan acumular sin aprender.

## Niveles

- 🌱 **Básico:** ahorro, necesidades vs. deseos, metas de ahorro.
- 🌿 **Intermedio:** presupuesto 50/30/20, bancos y cuentas, tarjetas de crédito e intereses.
- 🌳 **Avanzado:** interés compuesto e inflación, bolsa de valores, riesgo y plazo.

## Cómo editar

Todo está en `index.html`, sin dependencias:

- Preguntas y lecciones: el arreglo `LEVELS`.
- Valores de las semillas: el objeto `REWARD`.

El progreso se guarda en el navegador de cada persona (`localStorage`).
