# Respuestas de las prácticas

## Módulo I

### Pregunta inicial

**¿Por qué importa la ciencia de datos y dónde se puede aplicar?**

Para mí, sirve para encontrar patrones y responder preguntas usando información, en vez de decidir solamente por intuición. Se puede aplicar en salud, transporte, educación, comercios y muchos otros sectores.

### Actividad: datos que veo a mi alrededor

Elegí como ejemplo el tiempo de espera del colectivo. Podría anotar el día, la línea, la hora en que llegué y la hora en que pasó. No anotaría información de otras personas.

La pregunta sería: ¿en qué horario espero más tiempo? Antes de medirlo, pienso que puede ser en hora pico, pero tendría que comprobarlo con los datos.

### Preguntas de la unidad

1. **Diferencia entre analista y científico de datos:** el analista suele describir lo que pasó y presentar resultados. El científico de datos también puede programar y probar modelos para estimar qué podría pasar. En la práctica, algunas tareas se mezclan.
2. **Habilidades de un científico de datos:** se combinan programación, matemática y estadística, conocimiento del tema o negocio, curiosidad y comunicación. También hace falta explicar qué significan los resultados.
3. **Caso de LinkedIn:** Jonathan Goldman vio patrones en los perfiles y conexiones. Como el equipo de ingeniería no estaba convencido, probó sus sugerencias en pequeños anuncios dentro de la página. La gente hizo clic y, con ese resultado, pudo mostrar que la idea servía.
4. **Por qué conocer el negocio:** ayuda a entender qué problema se quiere resolver y qué datos realmente sirven. Por ejemplo, en salud no alcanza con calcular una cantidad: primero hay que entender qué significa una readmisión para el hospital o para el paciente.
5. **Oportunidades y desafíos:** hay oportunidades porque muchas organizaciones trabajan con datos. El desafío es que hace falta seguir aprendiendo, entender el tema del proyecto y poder explicar los resultados.
6. **Cómo explicar hallazgos:** usaría palabras comunes, un gráfico claro y un ejemplo. También diría qué no se puede concluir y qué limitaciones encontré.
7. **Cómo mantenerse actualizado:** practicaría con proyectos chicos, leería material nuevo y conversaría con otras personas del área. Me parece útil aprender varias herramientas porque el trabajo puede cambiar.

### Glosario del módulo I

1. **Dato:** información que se registró, como una fecha o una medida.
2. **Ciencia de datos:** trabajo que combina datos, programación y estadística para responder preguntas.
3. **Analista de datos:** persona que revisa datos y comunica qué muestran.
4. **Científico de datos:** profesional que puede analizar datos y construir soluciones o modelos.
5. **Big data:** conjuntos de datos tan grandes o variados que requieren herramientas adecuadas para procesarlos.
6. **Inteligencia de negocios:** uso de datos e informes para entender qué pasó y apoyar decisiones.
7. **Dato estructurado:** dato organizado en un formato claro, como una tabla.
8. **Computación en la nube:** uso de servidores y servicios por Internet.
9. **Aprendizaje automático:** técnicas que permiten que un programa encuentre patrones en ejemplos.
10. **Ética de datos:** cuidado de la privacidad, la calidad y el uso justo de los datos.

## Módulo II

### Pregunta inicial: comunicación con el cliente

Primero preguntaría qué problema quiere resolver el cliente. Después explicaría qué datos usé, qué pasos seguí y qué resultado obtuve. También diría los límites del análisis y le preguntaría si la respuesta le sirve para su objetivo.

### Marca personal

1. **Qué es:** para mí, es la idea que otras personas se forman sobre mi trabajo. En ciencia de datos la mostraría con proyectos claros, código que se pueda revisar y explicaciones sencillas.
2. **Cómo se forma:** influye lo que digo, pero también si cumplo lo que prometo, cómo trabajo con otras personas y si explico mis errores con honestidad.
3. **Para qué sirve:** puede ayudar a mostrar en qué temas tengo experiencia y a que me encuentren para un trabajo o proyecto.
4. **Cómo construir credibilidad:** no exageraría lo que sé. Mostraría los pasos, las fuentes, los resultados y las limitaciones.
5. **Pasos que seguiría:** elegiría los temas que me interesan, armaría algunos proyectos, los explicaría de manera clara y trataría de mantener una comunicación coherente.
6. **Autonomía y emprendimiento:** una marca clara puede ayudar a que un cliente entienda qué servicio puedo ofrecer. Eso puede abrir oportunidades para trabajar por cuenta propia.

### Actividades sobre datos

1. **Relevancia:** elegí Iris para revisar si las medidas de una flor ayudan a distinguir su especie. Tiene las medidas y la clase de cada registro. El archivo de UCI es fácil de conseguir; medir nuevas flores sería más lento porque habría que usar el mismo criterio y las mismas unidades.
2. **Estadística descriptiva:** en `notebooks/iris_modulo_ii.ipynb` revisé el tamaño, los tipos de columnas, los promedios, los valores mínimos y máximos, los conteos por especie y un gráfico. La conclusión es inicial: el largo promedio del pétalo cambia entre las tres especies.
3. **Datos faltantes:** revisé los valores vacíos y no encontré faltantes. Por eso no reemplacé datos. Si aparecieran, primero revisaría cuántos son y si afectan una variable importante; después decidiría si conviene completar o quitar algunos registros.
4. **Caso práctico y fuente:** usaría el caso de identificar la especie de una flor a partir de sus medidas. La fuente es el repositorio UCI. Para reunir nuevos datos anotaría largo y ancho del sépalo y del pétalo, la especie y la unidad utilizada.
5. **Caso de IBM y datos no disponibles:** el caso analiza readmisiones de pacientes y no tenía desde el inicio datos sobre medicamentos. Yo continuaría con los datos disponibles, dejando escrito qué información falta. Si el modelo muestra que ese dato cambia mucho el resultado, intentaría conseguirlo; si el análisis sigue siendo razonable, no esperaría para empezar.

