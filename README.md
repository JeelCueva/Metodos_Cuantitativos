# 📐 Métodos Cuantitativos para la Economía — Notebooks Python

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JeelCueva/Metodos_Cuantitativos)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 👨‍🏫 Autor

**MSc. Jeel Cueva** — Catedrático Universitario  
UNHEVAL | UDH | UTP — Lima, Perú, 2025

---

## 📚 Descripción

Notebooks de Python con **todos los ejemplos resueltos** del libro *"Métodos Cuantitativos para la Economía"*.

Cada ejemplo incluye:
- ✅ Resolución algebraica paso a paso
- 📊 Gráfica profesional con `matplotlib`
- 🔍 Verificación numérica del resultado
- 💬 Interpretación económica

---

## 📂 Estructura

```
Metodos_Cuantitativos/
├── notebooks/
│   ├── Cap01_Funciones_Elementales.ipynb        ← Cap. 1
│   ├── Cap02_Limites_Continuidad.ipynb          ← Cap. 2
│   ├── Cap03_Derivada_Reglas.ipynb              ← Cap. 3
│   ├── Cap04_Aplicaciones_Derivada.ipynb        ← Cap. 4
│   ├── Cap05_Funciones_Trascendentes.ipynb      ← Cap. 5
│   ├── Cap06_Integral_Indefinida.ipynb          ← Cap. 6
│   └── Cap07_Integral_Definida.ipynb            ← Cap. 7
├── requirements.txt
└── README.md
```

---

## 📋 Contenido por Capítulo

| Cap. | Título | Temas |
|------|--------|-------|
| **1** | Funciones Elementales | Lineal, cuadrática, exponencial, equilibrio, break-even, elasticidad |
| **2** | Límites y Continuidad | Formas indeterminadas, límites laterales, asíntotas, TVI |
| **3** | Derivada y Reglas | Reglas básicas, producto, cociente, cadena, implícita, orden superior |
| **4** | Aplicaciones de la Derivada | IM=CM, elasticidad, análisis completo, TVM, EOQ |
| **5** | Funciones Trascendentes | Exp, log, capitalización, regla del 70, VP, logística, Ley de Engel |
| **6** | Integral Indefinida | Antiderivadas, sustitución, partes, fracciones parciales |
| **7** | Integral Definida | Sumas Riemann, TFC, áreas, excedentes EC/EP, VP flujos, impropias |

---

## 🚀 Inicio Rápido

### Google Colab (sin instalación)
Clic en el badge **"Open in Colab"** de cualquier notebook.

### Local

```bash
git clone https://github.com/JeelCueva/Metodos_Cuantitativos.git
cd Metodos_Cuantitativos
pip install -r requirements.txt
jupyter notebook notebooks/
```

---

## 📊 Ejemplos Destacados

```python
# Cap. 1 — Equilibrio de Mercado
# Qd=200-4P, Qs=50+6P → P*=15, Q*=140
P_eq = (200 - 50) / (4 + 6)

# Cap. 4 — EOQ
Q_star = np.sqrt(2*D*s / h)    # D=1200, s=50, h=2 → Q*=245

# Cap. 7 — Excedente del Consumidor
EC, _ = quad(lambda Q: D(Q) - P_eq, 0, Q_eq)  # EC=3600
```

---

## 📄 Licencia

Código fuente: **MIT License** | Contenido académico © 2025 MSc. Jeel Cueva

---
*"La matemática es el lenguaje con el que Dios escribió el universo."* — Galileo Galilei
