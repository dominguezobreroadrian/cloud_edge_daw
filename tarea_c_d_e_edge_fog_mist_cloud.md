# Tarea (c+d+e) · Edge, Fog, Mist y Cloud (DAW 1º)

## 🅲 Tarea C — Edge Computing y relación con Cloud
**Definición (3–5 líneas):**
Edge Computing es un paradigma de computación distribuida donde el procesamiento de datos ocurre en dispositivos cercanos al lugar de generación, como routers, gateways o dispositivos IoT. Esto reduce la latencia y mejora la eficiencia de la red al realizar tareas de procesamiento sin depender completamente de la nube.

**Relación Edge ↔ Cloud (5–8 líneas):**
La relación entre Edge Computing y Cloud Computing es complementaria. Mientras que la nube ofrece capacidades de procesamiento y almacenamiento a gran escala, Edge Computing permite realizar procesamiento local en dispositivos cercanos al usuario o máquina, lo que reduce la latencia y el uso de ancho de banda. La nube se encarga de las tareas más intensivas en recursos, mientras que el edge maneja los procesos que requieren una respuesta rápida y en tiempo real.

**Ejemplo real:**
Un ejemplo real de Edge Computing es el uso de cámaras de seguridad inteligentes que procesan imágenes localmente para detectar movimientos o personas, enviando solo los datos relevantes a la nube para almacenamiento o análisis posterior.

**Fuentes oficiales (mín. 2):**
- [IBM Edge Computing](https://www.ibm.com/cloud/edge-computing)
- [Microsoft Azure Edge Computing](https://azure.microsoft.com/en-us/overview/edge-computing/)

## 🅳 Tarea D — Fog vs Mist (niveles y zonas de aplicación)

**Definición Fog (2–4 líneas):**
Fog Computing es un modelo que extiende la computación en la nube hacia los dispositivos cercanos al usuario, pero a diferencia del Edge, abarca una capa adicional de procesamiento, almacenamiento y redes entre los dispositivos finales y la nube. Se utiliza para casos donde el procesamiento no puede hacerse completamente en el borde, pero debe realizarse cerca del lugar de origen.

**Definición Mist (2–4 líneas):**
Mist Computing es una forma más ligera de Fog Computing, orientada a dispositivos con recursos limitados. El procesamiento ocurre aún más cerca de los sensores o dispositivos IoT, siendo un paso previo antes de enviar datos a la red más amplia.

**Esquema (ASCII o Mermaid recomendado):**
```mermaid
graph TB
    A[Mist] --> B[Edge]
    B --> C[Fog]
    C --> D[Cloud]
