---
title: Ejercicios IA
---


<style>
/* Only affects paragraph text */
.page-content p {
  text-align: justify;
}
</style>

<style>
/* Hide the top-right navigation bar */
.site-nav {
  display: none;
}
</style>

# Actividad A: detecta el sesgo!

**Objetivo**: Comprender cómo los modelos de IA pueden reflejar o amplificar sesgos en los datos médicos.

Considere las siguientes herramientas de IA entrenadas con datos sesgados:
- Un modelo de detección de cáncer de piel entrenado mayoritariamente con imágenes de piel clara.
- Un modelo de riesgo cardiovascular entrenado en su mayoría con datos de pacientes hombres.
- Un chatbot que da peores resultados con pacientes que no dominan el español.

Responda:
1. ¿Qué tipo de sesgo está presente en cada caso? (¿de datos, de etiquetas, poblacional? ...)
2. ¿Cómo podría esto afectar la atención al paciente?
3. ¿Qué se podría hacer para reducir o corregir ese sesgo?

# Actividad B: buscar con inteligencia

**Objetivo**: Evidenciar la diferencia entre búsqueda exacta, aproximada y semántica en registros clínicos.

Considere la siguiente tabla con registros clínicos:

| Nº | Registro clínico                                         |
| -- | -------------------------------------------------------- |
| 1  | Paciente con antecedentes de infarto agudo de miocardio. |
| 2  | Sufre de infarto de miocardio.                           |
| 3  | Antecedentes de ataque al corazón.                       |
| 4  | Dolor torácico reportado; descartar angina.              |
| 5  | No hay evidencia de isquemia.                            |
| 6  | Historial de enfermedad cardíaca.                        |
| 7  | Consulta por presión en el pecho.                        |
| 8  | Infarto documentado hace 3 años.                         |
| 9  | Paciente refiere episodio de dolor retroesternal.        |
| 10 | Angina estable bajo tratamiento.                         |

Realice las siguientes tareas de búsqueda:
1. Realice una **búsqueda exacta** por "infarto de miocardio". ¿Cuántas coincidencias existen?
2. Luego busque "ataque al corazón". ¿Qué diferencias existen respecto a los resultados de la búsqueda anterior?
3. Si tuvieras un **buscador semántico**, ¿qué registros deberían recuperarse? Compare con los resultados obtenidos en las dos partes anteriores.
4. ¿Qué limitaciones tuvo la búsqueda exacta?
5. ¿Cuándo es especialmente útil la búsqueda semántica en medicina?