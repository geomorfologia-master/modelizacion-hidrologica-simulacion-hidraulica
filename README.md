# Práctica: Modelización hidrológica y simulación hidráulica de un arroyo de la cordillera Septentrional

**Asignatura:** Geomorfología (GEO-114)  
**Modalidad:** Trabajo de investigación aplicado

## 1. Objetivo

Desarrollar una modelización hidrológica y una simulación hidráulica de un arroyo que desciende de la cordillera Septentrional, en un tramo anterior a su desembocadura en el río Yuna.

El trabajo deberá integrar análisis del relieve, delimitación de cuencas, modelización de la escorrentía y simulación de la propagación de una crecida.

## 2. Datos disponibles

Se utilizarán dos modelos digitales de elevación (DEM), con funciones diferentes:

- **Modelización hidrológica:** DEM de 12.5 m proporcionado por el profesor. Alternativamente, el estudiante podrá utilizar un DEM de 30 o 90 m obtenido por sus propios medios.
- **Simulación hidráulica:** DEM de alta resolución (1 m), proporcionado por el profesor.

Podrán incorporarse otros datos espaciales, hidrometeorológicos y bibliográficos que el estudiante considere necesarios.

## 3. Requisitos mínimos

### A. Modelización hidrológica — HEC-HMS

- Delimitar la cuenca y caracterizar sus principales propiedades morfométricas.
- Construir el modelo de cuenca (*Basin Model*).
- Construir el modelo meteorológico (*Meteorologic Model*), incluyendo un escenario de precipitación justificado.
- Definir las series temporales necesarias (*Time-Series Data*).
- Configurar las especificaciones de control (*Control Specifications*).
- Ejecutar el modelo y obtener hidrogramas de caudal.
- Interpretar los resultados hidrológicos.

### B. Simulación hidráulica — HEC-RAS

- Preparar el terreno de alta resolución y delimitar el dominio de simulación.
- Construir el modelo hidráulico del tramo seleccionado.
- Incorporar las condiciones de contorno, incluyendo el hidrograma obtenido mediante HEC-HMS.
- Definir y justificar los parámetros hidráulicos.
- Ejecutar una simulación de flujo no permanente.
- Obtener e interpretar mapas de extensión de inundación, profundidad y velocidad del flujo.

## 4. Manuscrito científico

Cada equipo elaborará un manuscrito con estructura científica, que incluya como mínimo:

1. **Título y resumen.**
2. **Introducción:** contexto, antecedentes y objetivos.
3. **Área de estudio:** localización y características geomorfológicas e hidrológicas.
4. **Materiales y métodos:** datos, herramientas, procedimientos y decisiones de modelización.
5. **Resultados:** mapas, gráficos, tablas e indicadores relevantes.
6. **Discusión:** interpretación geomorfológica, limitaciones e incertidumbres.
7. **Conclusiones.**
8. **Referencias bibliográficas.**

El manuscrito debe permitir comprender y reproducir las principales etapas del trabajo.

## 5. Entregables

El repositorio deberá contener:

- Manuscrito científico en PDF.
- Proyectos y archivos necesarios de HEC-HMS y HEC-RAS.
- Datos de entrada y resultados principales, o enlaces para obtenerlos cuando su tamaño impida incorporarlos al repositorio.
- Mapas, figuras y tablas utilizados en el manuscrito.
- Una descripción breve de la organización de los archivos y de cómo reproducir los modelos.

## 6. Consideraciones generales

Los estudiantes tendrán libertad para seleccionar los métodos de transformación lluvia-escorrentía, parámetros, escenarios de precipitación y configuraciones de simulación, siempre que sus decisiones estén justificadas.

Se valorará especialmente la coherencia entre ambos modelos, la interpretación geomorfológica de los resultados, la calidad cartográfica, la reproducibilidad y la discusión crítica de las incertidumbres.

**No se espera únicamente obtener una simulación funcional, sino comprender y explicar los procesos hidrológicos e hidráulicos representados.**
