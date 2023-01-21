# KaggleMetaData

## Descripción 🚀

Repositorio en el que se analizan los datos generados por la plataforma Kaggle.

Este proyecto corresponde con el proyecto final de la asignatura _Visualización de Datos_ del Máster en Ciencia de Datos de la [Universitat Oberta de Catalunya](https://www.uoc.edu/portal/en/index.html).

## Contenido 📦

Finalmente el proyecto generado se distribuye con el siguiente árbol de directorios:

```
KaggleMetaData
├── pdf
│   ├── Proyecto Final.pdf
│   └── README.md
├── data
│   ├── original
│   │   └── ...
│   ├── processed
│   │   ├── tags
│   │   ├── topDatasets
│   │   └── topUsers
│   └── README.md
├── src
│   ├── Tops.ipynb
│   ├── User_Network.ipynb
│   ├── Word_Clouds_Competitions.ipynb
│   ├── Word_Clouds_Datasets.ipynb
│   └── README.md
└── README.md
```

Dentro de estos se destacan las siguientes carpetas

* _**src**_ : Códigos que generan los diversos conjuntos de datos: la red de usuarios con diversas métricas más la información de estos (_User_Network.ipynb_), estructuras para generar nubes de palabras (_Word_Clouds_Competitions.ipynb_, _Word_Clouds_Datasets.ipynb_), los usuarios con una mayor significancia en la red e información de los conjuntos de datos con votaciones positivas (Tops.ipynb_), ...

* _**data**_ : Esta carpeta contiene diversos conjuntos de datos, los datos originales y los generados (la red de usuarios, los tags de los conjuntos de datos / de las competiciones, los usuarios con una influencia destacada, etc.

* _**pdf**_ : Carpeta donde se encuentra el documento descriptivo del proyecto.

## Datos 📋

Los datos originales utilizados pertenecen a Kaggle (y se encuentran en esta misma plataforma), [Meta Kaggle](https://www.kaggle.com/datasets/kaggle/meta-kaggle?select=ForumTopics.csv). Está formado por los metadatos de dicha plataforma y pueden ser utilizados para diferentes objetivos como por ejemplo: evaluar métricas sobre proyectos de ciencia de datos, determinar la influencia de equipos ó usuarios, y evaluar temas de interés a lo largo del tiempo. Estos datos han sido procesados y filtrados para proteger la privacidad de los usuarios y están disponibles bajo una licencia CC BY-NC-SA 4.0.

## Visualización de datos

La visualización final se desarrolló en [Flourish](https://flourish.studio/) y se puede acceder en este [enlace](https://public.flourish.studio/story/1804077/).

## Autor ✒️

* [Kevin Martín Chinea](https://www.linkedin.com/in/kevmch/)
