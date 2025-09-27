# Serie III - Resolución en Excel

Este repositorio contiene la resolución de la **Serie III** del examen de Aseguramiento de la Calidad de Software.

## 📂 Contenido del archivo

El archivo `SerieIII_Tabla_Decisiones.xlsx` incluye **3 hojas**:

### 1. Tabla_Decisiones
Contiene la tabla de decisiones con las 8 reglas (R1–R8) que combinan las condiciones de:
- Productividad (P ≥ 90 o no)
- Encargado (Sí/No)
- Infracción grave (IG ≥ 1 o no)

Y las acciones resultantes:
- A1: Asignar bono de productividad
- A2: Asignar bono de encargado
- A3: Eliminar bonos (prioridad sobre todo)

### 2. Clases_Equivalencia
Incluye las clases de equivalencia y valores límite definidos para las entradas:
- Productividad (P)
- Encargado (E)
- Infracción grave (IG)

Con sus rangos, definiciones y valores límite obligatorios para pruebas.

### 3. Casos_Prueba
Muestra un conjunto mínimo de **6 casos de prueba** que cubren todas las reglas, equivalencias y valores límite.  
Cada caso incluye entradas (P, E, IG) y el **resultado esperado** (acciones aplicables).

## 📖 Cómo usarlo
1. Abrir el archivo Excel.
2. Identificar en la hoja **Tabla_Decisiones** la regla que corresponde a las condiciones de un empleado.
3. Revisar en **Casos_Prueba** ejemplos listos para verificar el comportamiento esperado.
4. Utilizar **Clases_Equivalencia** para diseñar pruebas adicionales y asegurar cobertura total.

---
✍️ Autor: Resolución generada como apoyo al examen de **Aseguramiento de la Calidad de Software**.