## Módulo III

### Pregunta inicial: fuente, calidad y relevancia

Primero miraría si la fuente permite responder la pregunta del proyecto. Después revisaría quién juntó los datos, cuándo, qué significan las columnas, si hay valores faltantes o repetidos y si los registros representan el tema que quiero analizar. También tendría en cuenta los permisos de uso.

### Glosario del módulo III

1. **Eficacia:** lograr el objetivo.
2. **Eficiencia:** usar los recursos sin desperdiciarlos.
3. **Framework:** marco que organiza un trabajo y ofrece herramientas o reglas para avanzar.
4. **Waterfall:** forma de trabajar por etapas que se completan una después de la otra.
5. **Agile:** manera de trabajar en partes cortas y ajustar el plan con comentarios.
6. **Iteración:** ciclo corto de trabajo que se puede repetir y mejorar.
7. **Scrum:** framework ágil donde un equipo organiza el trabajo en ciclos cortos.
8. **Kanban:** forma visual de ordenar tareas y limitar cuántas quedan en curso.
9. **Extreme Programming (XP):** método de trabajo ágil que pone mucho énfasis en la calidad del código y las pruebas.
10. **Habilidades blandas:** capacidades para comunicarse, colaborar y resolver problemas con otras personas.

## Módulo IV

### Preguntas iniciales sobre IoT

1. **Uso en mis proyectos:** hasta ahora no trabajé con datos de dispositivos IoT. Para este ejercicio entendí que podría usarlos si recibiera datos de sensores, como temperatura o ubicación, y los juntara con otras variables.
2. **Desafíos:** puede haber cortes de conexión, datos repetidos, horarios distintos o información sensible. Revisaría los datos, ordenaría las fechas, controlaría duplicados y limitaría el acceso a información privada.

### Preguntas de la unidad

1. **Qué es IoT:** es una red de objetos físicos conectados que recogen y comparten datos. Una característica importante es que pueden enviar información sin que una persona tenga que cargarla manualmente.
2. **Cómo se usan esos datos:** los sensores registran información y luego se la puede almacenar y analizar junto con otros datos. En mis proyectos todavía no usé datos reales de IoT.
3. **Desafíos:** puede faltar conexión, haber medidas incorrectas o recibirse muchos datos a la vez. Revisaría formatos y fechas, buscaría registros duplicados y controlaría la calidad.
4. **Aplicaciones:** se puede usar en una casa para medir energía, en salud para seguir algunas mediciones de un paciente o en transporte para conocer la ubicación de vehículos.
5. **Privacidad y seguridad:** un dispositivo puede recoger información personal. Se deberían pedir los permisos necesarios, guardar solo lo que hace falta y proteger el acceso.
6. **Regresión logística:** es un modelo que estima la probabilidad de una respuesta de categorías, por ejemplo sí o no. Podría usarse para estimar si un paciente tiene riesgo de volver al hospital.
7. **Árbol de decisión:** ordena preguntas y reglas en ramas. Se puede usar para clasificar datos, y sus pasos suelen ser más fáciles de explicar que los de otros modelos.
8. **Matriz de confusión:** es una tabla que compara las respuestas reales con las que predijo el modelo. Sirve para contar aciertos y errores por clase.
9. **Jupyter:** permite mezclar código, texto y gráficos en un mismo archivo, y ejecutar partes por separado. Como desventaja, puede ser confuso si las celdas se ejecutan en distinto orden.
10. **Función para describir variables numéricas:** usé `describe()` de pandas dentro de una función. `def` es la palabra con la que empieza una función en Python; así puedo guardar esos pasos y volver a usarlos. En el notebook quedó este ejemplo:

    ```python
    def describir_numericas(datos):
        return datos.describe()

    print(describir_numericas(df))
    ```

### Proyecto práctico Titanic

El módulo IV propone practicar con los datos de pasajeros del Titanic. En el notebook cargué el CSV, revisé las filas, columnas y valores faltantes, y comparé cuántas personas sobrevivieron.

Para la limpieza completé las edades faltantes con la mediana. También pasé `Sex` a números y creé `FlagSolo` para indicar si una persona viajaba sola. Después comparé una Regresión Logística y un Árbol de Decisión con una matriz de confusión.

La variable que intenté predecir fue `Survived`. Las variables que usé fueron sexo, edad, clase del pasaje y si viajaba sola. Este ejercicio es para repasar el módulo IV; no forma parte del Trabajo Integrador de concentración delictiva.

### Glosario del módulo IV

1. **IoT:** dispositivos físicos conectados que recopilan o comparten datos.
2. **Sensor:** componente que mide algo, como temperatura o movimiento.
3. **Variable:** columna que describe una característica de cada registro.
4. **Clase:** categoría que queremos distinguir, como la especie de una flor.
5. **Análisis exploratorio:** primera revisión para conocer datos, errores, patrones y valores.
6. **Estadística descriptiva:** cálculos que resumen los datos.
7. **Dato faltante:** valor que no está registrado.
8. **Clasificación:** tarea de asignar un registro a una categoría.
9. **Regresión logística:** modelo que calcula probabilidades para clasificar en categorías.
10. **Matriz de confusión:** tabla que muestra aciertos y errores de un modelo.

