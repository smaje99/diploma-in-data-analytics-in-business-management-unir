# Diploma in Data Analytics in Business Management (UNIR)

Proyectos del **Diplomado en Analítica de Datos en la Gestión Empresarial** (UNIR).  
Este repositorio reúne ejercicios y proyectos desarrollados en **Jupyter Notebooks**, con foco en análisis exploratorio, limpieza de datos, métricas e insights orientados a negocio.

> 📌 Nota: este repo contiene múltiples proyectos. Cada carpeta principal corresponde a una línea de trabajo independiente.

---

## Contenido

- [Proyectos incluidos](#proyectos-incluidos)
- [Requisitos](#requisitos)
- [Instalación](#instalación)

---

## Proyectos incluidos

### 1) `medellin-business-landscape`
**Objetivo:** análisis del “paisaje empresarial” (business landscape) para extraer insights de distribución / composición / concentración (según el dataset utilizado).

**Qué encontrarás aquí (esperado):**
- notebooks de EDA (limpieza, transformación, variables derivadas)
- métricas e indicadores de interés (p. ej. rankings, participación por categoría, tendencias temporales si aplica)
- visualizaciones y conclusiones orientadas a negocio/territorio

---

### 2) `mbr-susceptibility-eda`
**Objetivo:** análisis exploratorio de datos de “susceptibilidad” de la multiresistencia bacteriana (según el dominio del dataset: clínico/biomédico u otro).

**Qué encontrarás aquí (esperado):**
- EDA del dataset (calidad de datos, nulos, outliers, distribuciones)
- segmentaciones relevantes (por categorías, periodos, grupos, etc.)
- visualizaciones y hallazgos

---

## Requisitos

- Python 3.10+ (recomendado)
- Jupyter Lab o Jupyter Notebook
- Dependencias declaradas en requirements.txt

## Instalación

```bash
python -m venv .venv

# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# macOS/Linux
source .venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt

```
