# # 🧪 HCI-2026-G1 — Usability Test Plan Dashboard

> **Rediseño de una interfaz de planificación de pruebas de usabilidad mediante principios de Interacción Humano-Computador (IHC).**

**Universidad Técnica de Ambato**  
**FISEI | Carrera de Software**  
**Asignatura:** Interacción Humano Computador  
**Grupo:** 1  
**Periodo:** 2026

---

## 📌 Descripción del proyecto

**HCI-2026-G1** es un proyecto académico enfocado en el análisis y rediseño del **Usability Test Plan Dashboard**, una interfaz utilizada para organizar y ejecutar procedimientos relacionados con pruebas de usabilidad.

El proyecto parte del diagnóstico de la interfaz original y aplica conceptos de **Interacción Humano-Computador (IHC)** para mejorar la organización visual, reducir la carga cognitiva, comunicar el estado del sistema y proporcionar una experiencia más clara durante la ejecución de una prueba.

El proceso incluye el análisis de **touchpoints**, identificación de **Momentos de Verdad (MdV)**, construcción de una **curva emocional**, rediseño del prototipo y comparación **Antes vs. Después**.

---

## 🎯 Objetivo

Evaluar y rediseñar la experiencia de usuario (UX) del **Usability Test Plan Dashboard** aplicando principios fundamentales de Interacción Humano-Computador, con el propósito de:

- Optimizar la jerarquía visual.
- Reducir la carga cognitiva.
- Mejorar la organización de los elementos.
- Garantizar la visibilidad del estado del sistema.
- Facilitar el seguimiento secuencial de una prueba.
- Mejorar la experiencia emocional del usuario durante la interacción.

---

## 🔎 Problema identificado

La interfaz original presentaba diferentes problemas de usabilidad y diseño de interacción.

| Problema | Descripción | Consecuencia |
| --- | --- | --- |
| **Jerarquía visual plana** | Los bloques de texto y áreas de entrada carecían de diferenciación visual. | La interfaz se percibía como un formulario estático en lugar de una herramienta interactiva. |
| **Contraste y uso del espacio** | Predominaban fondos grises sobre blanco sin una separación visual clara. | Dificultad para identificar secciones y prioridades. |
| **Problemas de proximidad y alineación** | Fechas, campos y *checkboxes* de `Review before the test` se encontraban desalineados. | Mayor carga cognitiva y posibilidad de errores. |
| **Falta de secuencialidad** | Los pasos de `Test plan / procedure` se presentaban mediante cajas estáticas. | El usuario no podía identificar fácilmente la etapa actual del proceso. |

---

## 🧠 Conceptos de IHC aplicados

### 🗂️ Ley de Región Común — Gestalt

Los elementos relacionados fueron agrupados mediante componentes **Card UI**, utilizando separación visual y sombras sutiles (*drop shadows*).

Esto permite distinguir rápidamente las diferentes áreas funcionales del dashboard.

### 👁️ Visibilidad del Estado del Sistema

Siguiendo la **Heurística de Nielsen #1**, se incorporó un componente **Stepper** horizontal que representa visualmente las diferentes etapas del procedimiento.

El usuario puede reconocer:

- Qué pasos ya fueron completados.
- En qué paso se encuentra.
- Qué pasos faltan por realizar.

### 📐 Ley de Proximidad y alineación en Grid

La sección de revisión previa fue reorganizada mediante una estructura **Grid**, alineando:

- Campos de fecha.
- Etiquetas.
- *Checkboxes*.
- Elementos relacionados.

Esto facilita el escaneo visual y reduce la posibilidad de cometer errores.

### 📈 Curva Emocional del Usuario

Se analizaron **7 touchpoints** del flujo para representar la evolución de la experiencia mediante niveles emocionales.

La evaluación permitió identificar:

- 😊 Satisfacción.
- 😐 Neutralidad.
- 😟 Frustración.

Posteriormente se compararon las curvas emocionales **Antes vs. Después** del rediseño.

### ⭐ Momentos de Verdad (MdV)

Se identificaron puntos críticos donde la experiencia puede influir significativamente en la percepción general del sistema.

Los principales Momentos de Verdad fueron:

1. **Visualización y seguimiento del procedimiento.**
2. **Revisión del checklist previo a la prueba.**

---

