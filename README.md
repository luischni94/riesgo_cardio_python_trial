# riesgo_cardio_python_trial
# Evaluación de Riesgo Cardiovascular en Python 

Este proyecto es un ejercicio de programación funcional creado como parte de mi transición profesional desde la medicina clínica hacia la informática médica y la inteligencia artificial aplicada a la salud.

Permite ingresar datos antropométricos y de presión arterial para calcular un estimado de riesgo cardiovascular general, con validación de entradas y categorización médica básica.

## ¿Qué hace este programa?

- Solicita **peso, talla, presión arterial sistólica y diastólica**
- Calcula el **Índice de Masa Corporal (IMC)** y lo clasifica
- Evalúa si la **presión arterial está controlada**
- Determina un **nivel de riesgo cardiovascular** (bajo, moderado, alto)
- Valida que los datos sean numéricos y positivos
- Presenta los resultados de manera organizada

## Lógica médica utilizada

- **IMC**: categorización estándar (bajo peso, normal, sobrepeso, obesidad)
- **Presión arterial**: controlada si <140/90 mmHg
- **Riesgo alto**: TA no controlada **y** sobrepeso/obesidad
- **Riesgo bajo**: TA controlada **y** IMC normal o bajo
- Todo lo demás: **riesgo moderado**

## Disclaimer clínico

Este proyecto es exclusivamente educativo.  
No ha sido validado para uso diagnóstico ni clínico.  
No reemplaza el juicio profesional ni el seguimiento médico.

## Sobre mí

Soy médico colombiano en transición hacia la informática médica y la inteligencia artificial aplicada a la salud.  
Este repositorio forma parte de mi portafolio público de aprendizaje práctico en programación.
