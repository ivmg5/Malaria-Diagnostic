# Diagnóstico de Malaria Utilizando Dielectroforesis en MATLAB

## Descripción del Proyecto

**Institución:** ITESM  
**Autores:**  
- Roberto Morales - A01642426  
- Diego Morales - A01643382  
- Edwin Iñiguez Moncada - A01637064  
- Sergio Emanuel Ramirez Anaya - A01641886  

### Problemática

Los mosquitos transmiten diversas enfermedades como fiebre amarilla, zika, chikungunya, dengue, malaria, entre otras. De estas, la malaria, también conocida como paludismo, es responsable de más del 80% de las muertes atribuidas a picaduras de mosquitos anualmente. A pesar de que la mayoría de estas muertes ocurren en África, la malaria es una realidad también en México. El diagnóstico oportuno y preciso es crucial para el tratamiento adecuado, pero determinar si un paciente tiene malaria puede ser desafiante. Es vital desarrollar técnicas efectivas de diagnóstico.

### Solución Planteada: Dielectroforesis

La **dielectroforesis** es un movimiento electrocinético de partículas causado por la polarización en un campo eléctrico no uniforme. Este fenómeno permite manipular a las partículas y puede ser empleado para separar glóbulos rojos infectados de los sanos, ya que los infectados poseen una mayor magnitud de carga eléctrica positiva, siendo atraídos por la placa negativa.

### Modelación en MATLAB

#### Proceso de la Modelación

Para simular el sistema, se modeló el campo eléctrico utilizando cargas puntuales y se basó en leyes físicas que describen la interacción entre cargas opuestas.

#### Representación de Campo Eléctrico

Se empleó la función `quiver` de MATLAB para ilustrar las cargas. Las cargas y la placa negativa se ajustan basándose en parámetros como la cantidad de cargas puntuales o el tamaño de la placa.

#### Modelado en Tres Dimensiones

Con la ayuda de `quiver3`, se visualizó el campo eléctrico en un ambiente tridimensional. Esta representación se adapta según las medidas de la placa y la cantidad de cargas introducidas.

#### Creación de la App

Con el uso de las herramientas de MATLAB, se desarrolló una aplicación interactiva que incorpora botones, sliders y check boxes, facilitando al usuario la visualización y manipulación del modelo, así como la transición entre visualizaciones 2D y 3D.

## Conclusión

El diagnóstico temprano y preciso de la malaria es esencial para evitar complicaciones y garantizar un tratamiento adecuado. Aunque los métodos actuales de diagnóstico tienen limitaciones, la innovación en técnicas y tecnologías puede ofrecer soluciones significativas. Este proyecto representa un paso hacia una herramienta de diagnóstico más efectiva y precisa, con el objetivo de mejorar la gestión y tratamiento de la malaria globalmente.

---
