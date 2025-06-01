# 📊 TelecomX Data Analysis

Este repositorio contiene un análisis de datos de telecomunicaciones utilizando Python y Google Colab. El archivo de datos principal está en formato JSON y se incluye junto con el notebook para facilitar la ejecución y reproducción de resultados.

---

## 📁 Estructura del repositorio

```
.
├── TelecomX_Data.json         # Archivo de datos en formato JSON
├── analisis.ipynb             # Notebook principal para análisis
└── README.md                  # Descripción del proyecto
```
---

## 💡 Cómo usar

1. Abre el notebook desde Colab o clónalo localmente.
2. Asegúrate de que el archivo `TelecomX_Data.json` esté en la misma carpeta que el notebook.
3. Ejecuta todas las celdas del notebook (`Entorno de ejecución > Ejecutar todo`).
4. El archivo de datos se carga automáticamente con:

```python
import pandas as pd
df = pd.read_json('TelecomX_Data.json')
```

---

## 📝 Licencia

Este proyecto está distribuido bajo una licencia abierta para fines de aprendizaje, análisis y desarrollo.
