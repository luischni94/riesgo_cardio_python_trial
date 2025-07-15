# riesgo_cardio_python_trial
# Evaluación de Riesgo Cardiovascular en Python 

Este proyecto es un ejercicio de programación funcional creado como parte de mi transición profesional desde la medicina clínica hacia medicina informatica

Permite ingresar datos antropométricos y de presión arterial para calcular el riesgo cardiovascular general de una persona, con validación de entradas y categorización médica básica.

## ¿Qué hace este programa?

- Solicita **peso, talla, presión arterial sistólica y diastólica**
- Calcula el **Índice de Masa Corporal (IMC)** y lo clasifica
- Evalúa si la **presión arterial está controlada**
- Determina un **nivel de riesgo cardiovascular** (bajo, moderado, alto)
- Valida que los datos sean numéricos y positivos
- Presenta los resultados de manera organizada

##  Lógica médica utilizada

- IMC: categorización estándar (bajo peso, normal, sobrepeso, obesidad)
- Tensión arterial: controlada si <140/90
- Riesgo alto si hay TA no controlada **y** sobrepeso/obesidad
- Riesgo bajo si hay TA controlada **y** IMC normal o bajo
- Todo lo demás es riesgo moderado

##  Disclaimer clínico

Este proyecto es exclusivamente educativo.  
No está validado para uso diagnóstico ni clínico.  
No reemplaza el juicio profesional ni el seguimiento médico.

## 🧠 Sobre mí

Soy un médico colombiano en proceso de transición hacia un doctorado en biociencias con énfasis en inteligencia artificial.  
Este repositorio es parte de mi portafolio público de aprendizaje práctico en programación.

