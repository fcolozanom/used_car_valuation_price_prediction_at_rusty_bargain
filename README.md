# used_car_valuation_price_prediction_at_rusty_bargain

El servicio de venta de autos usados Rusty Bargain está desarrollando una aplicación para atraer nuevos clientes. Gracias a esa app, puedes averiguar rápidamente el valor de mercado de tu coche. Tienes acceso al historial: especificaciones técnicas, versiones de equipamiento y precios. Tienes que crear un modelo que determine el valor de mercado.

# Introducción:

En el contexto del mercado de vehículos usados, determinar el precio adecuado para un automóvil puede ser un desafío tanto para los vendedores como para los compradores. En este proyecto, nos enfocamos en abordar esta problemática desarrollando un modelo de machine learning capaz de predecir el valor de mercado de vehículos usados. Este modelo será implementado en una aplicación desarrollada por Rusty Bargain, una empresa dedicada a la venta de autos usados, con el objetivo de proporcionar a sus usuarios una herramienta práctica y confiable para estimar el precio de sus vehículos. Utilizando técnicas de procesamiento de datos y modelos predictivos avanzados, buscamos ofrecer una solución eficaz que no solo garantice la precisión en las predicciones, sino también la velocidad en la respuesta, brindando así una experiencia óptima a los usuarios de la aplicación.

# Observaciones

La preparación de datos aborda la carga y exploración inicial del conjunto de datos, eliminando filas con valores faltantes y dividiendo los datos en conjuntos de entrenamiento y prueba. Se identifican las características categóricas y numéricas, y se define un preprocesador para aplicar transformaciones específicas a cada tipo de característica. Además, se realizan estadísticas adicionales del conjunto de datos para comprender mejor la distribución de las características numéricas. Aunque la preparación parece completa, sería beneficioso agregar más comentarios para explicar cada paso y optimizar los modelos utilizando hiperparámetros para mejorar su rendimiento predictivo.

# Conclusiones

En la evaluación de modelos para predecir los precios de autos usados, se observó que los modelos de árbol de decisión, como CatBoost y XGBoost, superaron en calidad de predicción al modelo de regresión lineal, logrando un RMSE más bajo. El modelo de regresión lineal tuvo un RMSE de 2986.42, mientras que CatBoost y XGBoost obtuvieron un RMSE de 1627.36 y 1623.38 respectivamente. Aunque los modelos de árbol requirieron un tiempo considerablemente mayor tanto para el entrenamiento como para la predicción, su capacidad predictiva superior los hace más adecuados para esta tarea. Sin embargo, si la velocidad de predicción es una prioridad, el modelo de regresión lineal ofrece tiempos significativamente más rápidos. En resumen, la elección del modelo dependerá de la importancia relativa entre la calidad de la predicción y la eficiencia computacional requerida en el contexto específico de la aplicación.
