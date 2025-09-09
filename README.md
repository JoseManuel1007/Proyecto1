# Simulador Solar Fotovoltaico en Python

Este proyecto implementa un simulador solar fotovoltaico en Python que permite:

- Calcular la posición del sol (altitud y azimut) en una ubicación y hora específicas.
- Estimar la irradiancia incidente sobre un panel solar con inclinación y orientación definidas.
- Simular la producción de energía fotovoltaica a lo largo de un día.
- Generar gráficas y reportes CSV con los resultados de la simulación.

---

## Ejecutar en Google Colab

Haz clic en el siguiente botón para abrir y ejecutar el simulador directamente en Google Colab:

<a href="https://colab.research.google.com/github/JoseManuel1007/Proyecto1/blob/main/solar_simulator.ipynb" target="_parent">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

## Archivos generados

- `sim_YYYYMMDD.csv` → Resultados de la simulación en formato tabular (tiempo, altitud, azimut, irradiancia, potencia).  
- Carpeta `graficas_YYYY-MM-DD/` con:
  - `altitud_vs_hora.png`
  - `azimut_vs_hora.png`
  - `irradiancia_vs_hora.png`
  - `potencia_vs_hora.png`
  - `energia_acumulada.png`

---

## Dependencias

El código utiliza únicamente librerías estándar de **Python 3.x**:

- `numpy`
- `pandas`
- `matplotlib`
- `datetime`
- `os`

En Google Colab ya están preinstaladas.  
En ejecución local, se pueden instalar con:

```bash
pip install numpy pandas matplotlib
 irradiancia, potencia).  
- Carpeta `graficas_YYYY-MM-DD/` con:
  - `altitud_vs_hora.png`
  - `azimut_vs_hora.png`
  - `irradiancia_vs_hora.png`
  - `potencia_vs_hora.png`
  - `energia_acumulada.png`

---

## Dependencias

El código utiliza únicamente librerías estándar de **Python 3.x**:

- `numpy`
- `pandas`
- `matplotlib`
- `datetime`
- `os`

En Google Colab ya están preinstaladas.  
En ejecución local, se pueden instalar con:

```bash
pip install numpy pandas matplotlib
