# 📡 Telecom X Latam — Análisis de Cancelación de Clientes

Análisis exploratorio de datos sobre cancelación de clientes en Telecom X Latam, desarrollado como parte del challenge de Data Science.

---

## ¿De qué trata?

Se trabajó con datos de más de 7.000 clientes para identificar qué factores están asociados a la cancelación del servicio. El proceso incluyó extracción desde una API, limpieza del dataset y análisis con visualizaciones.

---

## Tecnologías

Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

---

## Estructura

```
challenge-telecom-x/
├── TelecomX_LATAM.ipynb   # Análisis completo
├── TelecomX_Data.json     # Dataset original
└── README.md
```

---

## Cómo ejecutarlo

1. Abrí el notebook en [Google Colab](https://colab.research.google.com)
2. Ejecutá las celdas en orden con `Shift + Enter`

Los datos se descargan automáticamente desde la API, no hace falta instalar nada.

---

## Principales hallazgos

- Los contratos mensuales tienen una tasa de cancelación del 42.7%, frente al 2.8% de los contratos bianuales
- El 53.3% de los clientes nuevos cancela en los primeros 6 meses
- Los clientes sin soporte técnico cancelan al 41.6%, frente al 15.2% de los que lo tienen
