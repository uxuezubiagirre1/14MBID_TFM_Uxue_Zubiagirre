# 14MBID_TFM_Uxue_Zubiagirre
# TFM — Análisis del desempeño y la resiliencia del sector bancario español (2007–2025)

**Autor:** Uxue Zubiagirre  
**Máster:** 14MBID — Máster en Business Intelligence y Data Science  
**Fecha:** Mayo 2025  

## Descripción

Análisis multidimensional del desempeño de los cinco principales bancos 
cotizados españoles (Santander, BBVA, CaixaBank, Bankinter y Sabadell) 
durante el período 2007–2025, mediante la integración de datos financieros, 
de mercado y macroeconómicos, y su visualización en un cuadro de mando 
interactivo desarrollado en Power BI.

## Estructura del repositorio

- `notebooks/` — Notebook de Python con todo el código de análisis
- `dashboard/` — Cuadro de mando interactivo en Power BI (.pbix)
- `data/raw/` — Dataset financiero recopilado manualmente
- `data/processed/` — Datasets integrados generados por el notebook
- `data/outputs/` — Gráficos generados por Python incluidos en la memoria

## Requisitos

```python
pandas
numpy
matplotlib
seaborn
yfinance
fredapi
linearmodels
statsmodels
scikit-learn
openpyxl
```

## Fuentes de datos

- Datos financieros: informes anuales oficiales de cada entidad (SEC, CNMV)
- Datos de mercado: Yahoo Finance vía yfinance
- Datos macroeconómicos: Banco Mundial API y FRED API
