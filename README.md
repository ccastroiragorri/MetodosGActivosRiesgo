# Métodos cuantitativos para gestión de activos y análisis de riesgo.

## Objetivos
El objetivo del curso es fortalecer las capacidades técnicas donde se abordaran diferentes métodos de estadística aplicada en finanzas que son capacidades esenciales para los equipos de gestión de activos y riesgos en el sector financiero. El curso incluye conceptos clásicos del análisis estadístico de series de tiempo financieras y de gestión de portafolios así como las principales tendencias recientes en ambos campos.
Se ofrece un conjunto de módulos que se presentaran en espacios de 3 horas diarias. En cada módulo se realizara una presentación conceptual, junto con una ilustración de la implementación a través de Excel y/o software de libre distribución como [Gretl](https://gretl.sourceforge.net/index.html) o [R](https://www.r-project.org/) (de acuerdo a los conocimientos previos e intereses de los participantes).
Los participantes tendrán acceso permanente a una página web del curso donde tendrán todo el material necesario para participar de manera activa en la sesiones y preparar el material anticipadamente. 

## Preliminares
* Instalacion de Gretl, [windows](https://gretl.sourceforge.net/win32/).

## Contenido

# Modelos para la media condicional.
1. Hechos estilizados de las series financieras.
2. Identificación y estimación de modelos ARMA.
3. Pronóstico de modelos ARMA.
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/SeriesUnivariadas.pdf).
* [Procesos generadores de datos](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/dgp.xlsx).
* Series Financieras: [TRM](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/TRM.gdt), [Oil](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/oil.xlsx).
4. Modelos multivariados vectores autoregresivos (VAR): Estimación y análisis.
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/SeriesMultivariadas.pdf)
* [Tasas de Interes](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/TasasCol.gdt).

# Modelos estimacion y pronostico de la varianza.
1. Estimación de Volatilidad con información diaria: GARCH.
2. Modelos asimétricos para Volatilidad.
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/GARCH.pdf)
3. Estimación de Volatilidad con información intradía: Volatilidad Realizada.
4. Estimación de Saltos en las series financieras.
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/RM.pdf)
* [Ejemplo Excel Datos Intradia](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/Ecopetrol.xlsx).
* [Ejemplo Python Datos Intradia](https://nbviewer.org/github/nromerodiaz/MarketQualityParams/blob/master/JumpStatistic.ipynb).
5. Modelos de pronóstico para la Volatilidad.
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/PronosticoVol.pdf)

# Teoria de Portafolio.
1. Preferencias de Media-Varianza. 
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/PFMV.pdf)
2. Modelo de portafolio de Markowitz (Media-Varianza). 
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/Markovitz.pdf)
3. Modelo de Black-Litterman. 
* [Diapositivas](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/BL.pdf)
* [Ejemplo Markowitz/Black-Litterman](https://github.com/ccastroiragorri/MetodosGActivosRiesgo/blob/main/OptimizacionPortafolioMV_BL.xlsx).

# Referencias
* [Hyndman and Athanasopoulos. Forecasting: Principles and Practice](https://otexts.com/fpp3/)
* [Sheppard, K. Financial Econometrics Notes](https://www.kevinsheppard.com/files/teaching/mfe/notes/financial-econometrics-2020-2021.pdf)
* [Empirical evidence of jump behaviour in the Colombian intraday bond market (2020)](https://ideas.repec.org/p/col/000092/018098.html)
* [Pedersen, L.H., Babu, A., Levine, A.(2021). Enhanced Portfolio Optimization, Financial Analysts Journal Volume 77(2)](https://doi.org/10.1080/0015198X.2020.1854543)
