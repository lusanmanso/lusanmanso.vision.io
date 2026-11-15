# ¡Bienvenidos a la Competición de CNNs 2026!

El objetivo principal de esta competición es alcanzar el F1-score más alto posible, demostrando tu destreza en la construcción y evaluación de modelos. El F1-score es una métrica fundamental que mide la precisión y la exhaustividad (recall) de tus predicciones, buscando el equilibrio perfecto entre acertar y evitar errores.

## Normas de Participación y Dataset

- **Grupos:** La participación únicamente será posible en grupos de 3 a 4 personas.
- **Dataset proporcionado:** `cards.zip` (disponible en la entrega).
- **Temática y categorías:** Las características de la clasificación o qué objetos se clasifican se deja a elección de los participantes.
  > **Nota:** Se recomienda evitar soluciones triviales (ej. "tiene color rojo / no tiene color rojo"). Cada tipo de clasificación se considerará una categoría distinta.

### Reglas sobre las imágenes y particiones

- En caso de necesitar reorganizar las imágenes dentro de cada conjunto de datos (sin mover imágenes entre particiones) para realizar otro tipo de clasificación, se deberá entregar el conjunto de datos completo ya reorganizado.
- En ningún caso se podrán eliminar imágenes de cualquiera de las tres particiones.
- Se permite el uso de data augmentation, redimensionamiento y otras modificaciones de preprocesamiento.

## Sistema de Puntuación y Premios

### Puntos por Competición (hasta 3 puntos extra)

- **Ganador de cada categoría:** 3 puntos.
- **Clasificación general (primeros puestos):**
  - 1er puesto: 3 puntos.
  - 2do puesto: 2 puntos.
  - 3er puesto: 1 punto.
- **Desempate:** En caso de empate en el F1-score, se analizarán las tasas de falsos positivos (FP) y falsos negativos (FN) para determinar al ganador.

### Evaluación de la Práctica (7 puntos restantes)

El resto de los participantes no recibirán puntos extra de competición, pero los 7 puntos restantes de la nota corresponden a la implementación en Python con PyTorch del modelo CNN y su respectiva memoria.

## Estructura de la Memoria (.pdf)

La estructura propuesta es orientativa y podéis incluir otra información si lo consideráis oportuno:

1. **Temática y características de la clasificación realizada y su justificación:**
   - a. ¿Qué objetos habéis decidido clasificar? ¿Por qué?
   - b. ¿Qué tipo de clasificación se ha aplicado? ¿Por qué?
   - c. ¿Se han realizado modificaciones al dataset? Indica cuáles y por qué.
2. **Decisiones en cuanto a la arquitectura de la CNN:**
   - a. ¿Cuántas capas tiene vuestro modelo? ¿Por qué?
   - b. ¿Qué modificaciones habéis introducido? ¿Por qué?
   - c. Justificación de las métricas, función de pérdida (loss) y optimizador.
3. **Metodología y resultados (incluyendo gráficas de rendimiento):**
   - a. Hiperparámetros y selección de estos.
   - b. Resultado de las métricas seleccionadas.
   - c. Gráficas de resultados.

## Requisitos de Entrega

La entrega deberá ser subida por una sola persona de cada grupo e incluir:

- **Archivo de código (.ipynb):** Con todo el código utilizado.
- **Memoria / Documentación (.pdf):**
  - Debe incluir el nombre de cada integrante del grupo.
  - Debe mostrar los resultados obtenidos.
  - Debe justificar debidamente la elección de los métodos utilizados, los valores seleccionados para los parámetros y los resultados.
- **Modelo entrenado:** Deberá entregarse siempre.
- **Dataset reorganizado:** Se entregará solo cuando corresponda (si se ha modificado la estructura de clases original).

## Advertencias y Recomendaciones

### Uso de LLMs y Plagio

- El uso de modelos de lenguaje (LLMs), tanto para la generación de código como de texto, será penalizado y puede requerir defensa presencial. Solo se permite su utilización para la corrección gramatical.
- El falseamiento de resultados será gravemente penalizado.
- En caso de emplear código o información procedente de alguna fuente externa, se recomienda encarecidamente indicar dicha fuente.

### Hardware

Se recomienda el uso de Google Colab para aquellos participantes que tengan problemas o limitaciones con su GPU local.
