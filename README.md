# PROYECTO DE INVESTIGACIÓN

# Tema: Evaluación automatizada de escenarios de calidad del aire para SO₂ mediante aprendizaje automático en La Oroya, 2018–2021

Este repositorio reúne el desarrollo técnico de una investigación que busca desarrollar y evaluar un procedimiento automatizado para comparar escenarios de calidad del aire para dióxido de azufre (SO₂), incorporando técnicas de aprendizaje automático como apoyo para caracterizar episodios de contaminación atmosférica en La Oroya durante el periodo 2018–2021.

## 📌 Descripción

La investigación propone integrar registros de concentración de SO₂, información meteorológica y criterios nacionales e internacionales de calidad del aire para analizar la frecuencia, intensidad y duración de los episodios de contaminación.

Se compararán principalmente el ECA peruano de 2017 (250 µg/m³), la referencia particular documentada para el Complejo Metalúrgico de La Oroya (365 µg/m³) y la guía de la OMS de 2021 (40 µg/m³), considerando las reglas y condiciones de aplicación de cada escenario.

Como complemento, se evaluarán técnicas de aprendizaje automático no supervisado, como K-means e Isolation Forest, para identificar perfiles meteorológicos y condiciones atmosféricas atípicas, y determinar si aportan información adicional al análisis ambiental convencional.

El proyecto contempla el desarrollo de un prototipo denominado *NormEval*, orientado a automatizar los cálculos y facilitar la consulta y visualización de resultados.

## 📊 Fuentes de datos

Calidad del aire: registros diarios de SO₂ de la estación CA-CC-01 del OEFA, La Oroya.

Meteorología observada: registros de la estación La Oroya (código 000604) del SENAMHI.

Meteorología de reanálisis: ERA5 del programa Copernicus, con información de temperatura, humedad, viento, precipitación, radiación solar y presión atmosférica.

Normativa peruana: Estándares de Calidad Ambiental para Aire del MINAM e instrumentos ambientales aplicables.

Referencias internacionales: Directrices Mundiales sobre la Calidad del Aire de la OMS (2021).

## 🛠️ Tecnologías

* Python
* Jupyter Notebook
* Pandas y NumPy
* Scikit-learn
* SciPy
* Matplotlib
* Streamlit (prototipo)
* Joblib (almacena modelos entrenados)

## 📂 Estructura del repositorio

    01_notebooks_proyecto/
    02_datos_originales/
    03_datos_construidos/
    04_analisis_ambiental/
    05_resultados_modelado/
    06_prototipo_normeval/
    07_documentacion_tecnica/

## 📈 Contenido

El repositorio se organizará para documentar progresivamente:

* Obtención e integración de datos ambientales y meteorológicos.
* Construcción del dataset maestro y conjuntos de datos analíticos.
* Auditoría de registros, análisis de faltantes y preprocesamiento.
* Análisis descriptivo de concentraciones y episodios de SO₂.
* Comparación de escenarios de calidad del aire.
* Entrenamiento y evaluación de modelos de aprendizaje automático no supervisado.
* Validación temporal, análisis de estabilidad y sensibilidad de los resultados.
* Desarrollo y pruebas del prototipo NormEval.
* Documentación de los procedimientos para facilitar su reproducción.

## 🔎 Estado del proyecto

*En preparación y desarrollo preliminar.*


## 👨‍💻 Autor

**Jhoenmert Edgar Tinoco Canto**

Maestría en Ciencias en Ingeniería Ambiental

Mención en Gestión Ambiental

Universidad Nacional de Ingeniería (UNI)

Lima, Perú — 2026
