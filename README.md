# 🎛️ Implementación y Evaluación de Filtros Digitales (MATLAB)

Este repositorio contiene el desarrollo de una actividad de diseño e implementación de **filtros digitales FIR e IIR** utilizando MATLAB.  
El objetivo principal es analizar cómo los filtros afectan una señal compuesta por varias frecuencias y ruido blanco, así como comparar sus respuestas en frecuencia y comportamiento temporal.

---

## 📌 Objetivos del proyecto

- Generar señales de prueba (suma de sinusoides + ruido blanco).
- Diseñar diferentes tipos de filtros digitales:
  - **FIR con ventana de Hamming**
  - **IIR Butterworth**
  - **IIR Chebyshev Tipo I**
- Aplicar los filtros sobre las señales de prueba.
- Visualizar y comparar:
  - Señales antes y después del filtrado.
  - Respuesta en frecuencia de cada filtro.
  - Retardo de grupo (cuando aplica).
- Documentar el proceso de forma clara y entendible.

---

## 📂 Archivos del repositorio

| Archivo | Descripción |
|--------|-------------|
| `implementacion_filtros_documentado.m` | Script principal completamente documentado. |
| `figs/` | Carpeta opcional para guardar imágenes de resultados. |
| `README.md` | Este archivo. |

---

## 🧪 Descripción del código

El script está organizado de acuerdo con las recomendaciones académicas:

### **1. Definición de la señal de entrada**
- Frecuencia de muestreo: `fs = 1000 Hz`
- Duración: `T = 5 s`
- Señal compuesta:
  - 5 Hz
  - 40 Hz
  - 120 Hz
- Ruido blanco agregado para simular medición real.

### **2. Diseño de los filtros**
- **LPF (Pasa-bajos)**: 60 Hz  
