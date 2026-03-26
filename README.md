# Proyecto: Reconocimiento de Variedades de Papa Nativa

## Universidad Nacional de San Antonio Abad del Cusco  
Facultad de Ingeniería Eléctrica, Electrónica, Informática y Mecánica  
Carrera Profesional de Ingeniería Informática y de Sistemas  

---

## Integrantes

- Mamani Jara Jorge Luis (210933)  
- Torre Cano Eduardo (211361)  
- Rodriguez Pauccara Cristian Diego (210942)  
- Merma Chura Jeanpier Xilander (210935)  


## Descripción del Proyecto

Este proyecto consiste en el desarrollo de una aplicación móvil para la identificación de variedades de papa nativa mediante el uso de técnicas de aprendizaje automático y visión por computadora.

La solución permite analizar imágenes de papas y clasificarlas automáticamente según sus características visuales, como color, forma, textura y tamaño.

---

## Problema

La identificación de variedades de papa nativa se realiza tradicionalmente mediante observación visual, lo cual es subjetivo, requiere experiencia y es propenso a errores.

---

## Objetivo General

Desarrollar una aplicación móvil que permita la identificación precisa y rápida de variedades de papa nativa mediante extracción de características visuales y modelos de aprendizaje automático.

---

## Objetivos Específicos

- Crear un dataset de imágenes de papas nativas  
- Extraer características visuales relevantes  
- Entrenar modelos de clasificación  
- Desarrollar una aplicación móvil funcional  
- Validar el sistema en condiciones reales  

---

## Metodología

Se utilizó el proceso KDD (Knowledge Discovery in Databases):

1. Selección de datos  
2. Limpieza y preprocesamiento  
3. Transformación de datos  
4. Selección del modelo  
5. Entrenamiento  
6. Evaluación  
7. Implementación  

También se utilizó el modelo de desarrollo por prototipos para la aplicación móvil.

---

## Estructura del Proyecto
Proyecto - PAPAS - AprendizajeAutomatico
│
├── Codigo - Colab
│ ├── Codigo-Extraccion-Metricas-Descriptores.ipynb
│ ├── Entrenar Modelo.ipynb
│ ├── Prueba ONNX
│ └── quitar fondo de papas.ipynb
│
├── DATA-SET_CaracteristicasExtraidas
│ └── caracteristicas_papa_nativa_atributos.csv
│
├── Imagenes - DATA-SET_PAPAS
│ ├── 1
│ ├── 2
│ ├── ...
│ └── 84


---

## Tecnologías Utilizadas

- Python  
- Google Colab  
- OpenCV  
- Scikit-learn  
- TensorFlow / Keras  
- ONNX  
- Android Studio  

---

## Dataset

El dataset está compuesto por imágenes organizadas por clases (variedades de papa), donde cada carpeta representa una categoría.

También se incluye un archivo CSV con características extraídas de las imágenes.

---

## Resultados Esperados

- Clasificación automática de variedades de papa  
- Alta precisión en reconocimiento  
- Aplicación funcional para uso en campo  

---

## Impacto

### Social
- Preservación de la cultura andina  
- Apoyo a agricultores  

### Económico
- Mejora en comercialización  
- Nuevas oportunidades de mercado  

### Ambiental
- Conservación de biodiversidad  
- Reducción de impacto ambiental  

---

## Cómo usar el proyecto

1. Clonar el repositorio:
git clone https://github.com/Zttxw/proyecto-reconocimiento-papa.git


2. Abrir los notebooks en Google Colab o Jupyter  

3. Ejecutar:
- Preprocesamiento  
- Extracción de características  
- Entrenamiento del modelo  

---

## Notas

Este proyecto tiene fines académicos y de investigación.