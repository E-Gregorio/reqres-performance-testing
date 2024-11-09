# Reqres API Performance Testing

Este proyecto tiene como objetivo realizar pruebas de rendimiento a la API de Reqres. Utilizando JMeter, se llevan a cabo pruebas de carga y análisis de rendimiento para evaluar la capacidad de la API al manejar múltiples solicitudes simultáneas.

## Descripción

- El **Test Plan** incluido en este repositorio está diseñado para simular una carga realista sobre los endpoints de la API Reqres.
- Se configuran pruebas de rendimiento para evaluar la latencia, tiempos de respuesta, y la estabilidad de la API.
- Los resultados de las pruebas se guardan en el directorio `results`, donde se pueden analizar para determinar el rendimiento de la API bajo diferentes condiciones de carga.

## Pruebas realizadas

1. **Pruebas de Carga**: Validar cómo la API maneja un número creciente de solicitudes.
2. **Pruebas de Resistencia**: Ejecutar pruebas durante períodos prolongados para evaluar la estabilidad de la API.
3. **Pruebas de Picos**: Evaluar el comportamiento de la API al recibir un pico de solicitudes en un corto período de tiempo.

## Requisitos

- **JMeter** instalado en tu máquina para ejecutar las pruebas.
- **Conexión a Internet** para acceder a la API Reqres.
- **Java** (opcional, dependiendo de la configuración de JMeter).

## Ejecución

1. Abre el archivo **`Reqres API Perfomance Test.jmx`** en JMeter.
2. Personaliza los parámetros según las necesidades de la prueba (número de hilos, duración de la prueba, etc.).
3. Ejecuta el test y revisa los resultados generados en la carpeta `results`.

## Resultados

Los resultados se generarán automáticamente en el formato configurado (por ejemplo, CSV, XML) en la carpeta **`results`**. Puedes revisar estos archivos para obtener detalles sobre el rendimiento de la API, como tiempos de respuesta, errores, etc.
