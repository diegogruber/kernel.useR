---
title: ML Benchmarks
author: Diego Gruber
date: '2017-07-05'
Weight: 2
slug: ml-benchmarks
categories: []
tags: []
Categories: []
Description: ''
Tags: []
---

Una charla cuyo contenido ha circulado ya por varios blogs del mundillo del machine learning sobre performance de varios algoritmos e implementaciones sobre una tarea de clasificación binaria para diferentes volúmenes de datos, siempre limitado a un tablón que cabe en memoria. Las conclusiones en esta versión actualizada no han cambiado demasiado: `xgboost`y `H2O` son los ganadores por precisión, eficiencia y escalabilidad. Random forest gana por los pelos al boosting y la regresión logística se queda lejos. El *deep learning* no parece la herramienta más adecuada para este problema. 

El código del testing y los resultados están disponibles en [este repo](https://github.com/szilard/benchm-ml). Me gustaría que en la comparación de implmentaciones de random forest se incluyera `ranger`... igual me animo con un pull request uno de estos días.