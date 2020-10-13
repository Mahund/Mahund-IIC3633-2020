### Multi-armed recommender system bandit ensembles

#### Resumen

La lectura nos presenta el concepto de _Ensembles Methods_. Explica como se basa en utilizar un grupo de sistemas recomendadores (modelos como los vistos anteriormente) y entregar la mejor predicción entregada por ellos.

A parte de explicar el funcionamiento de estos grupos de modelos, se nos presentan sus problemas, principalmente la escalabilidad. Por obviedad que parezca, a medida que aumentan los datos, como estos deben ser procesados por cada modelo en separado, aumenta exponencialmente su tiempo de procesamiento.

Frente a esto se presenta un nuevo sistema, el _Multi-armed Recommender System_, reemplazando esta "repetición" de datos en cada modelo, por una elección de modelo. Dependiendo de los rendimientos anteriores se decide que modelo usar con la nueva data, asi evitando este crecimiento excesivo en procesamiento.

#### Crítica

Me gustó mucho la idea de elección por eficiencia. Me parecia un poco burdo que un sistema mixto termine siendo poco escalable debido a lo mencionado anteriormente, por lo que la "solución" entregada me parecio muy intuitiva y clara.

Pese a esto me parece un poco raro que modelos como "Most Popular" fuese tan eficiente por lo visto, generandome dudas de si la métrica utilizada será la adecuada