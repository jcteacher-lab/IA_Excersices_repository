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
├── 01-fundamentos-matematicos/
│   ├── algebra-lineal/
│   ├── calculo-multivariable/
│   ├── probabilidad-estadistica/
│   └── optimizacion/
│
├── 02-machine-learning/
│   ├── supervised-learning/
│   ├── unsupervised-learning/
│   ├── ensembles/
│   └── feature-engineering/
│
├── 03-deep-learning/
│   ├── redes-neuronales-basicas/
│   ├── cnn/
│   ├── rnn-lstm-gru/
│   ├── transformers/
│   └── autoencoders-gans/
│
├── 04-nlp/                            ← PLN
│   ├── preprocesamiento/
│   ├── embeddings/
│   ├── modelos-clasicos/
│   └── llms/
│
├── 05-computer-vision/
│   ├── procesamiento-imagenes/
│   ├── deteccion-objetos/
│   ├── segmentacion/
│   └── vision-transformers/
│
├── 06-reinforcement-learning/
│   ├── bandits-multiarm/
│   ├── q-learning/
│   ├── policy-gradients/
│   └── deep-rl/
│
├── 07-generative-ai-llms/
│   ├── prompt-engineering/
│   ├── fine-tuning/
│   ├── rag/
│   └── agentes/
│
├── 08-mlops/
│   ├── dockerizacion/
│   ├── pipelines/
│   ├── despliegue/
│   └── monitoreo/
│
├── 09-etica-ia/
│   ├── sesgo-fairness/
│   ├── explicabilidad/
│   └── regulacion/
│
├── 10-datasets/
│   └── README.md
│
└── PLN/
    └── Regrex/
        ├── Expresiones regulares en Python.pdf
        └── Expresiones regulares en Python.text