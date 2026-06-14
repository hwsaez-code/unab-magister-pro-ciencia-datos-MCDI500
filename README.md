# Proyecto de Ciencia de Datos

## Descripción General

Este repositorio contiene el desarrollo de un proyecto de Ciencia de Datos enfocado en la aplicación de las primeras fases de una metodología analítica, considerando:

1. Comprensión del Negocio.
2. Comprensión de los Datos.
3. Preparación de los Datos.

El objetivo principal es transformar datos brutos en un conjunto de datos confiable y estructurado que permita realizar análisis posteriores, generar conocimiento y apoyar la toma de decisiones.

---

# Objetivos del Proyecto

## Objetivo General

Desarrollar un proceso de análisis de datos que permita comprender una problemática de negocio, explorar la información disponible y preparar los datos para futuras etapas de modelamiento y evaluación.

## Objetivos Específicos

- Identificar y comprender el contexto del problema de negocio.
- Analizar las características, calidad y estructura de los datos disponibles.
- Detectar inconsistencias, valores faltantes y posibles anomalías.
- Aplicar procesos de limpieza y transformación de datos.
- Generar un conjunto de datos preparado para análisis posteriores.

---

# Metodología

El proyecto sigue una aproximación basada en las primeras etapas de CRISP-DM (Cross Industry Standard Process for Data Mining).

## 1. Comprensión del Negocio

Durante esta fase se busca:

- Definir el problema a resolver.
- Identificar los objetivos del análisis.
- Comprender las necesidades de los usuarios o stakeholders.
- Determinar los indicadores de éxito.
- Establecer el alcance del proyecto.

### Preguntas clave

- ¿Qué problema se desea resolver?
- ¿Qué valor aportará el análisis?
- ¿Quién utilizará los resultados?
- ¿Qué decisiones serán apoyadas por los hallazgos?

---

## 2. Comprensión de los Datos

Esta etapa considera:

- Recolección de datos.
- Descripción de las fuentes de información.
- Exploración inicial de variables.
- Identificación de patrones.
- Detección de problemas de calidad.

### Actividades realizadas

- Carga de datos.
- Revisión de tipos de datos.
- Estadísticas descriptivas.
- Identificación de valores nulos.
- Análisis exploratorio de datos (EDA).
- Visualización de distribuciones y relaciones.

---

## 3. Preparación de los Datos

En esta fase se realizan las transformaciones necesarias para obtener un dataset apto para análisis posteriores.

### Procesos considerados

- Limpieza de datos.
- Tratamiento de valores faltantes.
- Eliminación de duplicados.
- Corrección de inconsistencias.
- Conversión de tipos de datos.
- Transformación de variables.
- Selección de atributos relevantes.

---

### 4. Etapa de Modularización y Orquestación (POO)

Componentes a considerar: 

- Análisis y diagnóstico de calidad de datos automáticos.
- Limpieza estructural y conversión de tipos.
- Jerarquía de clases para tratamiento y alteración de variables.
- Normalización de texto, fechas y nomenclaturas.
- Suite para asegurar la integridad de los resultados.
- Orquestador central encargado de unir todos los módulos.

### Procesos considerados

- Organización del código en clases independientes.
- Imputación y escalado de variables usando POO.
- Limpieza y reemplazo de valores nulos.
- Unificación de alias y categorías repetidas.
- Formateo de textos.
- Estandarización de nombres de columnas.
- Escalamiento y normalización de números.
- Asignación de regiones mediante recursividad.
- Validación automática de casos de prueba.
- Creación de un pipeline de ejecución continuo.


Un conjunto de datos consistente, limpio y documentado para futuras etapas de modelado y evaluación.

---

# Estructura del Repositorio

```text
proyecto-ciencia-datos/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── datos/
│   ├── original/
│   ├── resultado/
│   ├── comunas-regiones.json
│
├── notebooks/
│   ├── Notebook F1_Definición.ipynb 
│   ├── Notebook F2_Transformation.ipynb
│   ├── Notebook F3_POO.ipynb       
│
├── src/
│
└── docs/