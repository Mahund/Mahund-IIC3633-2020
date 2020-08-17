### Item-Base Collaborative Filtering Recommendation Algorithms

#### Breve Resumen

Este paper menciona a gran escala como los Sistemas Recomendadoras han ido ganando importancia, y a la misma vez se han visto enfrentados a nuevas limitantes.

Ántes existía una falta de información para realizar correctos análisis, y por lo tanto, correctas recomendaciones. Pero hoy en día existe un volumen de información tan grande que el los principales cuellos de botella son:  
- Mejorar la escalabilidad de los algoritmos, para poder satisfacer con la demanda de, por ejemplo, buscar vecinos en KNN para millones de potenciales usuarios.
- Mejorar la calidad de las recomendaciones entregadas a cada usuario en específico.
- El esparcimiento que existe entre los millones de datos por analizar

Una problemática extra entregada es como estos desafios mencionados son de cierta forma opuestos entre si, ya que a mayor velocidad de computo, peores recomendaciones se entregan.

Frente a esto el paper presenta un experimento enfocado en un modelo basado en los elementos, revisando las relaciones entre ellos en vez de las relaciones entre los usuarios.

#### Crítica

El paper desarrolla en un formato, a mi parecer, poco claro el experimento realizado, llegando a conclusiones que no llegaron a convencerme totalmente.

Siento que el autor menciona elementos sin base a ratos, por ejemplo cuando menciona que en el experimento el modelo basado en elementos logra mejorar los desafios de performance (capacidad de analisis y calidad de recomendaciones) pero nunca menciona un comparación clara con algun modelo KNN.