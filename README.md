# Detección de Fraude Financiero con Tarjetas de Crédito 🛡️

## Descripción del Proyecto ✏️

Este proyecto se centra en la detección de fraudes financieros con tarjetas de crédito, un tema de gran relevancia en el mundo moderno, debido al aumento de las transacciones 
electrónicas. Utilizando un conjunto de datos detallado que clasifica las transacciones como fraudulentas o legítimas, el objetivo principal es identificar patrones que distingan 
las transacciones legítimas de las fraudulentas y desarrollar herramientas eficaces para su detección.



### Tabla de Contenidos 📌


* Objetivos del Proyecto
* Origen del Dataset
* Descripción de las Variables
* Análisis Exploratorio
* Metodología de Aprendizaje Supervisado
* Resultados del Análisis No Supervisado
* Anexo
* Requisitos del Proyecto
* Instalación y Ejecución
* Estructura del Repositorio
* Contribuciones



## Objetivos del Proyecto

- Detectar patrones de fraude en función de la hora del día, la categoría y la ubicación.
- Entender las causas y mecanismos detrás de los fraudes con tarjetas de crédito.
- Identificar variables clave para la detección de fraudes.


## Origen del Dataset 🔍
Debido a la falta de conjuntos de datos completos y públicos en Argentina, se eligió un dataset internacional de Kaggle, simulando que pertenece a un Banco Argentino.

Link al Dataset: https://www.kaggle.com/datasets/kelvinkelue/credit-card-fraud-prediction



## Análisis Exploratorio 

Nuestro análisis exploratorio de datos revela varios patrones significativos en las transacciones fraudulentas. Se observa que estos fraudes tienden a concentrarse en estados como Nueva York y Pennsylvania, ubicados en la región noreste de Estados Unidos, y suelen ocurrir durante las horas nocturnas, especialmente entre las 8:00 PM y las 3:00 AM. Además, hay un aumento notable en la actividad transaccional desde noviembre, alcanzando su punto máximo en diciembre. Sin embargo, los fraudes son más frecuentes entre agosto y octubre, a pesar de que las transacciones aumentan al final del año. También se ha identificado una tendencia en la que los montos de las transacciones fraudulentas tienden a ser mayores conforme aumenta la edad del cliente. Por último, las transacciones fraudulentas en línea muestran una incidencia de montos más elevados en comparación con otras categorías, que generalmente presentan montos fraudulentos más bajos.



## Metodología de Aprendizaje Supervisado

El análisis ha demostrado que los modelos de aprendizaje supervisado son herramientas efectivas para la detección de fraudes, con el Random Forest destacándose por su robustez y precisión. Sin embargo, es esencial abordar el desbalance de clases y considerar técnicas de ajuste adicionales para optimizar la detección de fraudes. La elección del modelo final debe basarse en una combinación de precisión, interpretabilidad y capacidad de adaptación a los datos específicos.

## Análisis No Supervisado

El análisis de detección de fraude utilizando métodos de agrupamiento no supervisado, como K-Means, ha mostrado que los clusters formados no presentan una separación clara entre transacciones fraudulentas y no fraudulentas. Esto sugiere que los métodos no supervisados, en este caso, no son adecuados para detectar fraude sin una mayor transformación de datos o la incorporación de características adicionales. Para mejorar la detección, se recomienda considerar métodos supervisados, que utilizan etiquetas de fraude/no fraude, o enfoques híbridos que combinen clustering no supervisado con modelos supervisados.


## Anexo
### Notebooks de Trabajo No Utilizados en Entregas

En el repositorio, encontrarás una carpeta llamada `Anexo` que contiene notebooks y archivos de trabajo que se utilizaron durante el desarrollo pero no formaron parte de las entregas finales. Esta carpeta incluye:

- **Análisis Preliminares:** Notebooks que muestran análisis exploratorios y pruebas iniciales.
- **Modelos Experimentales:** Archivos que contienen modelos o enfoques que se probaron pero no se incluyeron en la versión final del proyecto.
- **Notas y Esbozos:** Documentos y notas de trabajo que se usaron para desarrollar ideas y estrategias durante el proyecto.

Para acceder a estos archivos, navega a la carpeta `Anexo` en la raíz del repositorio.




### Requisitos del Proyecto
Python 3.7 o superior

### Librerías 📚

<h3 align="left"></h3>
<table>
    <tr>
        <td style="font-weight: bold; padding-right: 10px; vertical-align: center; border: none;">EDA</td>
        <td><img height="40" src="https://go-skill-icons.vercel.app/api/icons?i=python,pandas,numpy,matplotlib,seaborn&titles=true"/></td>
    </tr>
    <tr>
        <td style="font-weight: bold; padding-right: 10px; vertical-align: center; border: none;">Machine Learning</td>
        <td><img height="40" src="https://go-skill-icons.vercel.app/api/icons?i=scikitlearn,jupyter&titles=true"/><img height="40" src="https://www.kdnuggets.com/wp-content/uploads/chugh_lgbmclassifier_gettingstarted_guide_1.png"/>
          <img height="40" src="https://miro.medium.com/v2/resize:fit:1190/1*yhE3CBwTrlXcAIvNJNTQiA.png"/>
        </td>
    </tr>
</table>



## **INTEGRANTES**

*   Casanova, Beverly
*   Nuñez, Lourdes
*   Cardozo, Pamela
