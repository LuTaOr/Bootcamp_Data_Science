# Purchase Intention Prediction in an Online Store

## Project Description
This project aims to predict user purchase intentions in an e-commerce platform based on interaction data. Using Machine Learning and Deep Learning, models were developed to classify whether a user will make a purchase (class 1) or not (class 0).

The main objective is to provide the store managers (such as Manuel, the business owner in this case) with actionable insights to implement personalized marketing and discount strategies, optimizing resources and increasing conversions.

---

## Repository Structure
- **`data/`**  
  Contains the original dataset and preprocessed datasets used in the project.

- **`notebooks/`**  
  Notebooks with exploratory analyses, feature selection, and training of Machine Learning and Deep Learning models.

- **`pipelines/`**  
  Code for the pipelines used for data preprocessing, applying balancing techniques (like SMOTE), and training.

- **`model/`**  
  Trained models stored in `.pkl` format for Machine Learning and `.keras` for Deep Learning.

- **`images/`**  
  Images and graphs generated during the project.

- **`README.md`**  
  This project description file.

---

## Technologies Used
- **Python 3.10**
  - Main libraries:
    - `scikit-learn`
    - `imbalanced-learn`
    - `tensorflow`
    - `matplotlib`
    - `seaborn`
    - `pandas`
    - `numpy`

---

## Project Pipeline
1. **Data Loading:**  
   Data on user interactions in the e-commerce platform, featuring 18 attributes including administrative, informational, and product details.

2. **Preprocessing:**  
   - Transformation of categorical variables using `OneHotEncoder`.
   - Normalization of numerical data between -1 and 1.
   - Reduction of irrelevant features.

3. **Class Balancing:**  
   - Application of SMOTE to balance the imbalanced classes in the training set.

4. **Model Training:**  
   - **Machine Learning:** Models such as SVM, Random Forest, XGBoost, and Logistic Regression.
   - **Deep Learning:** Neural networks with multiple dense layers and regularization techniques (BatchNormalization and Dropout).

5. **Model Evaluation:**  
   - Key metrics: **Balanced Accuracy**, **Class 1 Recall**, and **Confusion Matrix**.
   - Class 1 Recall was prioritized to minimize misclassification of potential buyers.

---

## Results
### Machine Learning Models
- **Selected Model:** SVM with **SMOTE** applied.  
  - Class 1 Recall: **0.86**  
  - Balanced Accuracy: **0.86**  

### Deep Learning Models
- Architecture with three dense layers and regularization.  
  - Best Class 1 Recall: **0.79**.  

---

## Conclusions
- The application of techniques like Feature Reduction and SMOTE improves Class 1 Recall, enabling better identification of potential buyers.
- The system can be integrated into production to offer personalized promotions in real-time.

---

# Predicción de Intención de Compra en un Comercio Online

## Descripción del Proyecto
Este proyecto busca predecir la intención de compra de usuarios en un comercio electrónico a partir de datos de interacción con la plataforma web. Utilizando Machine Learning y Deep Learning, se desarrollaron modelos que clasifican si un usuario realizará una compra (clase 1) o no (clase 0).

El objetivo principal es proporcionar a los responsables del comercio (como Manuel, el dueño del negocio en este caso) información útil para implementar estrategias personalizadas de marketing y descuentos, optimizando recursos y aumentando las conversiones.

---

## Estructura del Repositorio
- **`data/`**  
  Contiene el dataset original y los datasets preprocesados utilizados en el proyecto.
  
- **`notebooks/`**  
  Notebooks con los análisis exploratorios, selección de características y entrenamiento de los modelos de Machine Learning y Deep Learning.
  
- **`pipelines/`**  
  Código de los pipelines utilizados para el preprocesamiento de los datos, aplicación de técnicas de balanceo (como SMOTE) y entrenamientos.

- **`model/`**  
  Modelos entrenados almacenados en formato `.pkl` para Machine Learning y `.keras` para Deep Learning.

- **`images/`**  
  Imágenes y gráficas generadas durante el proyecto.

- **`README.md`**  
  Este archivo de descripción del proyecto.

---

## Tecnologías Utilizadas
- **Python 3.10**
  - Librerías principales:
    - `scikit-learn`
    - `imbalanced-learn`
    - `tensorflow`
    - `matplotlib`
    - `seaborn`
    - `pandas`
    - `numpy`

---

## Pipeline del Proyecto
1. **Carga de Datos:**  
   Se utilizan datos sobre las interacciones de los usuarios en el comercio electrónico, con 18 características, incluyendo información administrativa, informativa y de productos.

2. **Preprocesamiento:**  
   - Transformación de variables categóricas con `OneHotEncoder`.
   - Normalización de datos numéricos entre -1 y 1.
   - Reducción de características irrelevantes.

3. **Balanceo de Clases:**  
   - Aplicación de SMOTE para equilibrar las clases desbalanceadas en el conjunto de entrenamiento.

4. **Entrenamiento de Modelos:**  
   - **Machine Learning:** Modelos como SVM, Random Forest, XGBoost y Logistic Regression.
   - **Deep Learning:** Redes neuronales con múltiples capas densas y técnicas de regularización (BatchNormalization y Dropout).

5. **Evaluación de Modelos:**  
   - Métricas principales: **Balanced Accuracy**, **Recall de la clase 1** y **Confusion Matrix**.
   - Se priorizó el Recall de la clase 1 para minimizar la cantidad de compradores potenciales mal clasificados.

---

## Resultados
### Modelos de Machine Learning
- **Modelo seleccionado:** SVM con **SMOTE** aplicado.  
  - Recall de la clase 1: **0.86**  
  - Balanced Accuracy: **0.86**  

### Modelos de Deep Learning
- Arquitectura con tres capas densas y regularización.  
  - Mejor Recall de la clase 1: **0.79**.  

---

## Conclusiones
- La aplicación de técnicas como Feature Reduction y SMOTE mejora el Recall de la clase 1, permitiendo identificar más compradores potenciales.
- El sistema puede integrarse en producción para ofrecer promociones personalizadas en tiempo real.

---



