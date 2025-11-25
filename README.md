# Python Aplicado a Finanzas y Gestión de Portafolios

Este repositorio consolida los proyectos y ejercicios prácticos desarrollados durante el curso de **Python Aplicado a Finanzas**. El objetivo principal es la aplicación de librerías de Data Science para el análisis financiero, la gestión de riesgos y la optimización de inversiones.

Aquí encontrarás implementaciones de modelos financieros clásicos y modernos, desde el análisis fundamental hasta estrategias cuantitativas avanzadas.

## 📂 Contenido del Repositorio (`/code`)

Los notebooks están organizados para cubrir distintas áreas del análisis financiero cuantitativo:

### 📊 Visualización y Análisis de Activos
Análisis exploratorio de datos financieros, cálculo de retornos y visualización de tendencias de mercado.
* **Evolución de Precios y Retornos:** Scripts para la descarga de datos históricos y visualización de precios (`02_evolucion_precio_grafico.ipynb`, `03_retornos_acumulados_visualizacion.ipynb`).
* **Screening de Acciones:** Filtrado y selección de activos basado en criterios financieros específicos (`05_screening.ipynb`).

### 📉 Modelado de Riesgo y Clasificación
Aplicación de modelos para evaluar la salud financiera de empresas y predecir quiebras.
* **Modelo Altman Z-Score:** Implementación de algoritmos de clasificación para evaluar el riesgo de crédito y probabilidad de quiebra (`04_altman_zcore_classification.ipynb`, `Tarea_altman_zcore_classification.ipynb`).

### 🧠 Optimización de Portafolios
Uso de técnicas de optimización matemática para la construcción de carteras eficientes.
* **Optimización Media-Varianza:** Implementación de la Frontera Eficiente de Markowitz para maximizar el ratio de Sharpe (`07_Pfin_Opt_Port.ipynb`).
* **Risk Parity:** Construcción de portafolios equilibrados basados en la contribución de riesgo de cada activo (`07_PFin_Risk_Parity_Opt.ipynb`).
* **Black-Litterman:** Incorporación de visiones de mercado subjetivas en la optimización de portafolios (`07_Pfin_B&L.ipynb`).

### 🎲 Simulación y Backtesting
Pruebas de estrategias y modelado estocástico.
* **Backtesting con QuantStats:** Evaluación de rendimiento de estrategias de inversión frente a benchmarks (`06_Backtesting_QuantStats.ipynb`).
* **Movimiento Browniano Geométrico:** Simulación de Monte Carlo para la proyección de precios de activos (`movimiento_browniano_geometrico.ipynb`).

---

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** Python 3.10+
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn, Scipy, QuantStats, yFinance.

---
*Desarrollado por [Joaquin Terrazas](https://www.linkedin.com/in/joaquinterrazas/) - Estudiante de Economía | Universidad de Lima*
