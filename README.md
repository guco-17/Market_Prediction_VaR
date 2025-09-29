# Value at Risk & Montecarlo Simulation.
## Español:
The following content is in Spanish, if you want to read the readme in English, scroll down to the English section.  
El siguiente contenido está en Español, si desea leer el readme en Inglés, desplace hacia abajo a la sección en Inglés.
## 📝 Descripción.
Este repositorio contiene programas en Jupyter Notebook que implementan la simulación de Montecarlo para predecir el valor futuro del precio de las acciones de ETFs como el SPY, GLD y QQQ y calcular el valor en riesgo al 95% de confianza.
## 🎯 Objetivo.
El objetivo de este repo es:
- Aplicar los conocimientos aprendidos en la clase de Simulación.
- Modelar la evolución futura de los precios de ETFs usando los retornos logarítmicos históricos.
- Calcular métricas de riesgo financiero, específicamente el VaR, para evaluar la pérdida máxima esperada en un horizonte temporal de 30 días con un 95% de confianza.
## 🚀 Características principales.
- Descarga de datos históricos usando la librería yfinance.
- Cálculo de retornos logarítmicos para modelar la evolución de precios.
- Simulación de Montecarlo con 10,000 escenarios posibles de precios futuros.
- Cálculo del Valor en Riesgo (VaR) al 95% de confianza.
- Visualización de resultados mediante histogramas y gráficos de distribución.
## 💻 Tecnologías usadas:
- Python 3.
- Librerías:
  - yfinance: Descarga de datos financieros.
  - Pandas: Manipulación y análisis de datos.
  - Numpy: Operacónes numéricas y generación de números aleatorios.
  - Matplotlib y seaborn: visualización de datos.
## 🏗️ Estructura del proyecto.
- market_prediction_var.ipynb: primer archivo con el código de la simulación y análisis.
- var_mejorado: Mejora del primer archivo.
- readme.me
## 🧠 Métodos de simulación y estadística.
- Simulación de Montecarlo: Genera múltiples trayectorias de precios basadas en la distribución histórica de retornos´.
- Cálculo de VaR: Utiliza percentiles de la distribución simulada para determinar el riesgo de pérdida.
- Retornos logarítmicos: Se utilizan porque son aditivos en el tiempo y simétricos, lo que facilita el modelado y la simulación. Además, evitan que los precios simulados sean negativos.
- Métricas adicionales: Valor esperado del precio y rangos de confianza.
## ✅ Resultados Principales.
- Valor Esperado: Precio proyectado del ETF en 30 días.
- VaR al 95%: Pérdida máxima esperada con 95% de confianza.
- Intervalo de Confianza: Rango de precios esperados para el horizonte temporal.
## ❗ Uso.
1.- Ejecutar los notebooks en un entorno con las dependencias instaladas.  
2.- Los datos se descargan automáticamente para el último año.  
3.- Ajustar los parámetro somo número de simulaciones o días según sea necesario.  
## 💡 Aplicaciones.
- Gestión de riesgos financieros.
- Análisis de inversiones en ETFs.
- Modelado de incertidumbre en mercados financieros.
## 🗒️ Nota importante.
Este proyecto es con fines educativos y de investigación. Los resultados no constituyen asesoramiento financiero.
##✍️ Autor.
Gustavo Cortés (guco).
