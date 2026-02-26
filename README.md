# actuarial_pricing_ML
Este proyecto explora cómo calcular la prima "justa" de un asegurado utilizando ML en comparación con los métodos actuariales tradicionales.

Objetivos
Modelar frecuencia y severidad de siniestros con enfoques clásicos actuariales (GLM con distribuciones Poisson y Gamma).

Replicar los mismos modelos con algoritmos de ML (XGBoost, Random Forest).

Comparar desempeño, estabilidad y capacidad predictiva de ambos enfoques.

Incorporar interpretabilidad con SHAP values, requisito clave para reguladores como la SSN.

Datos
https://dutangc.github.io/CASdatasets/reference/freMTPL.html

Estructura
Actuarial baseline: GLMs de frecuencia-severidad.

ML models: entrenamiento y validación con algoritmos de boosting y ensambles.

Interpretabilidad: análisis de variables más influyentes en el riesgo.
