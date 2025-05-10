Predicción Binaria de Diabetes – Proyecto Final
i. Problema a resolver
El objetivo de este proyecto es desarrollar un modelo de clasificación binaria que permita predecir si una persona tiene o está en riesgo de tener diabetes (prediabetes o diabetes), con base en variables relacionadas a su salud y estilo de vida. Esta predicción puede ser útil para implementar medidas preventivas y apoyar decisiones médicas en etapas tempranas.

ii. Dataset utilizado
Fuente: Encuesta BRFSS 2015 del CDC (disponible en Kaggle).

Cantidad de observaciones: 253,680 personas encuestadas.

Cantidad de variables: 22 variables totales, al menos 18 categóricas.

Target original: Diabetes_012 con tres clases:

0 = No diabetes o solo durante embarazo

1 = Prediabetes

2 = Diabetes

Target binario utilizado: Diabetes_binary:

0 = No diabetes

1 = Prediabetes o diabetes (agrupadas)


iii. Modelo final

Modelo utilizado: Regresión Logística

Features seleccionadas:


editar despues


Tratamiento aplicado:

- Variables categóricas transformadas con one-hot encoding.
- Selección de variables mediante correlación, importancia de coeficientes, y Weight of Evidence (WoE) con Information Value (IV).


Métricas del modelo final:

editar despues