## 🛠️ Mejoras implementadas

El rediseño se concentró en **tres mejoras principales**:

| N.º | Mejora | Principio aplicado | Resultado esperado |
| :---: | --- | --- | --- |
| **1** | Implementación de **Card UI** | Región Común — Gestalt | Mejor agrupación y jerarquía visual |
| **2** | Implementación de **Stepper interactivo** | Visibilidad del Estado del Sistema | Mayor claridad sobre el avance del procedimiento |
| **3** | Organización mediante **Grid de verificación** | Proximidad y alineación | Menor carga cognitiva y reducción de errores |

---

## 🔄 Proceso de trabajo

El proyecto se desarrolló mediante cinco etapas principales:

```text
1. Diagnóstico
       ↓
2. Matriz de experiencia
       ↓
3. Identificación de Momentos de Verdad
       ↓
4. Rediseño del prototipo
       ↓
5. Comparación y evaluación
```

### 1. Línea base y diagnóstico

Se realizó una evaluación cualitativa de la interfaz original para identificar problemas de usabilidad y establecer la **Curva Emocional Inicial**.

### 2. Matriz de experiencia

Se identificaron **7 touchpoints** representativos del recorrido del usuario.

### 3. Momentos de Verdad

Se determinaron **2 Momentos de Verdad (MdV)** donde los problemas de interacción tenían mayor impacto sobre la experiencia.

### 4. Rediseño

Se desarrolló una nueva propuesta incorporando:

- Card UI.
- Stepper interactivo.
- Grid de verificación.

### 5. Evaluación

Finalmente se realizó una comparación **Antes vs. Después**, incluyendo la construcción de la **Curva Emocional Corregida**.

---

## 📊 Resultados

### Antes vs. Después

| Aspecto | Antes | Después |
| --- | --- | --- |
| **Jerarquía visual** | Diseño plano | Organización mediante Card UI |
| **Seguimiento del proceso** | Pasos estáticos | Stepper visual e interactivo |
| **Checklist** | Elementos desalineados | Organización mediante Grid |
| **Estado del sistema** | Poco visible | Progreso claramente identificado |
| **Carga cognitiva** | Mayor esfuerzo de interpretación | Información agrupada y estructurada |
| **Momentos de Verdad** | Presencia de frustración | Mayor satisfacción |
| **Curva emocional** | Valores mínimos de **-2** | Valores de hasta **+2** |

### 📈 Transformación de la experiencia

El análisis comparativo mostró una transformación positiva en los puntos críticos del flujo.

En la interfaz inicial se identificaron valores de **frustración (-2)** durante los Momentos de Verdad correspondientes a los pasos críticos analizados.

Después del rediseño, estos puntos alcanzaron valores de **satisfacción (+2)** en la evaluación planteada.

> Los valores representan la evaluación utilizada en la matriz y curva emocional del proyecto.

---

## 🧰 Herramientas utilizadas

| Herramienta | Uso |
| --- | --- |
| **GitHub** | Control de versiones, Issues, ramas, Pull Requests y trabajo colaborativo |
| **Markdown (`.md`)** | Documentación técnica del proyecto |
| **Herramientas de prototipado** | Wireframes, prototipo rediseñado y evidencias visuales |
| **Mermaid** | Diagramación y representación de la curva emocional |
| **PDF** | Consolidación y presentación final de evidencias |

---

## 👥 Equipo de trabajo

| N.º | Integrante | GitHub | Correo institucional |
| :---: | --- | --- | --- |
| **1** | **Sarco Sailema Viviana Maribel** | `@maribelsailema` | `vsarco7769@uta.edu.ec` |
| **2** | **Guachi Aucapiña Alex Fabricio** | `@A1EXF6A` | `aguachi4414@uta.edu.ec` |
| **3** | **Pillapa Tubón Wilson Joseph** | `@W1LSONN` | `wpillapa8482@uta.edu.ec` |
| **4** | **Santana Durán Sebastián Israel** | `@SebasIsd` | `ssantana1312@uta.edu.ec` |

---

## 🌿 Distribución del trabajo en GitHub

El trabajo colaborativo se organizó mediante **Issues**, permitiendo asignar responsabilidades específicas y mantener trazabilidad sobre los aportes de cada integrante.

