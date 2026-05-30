# Simulación de un Sistema Bancario

## Descripción

Este proyecto desarrolla una simulación de atención bancaria utilizando un modelo de colas M/M/1. El objetivo es analizar el desempeño de los cajeros del Banco de Colombia y determinar cuál configuración ofrece menores tiempos de espera para los usuarios.

Se simularon operaciones de retiros y pagos durante jornadas de 8 horas, considerando diferentes tipos de usuarios y ejecutando 10 réplicas independientes para obtener resultados confiables.

## Objetivos

* Identificar el cajero con menor y mayor tiempo promedio de atención.
* Calcular el promedio de usuarios por tipo.
* Analizar el comportamiento de los usuarios en cada réplica.
* Determinar si es necesario agregar un nuevo cajero.
* Comparar diferentes configuraciones de atención.

## Tecnologías Utilizadas

* Python 3
* NumPy
* Pandas
* Matplotlib
* Google Colaboratory

## Escenarios Evaluados

1. Tres cajeros mixtos.
2. Un cajero para retiros y dos para pagos.
3. Dos cajeros para retiros y uno para pagos.
4. Cuatro cajeros mixtos.

## Resultados Principales

* El escenario mixto obtuvo un tiempo promedio de espera de **0.40 minutos**.
* Las configuraciones exclusivas para pagos y retiros aumentaron los tiempos de espera.
* El escenario con cuatro cajeros presentó la menor espera (**0.09 minutos**), pero la mejora no justifica la incorporación de un nuevo cajero.

## Conclusión

La mejor alternativa para el Banco de Colombia es mantener **tres cajeros mixtos**, ya que esta configuración ofrece un excelente equilibrio entre tiempo de espera, nivel de servicio y aprovechamiento de recursos.

## Archivos Generados

* `resultados_problema_bancario.xlsx`
* `grafica_usuarios_por_tipo.png`
* `grafica_tiempo_por_cajero.png`
* `grafica_comparacion_escenarios.png`



Marlon Monterrosa Muñoz
Rafael de jesus Gonzales Ayala
Yimy Antonio Mosquera Asprilla 
Ingeniería de Software y Datos
