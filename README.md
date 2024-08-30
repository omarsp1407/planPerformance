# Análisis de Tarifas de Prepago de Megaline

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar y comparar la rentabilidad de dos tarifas de prepago ofrecidas por Megaline: Surf y Ultimate. Usando datos de 500 clientes, se evaluará cuál de las tarifas genera más ingresos y se proporcionarán recomendaciones sobre el presupuesto de publicidad basado en el comportamiento de los clientes.

## Objetivos del Proyecto

1. **Evaluar la Rentabilidad de las Tarifas**: Determinar cuál de las tarifas, Surf o Ultimate, genera más ingresos en promedio.
2. **Analizar el Comportamiento del Cliente**: Identificar el uso de minutos de llamada, mensajes SMS y volumen de datos para cada tarifa.
3. **Prueba de Hipótesis**: Realizar pruebas estadísticas para comparar ingresos promedio entre las tarifas y entre regiones.

## Descripción de las Tarifas

- **Surf**:
  - **Pago mensual**: $20
  - **Incluye**: 500 minutos, 50 SMS, 15 GB de datos
  - **Tarifas adicionales**:
    - $0.03 por minuto extra
    - $0.03 por SMS extra
    - $10 por GB extra

- **Ultimate**:
  - **Pago mensual**: $70
  - **Incluye**: 3000 minutos, 1000 SMS, 30 GB de datos
  - **Tarifas adicionales**:
    - $0.01 por minuto extra
    - $0.01 por SMS extra
    - $7 por GB extra

## Datos Utilizados

El proyecto utiliza las siguientes tablas:

1. **users**: Información sobre los usuarios (ID, nombre, edad, fecha de suscripción, etc.).
2. **calls**: Datos sobre las llamadas realizadas (duración, fecha, ID del usuario).
3. **messages**: Información sobre los mensajes SMS enviados (fecha, ID del usuario).
4. **internet**: Datos sobre el uso de datos móviles (volumen de datos, fecha, ID del usuario).
5. **plans**: Detalles sobre las tarifas (nombre, cuota mensual, minutos incluidos, SMS incluidos, datos incluidos, precios adicionales).

## Pasos del Proyecto

### Paso 1: Preparación de Datos

- **Carga y estudio de datos**: Importar y revisar los archivos de datos.
- **Conversión de tipos de datos**: Asegurar que los datos estén en el formato correcto.
- **Limpieza de datos**: Identificar y corregir errores en los datos.

### Paso 2: Cálculo de Ingresos Mensuales

- **Número de llamadas y minutos utilizados**: Calcular el número total de llamadas y minutos por usuario al mes.
- **Cantidad de SMS enviados**: Determinar el total de mensajes SMS enviados por mes.
- **Volumen de datos por mes**: Calcular el volumen de datos utilizados mensualmente.
- **Cálculo de ingresos mensuales**: Estimar los ingresos basados en el uso excedido y la tarifa mensual.

### Paso 3: Análisis de Datos

- **Comportamiento del cliente**: Analizar minutos, SMS y datos utilizados por mes.
- **Cálculo de estadísticas descriptivas**: Media, varianza y desviación estándar.
- **Visualización**: Traza histogramas y describe las distribuciones de los datos.

### Paso 4: Pruebas de Hipótesis

- **Hipótesis sobre ingresos**: Comparar el ingreso promedio entre las tarifas Surf y Ultimate.
- **Hipótesis sobre regiones**: Comparar ingresos promedio entre usuarios en Nueva York-Nueva Jersey y otras regiones.
- **Determinación del valor alfa**: Establecer el umbral de significancia para las pruebas estadísticas.
- **Formulación de hipótesis y criterios de prueba**: Definir hipótesis nula y alternativa y criterios para las pruebas.

## Instrucciones de Ejecución

1. **Abrir archivos de datos**: Cargar los archivos desde las rutas proporcionadas.
2. **Preparar datos**: Convertir y limpiar los datos.
3. **Calcular ingresos y analizar datos**: Ejecutar cálculos y realizar análisis descriptivo.
4. **Realizar pruebas estadísticas**: Probar las hipótesis y presentar los resultados.

## Recursos

- **Datos**: Archivos CSV con datos sobre llamadas, mensajes, internet, planes y usuarios.
- **Código**: Cuaderno de Jupyter con celdas de código y Markdown para el análisis.

## Conclusión

Este proyecto proporcionará una visión clara sobre cuál tarifa de prepago es más rentable para Megaline y ayudará a orientar las decisiones estratégicas en publicidad y ajuste de tarifas.

---

Para más detalles sobre la implementación, consulte el cuaderno de Jupyter incluido en este repositorio. ¡Gracias por revisar el proyecto!
