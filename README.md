Descripción de la base de datos
---
La base de datos corresponde al Programa de formación artística de la Casa de la Cultura del Municipio de Chía (2024). Contiene registros de estudiantes inscritos en diferentes cursos de formación, junto con variables sociodemográficas y académicas que permiten caracterizar la población.

Transformaciones realizadas en Power BI
---
Columna AÑO
Convertida a texto para manipularla.
Se eliminó la coma en el valor 2,024 → quedando como 2024.
Luego se cambió a número entero.

Columna EDAD
Establecida como número entero para análisis cuantitativo.

Columna GÉNERO
Valores reemplazados:

"Mujer" → FEMENINO
"Hombre" → MASCULINO
Cualquier otro valor → OTRO

Todas las columnas
Convertidas a MAYÚSCULAS.

Se aplicó limpieza (eliminación de espacios innecesarios, valores inconsistentes).

---
📊 Gráficos construidos
**Gráfico 1: Estudiantes por ZONA DE RESIDENCIA y CURSO**

Visual: Gráfico de columnas agrupadas.
Eje X → CURSO
Valores → Recuento de filas (número de estudiantes)
Leyenda → ZONA DE RESIDENCIA (URBANA / RURAL)
Resultado esperado: Permite observar qué cursos concentran más estudiantes de zona urbana o rural, y si hay diferencias significativas entre ambos.

**Gráfico 2: Estudiantes por GÉNERO y ZONA DE RESIDENCIA**

Visual: Gráfico de columnas apiladas.
Eje X → GÉNERO (FEMENINO, MASCULINO, OTRO)
Valores → Recuento de filas (número de estudiantes)
Leyenda → ZONA DE RESIDENCIA (URBANA / RURAL)
Resultado esperado: Muestra dentro de cada género cómo se distribuyen los estudiantes entre zonas urbanas y rurales, permitiendo comparar diferencias en residencia por género.
