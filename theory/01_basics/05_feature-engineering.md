# ML Basics

## Feature engineering
Cuando empezamos a trabajar en un proyecto real, los datos que recolectamos reciben el nombre de "datos crudos". Por ejemplo:
- Meciones del clima
- Imágenes de una cámara
- Audio de grabadoras
- Fechas del calendario

La gran mayoría de los algoritmos funcionan unicamente con datos numéricos. Por tanto, a nuestros datos crudos, tenemos que aplicarle un proceso conocido como ingeniería de característas o feature engineering:
![Image4](https://firebasestorage.googleapis.com/v0/b/habacuc-javascript.appspot.com/o/images%2Fcaps%2F4.png?alt=media&token=54ce8165-b99e-4f05-8ea8-b7f7dba91f9b)
![Image5](https://firebasestorage.googleapis.com/v0/b/habacuc-javascript.appspot.com/o/images%2Fcaps%2F5.png?alt=media&token=c4714366-4c1e-4b5a-a751-6630327545fa)

Feature engineering se aplica principalmente con datos no estructurados:
- Reconocimiento de voz - sampleo en frecuencias
- Tratamiento de vídeo - dividir en frames
- Lenguaje natural - dividir en palabras

Pero también se aplica con datos estructurados:
- Variable categóricas, como la nacionalidad o el sexo
- Las diferentes formas de representar una fecha

El feature engineering es una tarea muy compleja que depende de muchos factores y se compone de muchas técnicas. Además, es importante resaltar que ningún análisis se parece al otro