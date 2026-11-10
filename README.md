# 🧠 IA Exercises & Academic Papers

![Licencia](https://img.shields.io/badge/Licencia-GPLv3-blue.svg)
![Markdown](https://img.shields.io/badge/Markdown-000000?logo=markdown&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Activo-success)
![Contribuciones](https://img.shields.io/badge/contribuciones-bienvenidas-brightgreen)

Repositorio académico que reúne **ejercicios resueltos, notebooks interactivos y documentos de estudio** sobre Inteligencia Artificial, organizados por áreas de especialización. Diseñado como material de consulta abierto para estudiantes, docentes e investigadores que quieran aprender, repasar o reutilizar contenido de IA sin depender de plataformas cerradas.

Cada área incluye ejercicios prácticos, material teórico en PDF/LaTeX, notebooks reproducibles y datasets de ejemplo. El repositorio se actualiza de forma continua y mantiene una **política de licencia libre** para todo el contenido generado por el autor.

**🌐 Índice navegable**: [https://jcteacher-lab.github.io/IA_Excersices_repository/](https://jcteacher-lab.github.io/IA_Excersices_repository/) *(disponible al activar GitHub Pages)*

---

## Tabla de contenidos

- [1. Características](#1-características)
- [2. Estructura del repositorio](#2-estructura-del-repositorio)
- [3. Áreas de IA cubiertas](#3-áreas-de-ia-cubiertas)
- [4. Índice de documentos](#4-índice-de-documentos)
- [5. Instalación y uso](#5-instalación-y-uso)
- [6. Convenciones del repositorio](#6-convenciones-del-repositorio)
- [7. Stack tecnológico](#7-stack-tecnológico)
- [8. Cómo contribuir](#8-cómo-contribuir)
- [9. Roadmap](#9-roadmap)
- [10. Agradecimientos](#10-agradecimientos)
- [11. Autor](#11-autor)
- [12. Licencia](#12-licencia)
- [13. Proyectos relacionados](#13-proyectos-relacionados)

---

## 1. Características

### 📚 Material académico centralizado
- **Ejercicios resueltos** de cursos universitarios y especializaciones en IA.
- **Notebooks reproducibles** en Jupyter con explicaciones paso a paso.
- **Documentos de estudio** (resúmenes, apuntes, guías y papers comentados).
- **Datasets de ejemplo** utilizados en los ejercicios.

### 🗂 Organización por áreas
- Clasificación temática clara: desde fundamentos matemáticos hasta LLMs, MLOps y ética.
- Cada área cuenta con su propio `README.md` con temario y descripción.
- Estructura consistente en todas las carpetas: `/ejercicios/`, `/documentos/`, `/datasets/`.

### 🌐 Índice navegable
- Página `index.html` con buscador, filtrado por área y descarga directa de cada documento.
- Compatible con GitHub Pages para consulta desde el navegador.
- Alternativa en Markdown (`docs/index.md`) para lectura directa desde el repo.

### 📖 Documentación complementaria
- Guías de ejercicios en **LaTeX** (compilables a PDF) para uso didáctico.
- Referencias bibliográficas y enlaces a recursos externos (papers, cursos, tutoriales).
- Rúbricas de evaluación y material de apoyo para el docente.

### 🆓 Sin dependencias propietarias
- Todo el contenido es **open source**.
- Los notebooks usan librerías estándar del ecosistema (NumPy, Pandas, scikit-learn, PyTorch, TensorFlow).
- Los documentos están en formatos abiertos (PDF, Markdown, LaTeX, `.ipynb`, `.txt`).

---

## 2. Estructura del repositorio

```text
IA_Excersices_repository/
│
├── README.md                          ← este archivo
├── LICENSE                            ← texto legal GNU GPL v3
├── index.html                         ← índice navegable (GitHub Pages)
├── requirements.txt                   ← dependencias base de Python
├── .gitignore                         ← exclusiones para Git
│
├── docs/
│   ├── index.md                       ← índice en Markdown
│   └── CONTRIBUTING.md                ← guía de contribución
│
├── Fundamentos-Matematicos/
│   ├── Algebra-lineal/
│   ├── Calculo-multivariable/
│   ├── Probabilidad-estadistica/
│   └── Optimizacion/
│
├── Machine-learning/
│   ├── supervised-learning/
│   ├── unsupervised-learning/
│   ├── ensembles/
│   └── feature-engineering/
│
├── Deep-Learning/
│   ├── redes-neuronales-basicas/
│   ├── cnn/
│   ├── rnn-lstm-gru/
│   ├── transformers/
│   └── autoencoders-gans/
│
├── PLN/
|   ├── preprocesamiento/
│   ├── embeddings/
│   ├── modelos-clasicos/
│   └── llms/
|   └── Regrex/
|       ├── Expresiones regulares en Python.pdf
|       └── Expresiones regulares en Python.text
│
├── Computer-vision/
│   ├── procesamiento-imagenes/
│   ├── deteccion-objetos/
│   ├── segmentacion/
│   └── vision-transformers/
│
├── Reinforcement-learning/
│   ├── bandits-multiarm/
│   ├── q-learning/
│   ├── policy-gradients/
│   └── deep-rl/
│
├── Generative-ai-llms/
│   ├── prompt-engineering/
│   ├── fine-tuning/
│   ├── rag/
│   └── agentes/
│
├── Mlops/
│   ├── dockerizacion/
│   ├── pipelines/
│   ├── despliegue/
│   └── monitoreo/
│
├── Etica-IA/
│   ├── sesgo-fairness/
│   ├── explicabilidad/
│   └── regulacion/
│
└── Datasets/
    └── README.md
​```
---

## 3. Áreas de IA cubiertas

| # | Área | Descripción | Estado |
|---|------|-------------|--------|
| 01 | 🧮 **Fundamentos Matemáticos** | Álgebra lineal, cálculo, probabilidad y optimización aplicados a IA. | 🚧 En progreso |
| 02 | 🤖 **Machine Learning** | Supervisado, no supervisado, ensembles y feature engineering. | 🚧 En progreso |
| 03 | 🧠 **Deep Learning** | Redes neuronales, CNN, RNN, Transformers, GANs. | 🚧 En progreso |
| 04 | 💬 **PLN / NLP** | Procesamiento de lenguaje natural, embeddings, LLMs. | 🟢 Activo |
| 05 | 👁 **Computer Vision** | Procesamiento de imágenes, detección y segmentación. | 🚧 En progreso |
| 06 | 🎮 **Reinforcement Learning** | Bandits, Q-Learning, Policy Gradients, Deep RL. | 🚧 En progreso |
| 07 | ✨ **Generative AI & LLMs** | Prompt engineering, fine-tuning, RAG, agentes. | 🚧 En progreso |
| 08 | ⚙️ **MLOps** | Docker, pipelines, despliegue y monitoreo. | 🚧 En progreso |
| 09 | ⚖️ **Ética en IA** | Sesgo, fairness, explicabilidad, regulación. | 🚧 En progreso |
| 10 | 📊 **Datasets** | Conjuntos de datos utilizados en los ejercicios. | 🚧 En progreso |

> 🟢 Activo con documentos · 🚧 En progreso (sin documentos aún) · ⏳ Planeado

---

## 4. Índice de documentos

### 💬 PLN — Procesamiento de Lenguaje Natural

| Documento | Tipo | Temas | Enlace |
|-----------|------|-------|--------|
| **Expresiones regulares en Python** — Guía PDF | `PDF` | `Python` · `Regex` · `PLN` | [📄 Abrir](https://github.com/jcteacher-lab/IA_Excersices_repository/blob/main/PLN/Regrex/Expresiones%20regulares%20en%20Python.pdf) |
| **Expresiones regulares en Python** — Texto plano | `TEXT` | `Python` · `Regex` · `PLN` | [📝 Abrir](https://github.com/jcteacher-lab/IA_Excersices_repository/blob/main/PLN/Regrex/Expresiones%20regulares%20en%20Python.text) |

---

## 5. Instalación y uso

### Opción 1 — Clonar el repositorio

```bash
git clone https://github.com/jcteacher-lab/IA_Excersices_repository.git
cd IA_Excersices_repository
```

### Opción 2 — Crear un entorno virtual (recomendado)

```bash
python -m venv .venv
source .venv/bin/activate       # Linux / macOS
.venv\Scripts\activate          # Windows
```

### Opción 3 — Instalar dependencias

```bash
pip install -r requirements.txt
```

### Opción 4 — Abrir los notebooks

```bash
jupyter lab
```

### Opción 5 — Publicar el índice en GitHub Pages

1. Sube `index.html` a la raíz del repositorio.
2. Ve a **Settings → Pages**.
3. Source: `Deploy from a branch` → Branch `main` → Folder `/ (root)`.
4. URL resultante:

```
https://jcteacher-lab.github.io/IA_Excersices_repository/
```

### Consulta directa de documentos

Los PDFs, notebooks y apuntes se pueden abrir directamente desde GitHub sin clonar el repo. Solo haz clic en el enlace del [índice de documentos](#4-índice-de-documentos).

---

## 6. Convenciones del repositorio

### Estructura de cada área

Cada carpeta de área contiene:

- `README.md` → Descripción del área y temario.
- `/ejercicios/` → Ejercicios resueltos (`.ipynb`, `.py` o `.pdf`).
- `/documentos/` → Apuntes, resúmenes y papers (`.pdf`, `.md`, `.tex`).
- `/datasets/` → Datos utilizados en los ejercicios.
- `requirements.txt` → Dependencias específicas del área (si aplica).

### Nomenclatura de archivos

```
<área>_<tema>_<nivel>_<autor>.<ext>

Ejemplos:
pln_regex_basico_jdoe.pdf
ml_regresion-lineal_basico_jdoe.ipynb
dl_cnn-cifar10_intermedio_jdoe.ipynb
```

### Niveles de dificultad

| Nivel | Descripción |
|-------|-------------|
| `basico` | Introducción al tema, sin prerrequisitos avanzados. |
| `intermedio` | Requiere conocimientos previos del área. |
| `avanzado` | Temas de especialización o investigación. |

---

## 7. Stack tecnológico

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown)

</div>

---

## 8. Cómo contribuir

Este proyecto es software libre bajo GPL v3 y todas las contribuciones son bienvenidas.

1. Haz **fork** del repositorio.
2. Crea una rama: `git checkout -b feature/nueva-area`.
3. Realiza tus cambios siguiendo la estructura y nomenclatura descritas.
4. Haz commit: `git commit -m "feat: añade ejercicios de X área"`.
5. Haz push: `git push origin feature/nueva-area`.
6. Abre un **Pull Request**.

### Buenas prácticas

- Mantén el estilo y la estructura de carpetas existente.
- Si añades un documento, actualiza también `index.html` y este `README.md`.
- Si añades un notebook, asegúrate de que sea reproducible (incluye `requirements`).
- Documenta las fórmulas y conceptos clave en el README del área correspondiente.
- Al ser GPL v3, tus contribuciones se integrarán bajo la misma licencia.

### Ideas especialmente buscadas

- Ejercicios de PLN con `spaCy`, `NLTK` y `Hugging Face Transformers`.
- Notebooks de fine-tuning de LLMs con `peft` y `trl`.
- Guías de MLOps con Docker, MLflow y GitHub Actions.
- Material sobre ética en IA y fairness (AI Fairness 360, SHAP).
- Traducción de guías al inglés, francés o portugués.

Consulta [`docs/CONTRIBUTING.md`](./docs/CONTRIBUTING.md) para más detalles.

---

## 9. Roadmap

- [x] Repositorio base con estructura por áreas de IA.
- [x] Primer documento: *Expresiones regulares en Python* (PLN) — PDF y texto plano.
- [x] Índice navegable con buscador (`index.html`).
- [x] Alternativa de índice en Markdown (`docs/index.md`).
- [ ] Añadir notebooks de Machine Learning (regresión, clasificación, clustering).
- [ ] Añadir ejercicios de Deep Learning con PyTorch.
- [ ] Guía de PLN con spaCy y Transformers.
- [ ] Guía de Computer Vision con OpenCV y torchvision.
- [ ] Notebook de fine-tuning de un LLM pequeño.
- [ ] Guía de MLOps con Docker y despliegue.
- [ ] Documento de ética en IA y fairness.
- [ ] Workflow de GitHub Actions que regenere `docs/index.md` automáticamente.
- [ ] Versión en inglés de la documentación.

---

## 10. Agradecimientos

A todos los docentes, autores y comunidades open source que comparten conocimiento y hacen posible este repositorio. Inspirado en la tradición de recursos abiertos para la enseñanza (PhET, Khan Academy, Hugging Face Course, fast.ai) y en la convicción de que el material educativo de calidad debe ser libre y accesible.

Construido con la idea de que cualquier docente o estudiante pueda extenderlo, modificarlo y adaptarlo a sus necesidades sin depender de plataformas propietarias.

---

## 11. Autor

**MTI. Juan Carlos Santiago Sánchez**

- GitHub: [@jcteacher-lab](https://github.com/jcteacher-lab)
- Correo: juancarlos.santiago.cb161@dgeti.sems.gob.mx

---

## 12. Licencia

**IA Exercises & Academic Papers**

Copyright (C) 2026

Este programa es software libre: puedes redistribuirlo y/o modificarlo bajo los términos de la GNU General Public License tal como la publica la Free Software Foundation, ya sea la versión 3 de la Licencia, o (a tu elección) cualquier versión posterior.

Este programa se distribuye con la esperanza de que sea útil, pero **SIN NINGUNA GARANTÍA**; ni siquiera la garantía implícita de COMERCIABILIDAD o IDONEIDAD PARA UN PROPÓSITO PARTICULAR. Consulta la GNU General Public License para más detalles.

Deberías haber recibido una copia de la GNU General Public License junto con este programa. Si no es así, consulta [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).

### Resumen de la licencia

|  |  |
|--|--|
| Licencia | GNU General Public License v3.0 |
| SPDX | GPL-3.0-or-later |
| Copyright | (C) 2026 |
| Texto legal completo | [LICENSE](./LICENSE) · [gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.txt) |

> **Nota sobre documentos de terceros**: los papers y materiales académicos incluidos mantienen sus licencias originales. Solo se incluyen versiones **open access** o enlaces oficiales a los repositorios de los autores.

> **Importante**: para que el proyecto esté correctamente licenciado bajo GPL v3, además de este `README.md` debes incluir en la raíz del repositorio un archivo llamado `LICENSE` (sin extensión) con el texto legal completo. Puedes obtenerlo con:

```bash
curl -o LICENSE https://www.gnu.org/licenses/gpl-3.0.txt
```

---

## 13. Proyectos relacionados

Otros simuladores educativos y herramientas didácticas del mismo autor, todos con licencia libre y orientados a la enseñanza de la física y las matemáticas:

- [**Simulador del Sistema Solar**](https://jcteacher-lab.github.io/sistemasolar/) — Simulador interactivo del Sistema Solar con órbitas keplerianas reales (elementos J2000), panel de datos físicos y guía de ejercicios en LaTeX.
- [**Simulador de Tiro Parabólico**](https://jcteacher-lab.github.io/tiroparabolico) — Simulador educativo de movimiento de proyectiles con Canvas 2D.
- [**Simulador de Movimiento Circular**](https://github.com/jcteacher-lab/movimientocircular) — Simulador interactivo de movimiento circular uniforme (MCU) con vectores de velocidad, fuerza y aceleración centrípeta en tiempo real, en tres versiones (escritorio, móvil y universal).
- [**Analizador de parábolas**](https://github.com/jcteacher-lab/analizadordeparabolas) — Herramienta didáctica para explorar la parábola: cambia a, h y k con deslizadores y observa cómo se traslada el vértice.
- [**Graficador dinámico de parábolas**](https://github.com/jcteacher-lab/Graficador_dinamico_parabolas) — Simulador educativo que construye la gráfica y la ecuación de una parábola a partir de sus elementos geométricos: Vértice, Foco y Directriz.

---

> *"La inteligencia artificial no reemplaza al que aprende, pero sí amplifica al que entiende."*

Hecho con ❤️ y con libertad — GPL v3 garantiza que el conocimiento seguirá siendo libre.
