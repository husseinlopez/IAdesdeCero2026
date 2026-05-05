# Curso IA desde Cero — Edición 2026

Curso práctico introductorio a la Inteligencia Artificial, impartido por el **Departamento de Ciencias de la Computación** del **Centro de Investigación Científica y de Educación Superior de Ensenada (CICESE)**, a través del **Laboratorio de Ciencia de Datos y Aprendizaje Automático (LCDAA)**.

El objetivo del curso es llevar a la persona participante desde los conceptos fundamentales de la IA hasta el despliegue de una aplicación web propia que use modelos de aprendizaje automático sobre datos, imágenes y texto.

---

## 📅 Información general

- **Edición:** 2026
- **Fechas:** del 4 de mayo al 3 de junio de 2026
- **Modalidad:** sesiones prácticas (clases + laboratorio)
- **Sede:** CICESE, Ensenada, Baja California, México
- **Educación Continua:** Física Aplicada / CICESE
- **Contacto del curso:** [cursosdfa@cicese.edu.mx](mailto:cursosdfa@cicese.edu.mx)

---

## 👥 Instructores

- **Dr. Irvin Hussein López Nava** — [hussein@cicese.edu.mx](mailto:hussein@cicese.edu.mx)
- **M.C. Joan M. Raygoza Romero** — [jraygoza@cicese.edu.mx](mailto:jraygoza@cicese.edu.mx)

Departamento de Ciencias de la Computación, CICESE.

---

## 🎯 Objetivos

Al finalizar el curso, la persona participante será capaz de:

1. Comprender qué es la IA, qué la diferencia del aprendizaje automático y del aprendizaje profundo, y qué es la IA generativa.
2. Manipular y explorar conjuntos de datos en Python.
3. Entrenar y evaluar modelos clásicos de aprendizaje automático.
4. Procesar imágenes y texto, y construir clasificadores para cada modalidad.
5. Integrar un modelo en una aplicación web sencilla y desplegarla en línea.

---

## 🗓️ Calendario de sesiones

| # | Fecha | Tema |
|---|---|---|
| 1 | 4/may  | Introducción |
| 2 | 6/may  | Manejo de datos |
| 3 | 11/may | Aprendizaje automático |
| 4 | 13/may | Manejo de imágenes |
| 5 | 18/may | Clasificación de imágenes |
| 6 | 20/may | Manejo de texto |
| 7 | 25/may | Clasificación de texto |
| 8 | 27/may | Integración |
| 9 | 1/jun  | Aplicaciones web |
| 10 | 3/jun | Despliegue de aplicación |

---

## 📂 Estructura del repositorio

```
curso-ia-desde-cero/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── sesiones/
│   ├── 01-introduccion/
│   ├── 02-manejo-de-datos/
│   ├── 03-aprendizaje-automatico/
│   ├── 04-manejo-de-imagenes/
│   ├── 05-clasificacion-de-imagenes/
│   ├── 06-manejo-de-texto/
│   ├── 07-clasificacion-de-texto/
│   ├── 08-integracion/
│   ├── 09-aplicaciones-web/
│   └── 10-despliegue/
├── datos/           # Conjuntos de datos usados en las sesiones
├── notebooks/       # Notebooks complementarios y ejercicios
└── recursos/        # Lecturas, slides y material extra
```

Cada carpeta de sesión contiene su propio `README.md` con los objetivos específicos, los notebooks y los datos correspondientes.

---

## 🛠️ Requisitos previos

- Conocimientos básicos de programación (no necesariamente en Python).
- Computadora con acceso a internet.
- Cuenta de Google (para usar **Google Colab**) **o** instalación local de Python ≥ 3.10.

> No se requiere experiencia previa en IA ni en aprendizaje automático.

---

## ⚙️ Cómo empezar

### Opción 1 — Google Colab (recomendada)

Cada notebook tiene un botón "Open in Colab" en la parte superior. Solo abre el notebook desde la carpeta de la sesión correspondiente y comienza a trabajar; no requiere instalación.

### Opción 2 — Entorno local

```bash
# 1. Clonar el repositorio
git clone https://github.com/<usuario>/curso-ia-desde-cero.git
cd curso-ia-desde-cero

# 2. Crear y activar un entorno virtual
python -m venv .venv
source .venv/bin/activate        # macOS / Linux
# .venv\Scripts\activate         # Windows

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Iniciar Jupyter
jupyter lab
```

---

## 📚 Contenido temático

El curso sigue el orden conceptual:

**IA → Aprendizaje Automático → Aprendizaje Profundo → IA Generativa**

Y aborda, entre otros, los siguientes temas:

- Diferencia entre IA, ML, DL e IA generativa.
- IA débil vs. IA fuerte.
- Tipos de aprendizaje: supervisado, no supervisado y por refuerzo.
- Manejo de datos tabulares con `pandas` y `numpy`.
- Modelos clásicos de ML con `scikit-learn`.
- Procesamiento de imágenes con `OpenCV` / `Pillow` y clasificación con redes neuronales.
- Procesamiento de texto y clasificación (NLP introductorio).
- Construcción de una aplicación web con el modelo entrenado.
- Despliegue de la aplicación en la nube.
- Ética y riesgos del uso de IA.

---

## 🧪 Líneas de investigación del LCDAA

El curso forma parte de las actividades de difusión del Laboratorio de Ciencia de Datos y Aprendizaje Automático, cuyas líneas incluyen:

- Clasificación de actividad y comportamiento humano
- Detección temprana de somnolencia al conducir
- Traducción automática de la Lengua de Señas Mexicana
- Comportamiento no verbal en interacción humano-robot
- Análisis de datos astronómicos
- Análisis de publicaciones en redes sociales
- Medición y análisis del comportamiento canino
- Monitoreo automático de especies marinas

---

## 🤝 Cómo contribuir

Si encuentras un error, una mejora posible o tienes una sugerencia:

1. Abre un *issue* describiendo el problema o la propuesta.
2. Si quieres aportar código, abre un *pull request* desde una rama con un nombre descriptivo (`fix/notebook-sesion-3`, `feat/ejemplo-clasificacion-texto`, etc.).

---

## 📄 Licencia

Este material se distribuye bajo la licencia [MIT](LICENSE), salvo cuando se indique lo contrario en archivos específicos. El material de imágenes, slides y datasets de terceros conserva su licencia original.

---

## ✉️ Contacto

¿Dudas o comentarios?

- **Dr. Irvin Hussein López Nava** — [hussein@cicese.mx](mailto:hussein@cicese.mx)
- **Educación Continua CICESE / Física Aplicada** — [cursosdfa@cicese.edu.mx](mailto:cursosdfa@cicese.edu.mx)

---

<sub>CICESE · Departamento de Ciencias de la Computación · Laboratorio de Ciencia de Datos y Aprendizaje Automático · Edición 2026</sub>