| Issue | Tarea | Responsable | GitHub |
| :---: | --- | --- | --- |
| **#1** | `docs: Redactar README.md, preguntas.md, conclusiones.md y PDF final` | **Viviana Sarco** | `@maribelsailema` |
| **#2** | `research: Evaluación de interfaces iniciales, touchpoints y curva emocional inicial` | **Alex Guachi** | `@A1EXF6A` |
| **#3** | `research: Identificación de momentos de verdad y matriz momento/emoción` | **Wilson Pillapa** | `@W1LSONN` |
| **#4** | `design: Prototipo rediseñado, 3 mejoras, comparación antes/después y curva corregida` | **Sebastián Santana** | `@SebasIsd` |

### 🔀 Flujo de colaboración

Cada integrante trabaja mediante el siguiente flujo:

```text
Issue asignado
      ↓
Rama individual
      ↓
Commits
      ↓
Pull Request
      ↓
Revisión cruzada
      ↓
Merge a main
```

Esto permite mantener la trazabilidad de las contribuciones individuales y realizar una revisión antes de incorporar los cambios a la versión principal del proyecto.

---

## 📁 Estructura del repositorio

```text
HCI-2026-G1/
│
├── 📂 docs/
│   ├── 📄 conclusiones.md
│   ├── 📄 investigacion.md
│   └── 📄 preguntas.md
│
├── 📂 evidencias/
│
├── 📂 prototipos/
│
├── 📂 resultados/
│
├── 📂 src/
│
└── 📄 README.md
```

### 📌 Organización del repositorio

| Ubicación | Contenido |
| --- | --- |
| `docs/conclusiones.md` | Conclusiones obtenidas a partir del análisis y rediseño de la interfaz |
| `docs/investigacion.md` | Investigación, fundamentos de IHC, análisis de *touchpoints*, Momentos de Verdad y conceptos aplicados |
| `docs/preguntas.md` | Desarrollo y respuestas de las preguntas planteadas en la actividad |
| `evidencias/` | Evidencias utilizadas y generadas durante el desarrollo del proyecto |
| `prototipos/` | Prototipo original, propuesta rediseñada y recursos relacionados con el diseño |
| `resultados/` | Resultados del análisis, comparaciones y curvas emocionales |
| `src/` | Archivos fuente utilizados para el desarrollo o implementación del proyecto |
| `README.md` | Presentación general, organización, metodología y resumen del proyecto |

---

## ✅ Lista de verificación

- [x] Evaluación de la interfaz original.
- [x] Identificación de problemas de usabilidad.
- [x] Identificación de 7 *touchpoints*.
- [x] Construcción de la curva emocional inicial.
- [x] Identificación de 2 Momentos de Verdad.
- [x] Aplicación de principios de Gestalt.
- [x] Aplicación de la heurística de visibilidad del estado del sistema.
- [x] Implementación conceptual de Card UI.
- [x] Implementación del Stepper.
- [x] Organización del checklist mediante Grid.
- [x] Elaboración del prototipo rediseñado.
- [x] Comparación Antes vs. Después.
- [x] Elaboración de la curva emocional corregida.
- [x] Distribución del trabajo mediante Issues.


---

## 🎓 Conclusiones

### 1. Reducción del esfuerzo cognitivo

La aplicación de principios visuales como la **Región Común** y la **Proximidad** permitió organizar los datos de manera más estructurada, facilitando el procesamiento de la información y reduciendo el esfuerzo necesario para interpretar la interfaz.

### 2. Impacto en la experiencia emocional

La incorporación de componentes como el **Stepper** y la alineación mediante **Grid** permitió transformar puntos de confusión y frustración en interacciones más claras, proporcionando al usuario una mayor percepción de control durante el proceso.

### 3. Trabajo colaborativo

La distribución de responsabilidades mediante **Issues**, ramas y Pull Requests permitió organizar los aportes individuales y mantener la trazabilidad del proceso de investigación, diseño y documentación.

---

## 🏫 Información académica

**Universidad Técnica de Ambato**  
**Facultad de Ingeniería en Sistemas, Electrónica e Industrial — FISEI**  
**Carrera de Software**  
**Interacción Humano Computador — 2026**  
**Grupo 1**

---

> 🧪 **HCI-2026-G1** — Proyecto académico de evaluación y rediseño de interfaces mediante principios de Interacción Humano-Computador.