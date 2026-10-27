# Trabajo Integrador: concentración delictiva urbana

## Qué propuse

Propuse un sistema sencillo que pueda leer distintas bases públicas de hechos denunciados, ordenar los datos y mostrar en qué combinaciones de zona y tiempo se repiten más ciertos hechos.

La profe consideró que la propuesta estaba bien planteada. Después revisó la forma de crear la variable `nivel_concentracion` y aprobó usar terciles, con una aclaración sobre qué quiere decir “alto”.

## Cómo definí la unidad de análisis

Primero agrupé los registros por:

- zona;
- día de la semana;
- franja horaria;
- mes;
- tipo de hecho.

Cada combinación de esos datos es una unidad de análisis. Después conté cuántos registros había en cada combinación y usé esos conteos para ordenar las combinaciones en tres grupos:

- tercil inferior: `bajo`;
- tercil del medio: `medio`;
- tercil superior: `alto`.

“Alto” significa que esa combinación está en el tercio superior comparada con las demás combinaciones analizadas. No significa necesariamente que allí ocurra la mayoría absoluta de los delitos. La cantidad de registros sirve para crear la etiqueta; no la usaría también como variable de entrada del modelo, porque sería darle la respuesta de antemano.

## Qué datos necesita cada archivo

La propuesta puede trabajar con archivos de distintas fuentes si se pueden relacionar con estos campos básicos:

- fecha del hecho;
- hora o franja horaria;
- zona, barrio, comuna o departamento;
- tipo de hecho;
- cantidad de hechos o registros individuales.

Si los nombres de las columnas cambian entre archivos, primero tendría que pasarlos a un formato común. La primera fuente sugerida en mi propuesta fue Buenos Aires Data; como alternativa mencioné las estadísticas criminales de Datos Argentina.

## Pasos que propuse

1. Descargar una base pública y conservar el archivo original.
2. Revisar y limpiar fechas, horas, valores faltantes, duplicados y nombres de columnas.
3. Crear las variables de día, mes y franja horaria.
4. Agrupar los registros y crear `nivel_concentracion` con los terciles.
5. Probar una clasificación básica de bajo, medio y alto.
6. Revisar los resultados con una matriz de confusión, accuracy, precisión y recall, y explicar las limitaciones.

## Cuidado con la interpretación

Los datos representan denuncias y pueden tener subregistro. Una zona con más denuncias no necesariamente es “peor”. La propuesta analiza patrones históricos agregados: no identifica personas, no predice delitos individuales y no recomienda vigilancia automatizada.

## Estado

En los correos, la profe aprobó la propuesta y la definición de la variable. Este archivo resume esas decisiones. No afirma que el sistema completo, el modelo ni los resultados esperados ya estén implementados.
