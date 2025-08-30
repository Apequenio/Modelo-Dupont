# 🧮 Modelo DuPont - Streamlit App

Este proyecto implementa un análisis de rentabilidad de negocios utilizando el modelo DuPont en Python, desplegado en una aplicación interactiva usando Streamlit.

## 📌 Características

- Carga de archivos `.xlsx` o `.csv` con indicadores financieros.
- Cálculo automático de:
  - Margen Neto (%)
  - Rotación (veces)
  - Apalancamiento (veces)
  - ROE (%)
  - ROA (%)
  - Pay Back sobre Capital y Activos
- Visualización de resultados por período.
- Exportación del reporte en formato Excel.

## 📊 Formato del archivo de entrada

El archivo debe contener los siguientes conceptos como filas:

- Ventas Netas
- Utilidad Neta
- Activos Totales
- Capital Contable

Y los períodos como columnas (ej. 2021, 2022, 2023…).

## 🚀 Instrucciones

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
