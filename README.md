# 🏦 Extracción de Datos de Resumen Bancario - Banco Provincia 🏦

Este proyecto está diseñado para extraer y procesar datos de los extractos bancarios del Banco Hipotecario en formato PDF utilizando Python. Las principales librerías empleadas son `tabula-py` para la lectura de archivos PDF y `pandas` para la manipulación y análisis de los datos.

## Características

- **Extracción Detallada de Datos**: Automatiza la extracción de movimientos bancarios, incluyendo la fecha, descripción, referencia, valor, débitos, créditos y saldo.
- **Detección de Período y CBU**: Detecta automáticamente el período y el CBU al que pertenece cada movimiento.
- **Separación de Débitos y Créditos**: Organiza y separa las transacciones entre débitos y créditos.
- **Cálculo de Saldo Acumulado**: Añade una columna de saldo acumulado para un control financiero más preciso.
- **Procesamiento y Limpieza de Datos**: Garantiza que los datos extraídos estén listos para análisis y uso posterior.
