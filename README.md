# Scraper

Repositorio reservado para experimentos de **extracción automatizada de datos**.

## Estado actual

La documentación previa del repositorio no indicaba todavía qué fuente de datos se consulta, qué librerías se utilizan ni cuál es el punto de entrada del proyecto. Este README deja preparada una estructura básica para completar esa información a medida que el scraper evolucione.

## Información que conviene documentar

- objetivo de la extracción;
- páginas o APIs consultadas;
- archivo principal de ejecución;
- dependencias necesarias;
- formato de los datos generados;
- límites de peticiones y consideraciones legales o de uso del sitio consultado.

## Puesta en marcha recomendada

1. Crea un entorno de Python.
2. Añade un archivo `requirements.txt` cuando las dependencias estén definidas.
3. Separa el código fuente, la configuración y los datos generados en carpetas distintas.
4. Añade instrucciones concretas de ejecución cuando el script principal esté identificado.

## Estructura sugerida

```text
src/            # código del scraper
config/         # configuración y variables no sensibles
data/           # resultados generados
requirements.txt
README.md
```

No incluyas credenciales, tokens ni datos sensibles directamente en el repositorio.
