# ML Basics

## Conjuntos de entrenamiento, validación y pruebas
Una vez conseguido el dataset para entrenar un modelo de ML lo primero que debemos hacer es:
- Dividir nuestro dataset en 3 subconjuntos:
    - Set de entrenamiento
    - Set de validación 
    - Set de prueba

Tanto el conjunto de validación, como el de prueba, se les conoce como "Conjuntos ocultos". Esto porque esperamos un buen desempeño en datos no vistos

### Conjunto de entrenamiento
Este es el set más grande, su propósito es ser usado por el algoritmo para entrenar y producir el modelo

### Conjunto de validación
A este set también se le conoce como el set de desarrollo. Es usado por desarrolladores para decidir qué modelo usar

### Conjunto de pruebas
El set de pruebas es usado para medir qué tan bueno es el modelo entrenado. Este conjunto es el que se debe usar para la toma de decisiones. Con este conjunto, se decide si el modelo es lo suficientemente bueno, como para ponerlo en producción

### Cómo se decide el tamaño ideal de cada set?
No existe una respuesta clara porque depende de muchos factores
![Image6](https://firebasestorage.googleapis.com/v0/b/habacuc-javascript.appspot.com/o/images%2Fcaps%2F6.png?alt=media&token=b761c1fc-20ef-474c-b667-eb3b91b85de1)

Lo que se debe considerar es:
1. El set de entrenamiento es generalmente el set más grande
2. El set de pruebas debe lo suficientemente representativo de lo que vamos a encontrar en producción

Puedes usar las siguientes guías para definir los tamaños de set:
![Image7](https://firebasestorage.googleapis.com/v0/b/habacuc-javascript.appspot.com/o/images%2Fcaps%2F7.png?alt=media&token=82b9e47b-9422-42a5-8fb5-a4ebcec6e86a)

Cuando no se tiene una cantidad suficiente de información, suele suceder que el conjunto de validación es omitido, favoreciendo otras técnias como la validación cruzada
![Image8](https://firebasestorage.googleapis.com/v0/b/habacuc-javascript.appspot.com/o/images%2Fcaps%2F8.png?alt=media&token=6f36f9b1-f66a-4c4c-982f-62ee3e05faba)