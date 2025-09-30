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

---
# Value at Risk & Montecarlo Simulation.
## Spanish:
El siguiente contenido está en Inglés, si desea leer el readme en Español, desplace hacia arriba a la sección en Español.
The following content is in English, if you want to read the readme in Spanish, scroll down to the Spanish section.  
## 📝 Description.
This repo contains Jupyter Notebook code in python that implement the Montecarlo simulation to predict the future value of the ETF stock prices such as SPY, GLD and QQQ and calculate the value at risk at 95% confidence.
## 🎯 Goal.
The purpose of this repo is:
- Apply the knowledge learned in the Simulation class.
- Model the future evolution of ETF prices using historical logarithmic returns.
- Calculate financial risk metrics, specifically VaR, to assess the maximum expected loss over a 30-day time horizon with 95% confidence.
## 🚀 key features.
- Download historic data using yfinance library.
- Descarga de datos históricos usando la librería yfinance.
- Calculation of logaritmic returns to model price evolution.
- Montecarlo simulation with 10,000 possible future price scenarios.
- Calculation of Value at Risk (VaR) at 95% confidence level.
- Display of results using histograms and distribution graphs.
## 💻 Used tech:
- Python 3.
- Libraries:
  - yfinance: Download financial data
  - Pandas: Manipulation and data analysis.
  - Numpy: Numeric operations and random number generation.
  - Matplotlib y seaborn: Data visualization.
## 🏗️ Project structure.
- market_prediction_var.ipynb: First file with the montecarlo and var implementation.
- var_mejorado: improvement of the first file.
- readme.me
## 🧠 Simulation and statistic methods.
- Monte Carlo simulation: Generates multiple price trajectories based on the historical distribution of returns.
- VaR calculation: Uses percentiles from the simulated distribution to determine the risk of loss.
- Logarithmic returns: These are used because they are additive over time and symmetric, which facilitates modeling and simulation. They also prevent simulated prices from being negative.
- Additional metrics: Expected value of the price and confidence intervals.
## ✅ Results.
- Expected Value: Projected price of the ETF in 30 days.
- VaR at 95%: Maximum expected loss with 95% confidence.
- Confidence Interval: Range of expected prices for the time horizon.
## ❗ Usage.
1.- Run the notebooks in an environment with the dependencies installed.  
2.- Data for the last year is downloaded automatically.  
3.- Adjust parameters such as the number of simulations or days as necessary.  
## 💡 Applications.
- Financial risk management.
- Analysis of investments in ETFs.
- Modeling uncertainty in financial markets.
## 🗒️ Important note.
This project is for educational and research purposes. The results do not constitute financial advice.
##✍️ Author.
Gustavo Cortés (guco).
