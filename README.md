# Calculadora-de-Costos-de-Materiales-para-Cimientos
Opción 1: Ingeniería Civil - Calculadora de Costos de Materiales para Cimientos
•	Objetivo: Desarrollar una calculadora en Python que estime la cantidad y el costo de los materiales (cemento, arena, grava, agua) necesarios para construir un cimiento de concreto simple (zapata aislada). El programa debe ser interactivo y fácil de usar.
•	Requisitos Funcionales:
1.	Interfaz de Usuario en Consola: Un menú claro que se ejecute en un bucle, permitiendo al usuario realizar múltiples cálculos o salir.
2.	Entrada de Datos: Solicitar las dimensiones del cimiento: largo (m), ancho (m) y altura (m).
3.	Base de Datos de Costos: Usar un diccionario para almacenar los costos unitarios de los materiales (ej. {'cemento_usd_saco': 8.5, 'arena_usd_m3': 20}).
4.	Cálculos Modulares (Funciones):
	Una función para calcular el volumen del cimiento.
	Una función que, a partir del volumen, calcule la cantidad de cada material (usando una dosificación estándar, ej. para 1 m³ de concreto se necesitan 7 sacos de cemento, 0.6 m³ de arena, 0.8 m³ de grava y 0.2 m³ de agua).
	Una función que calcule el costo total del proyecto.
5.	Robustez: Usar manejo de errores (try-except) para validar todas las entradas numéricas del usuario.
6.	Salida de Resultados: Presentar un resumen claro y bien formateado que incluya el volumen total, la cantidad de cada material requerido y el costo total estimado.
