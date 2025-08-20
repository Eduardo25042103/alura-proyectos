# 📊 Proyecto de Análisis de Abandono de Clientes - TelecomX

## 📌 Descripción
Análisis predictivo del abandono de clientes en TelecomX utilizando técnicas de machine learning. El proyecto incluye análisis exploratorio de datos (EDA), modelado predictivo y recomendaciones estratégicas basadas en datos.

## 🛠️ Tecnologías Utilizadas
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- NumPy

## 📦 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/Eduardo25042103/alura-proyectos
cd challenge3-aluralatam

# Instalar dependencias
pip install -r requirements.txt
```

## 📊 Estructura del Proyecto

```plaintext
telecomx-analysis/
├── data/
│   ├── raw/                    # Datos originales
│   └── processed/              # Datos procesados
├── notebooks/
│   ├── 01_EDA.ipynb           # Análisis exploratorio
│   └── 02_Modeling.ipynb      # Modelado predictivo
├── src/
│   └── utils/                 # Funciones auxiliares
├── requirements.txt           # Dependencias
└── README.md                 # Este archivo
```

## 📈 Resultados Principales

### Métricas de Modelos
- Random Forest: 79.12% precisión
- Decision Tree: 73.24% precisión

### Factores Clave de Abandono
1. Tipo de contrato (mensual)
2. Antigüedad del cliente
3. Cargos totales

## 💡 Uso

```python
# Ejemplo de carga de datos
import pandas as pd

# Cargar datos procesados
df = pd.read_csv('telecomx_datos_procesados.csv')

# Ver primeras filas
print(df.head())
```

## 🔍 Análisis Realizados

1. **Análisis Exploratorio**
   - Distribución de variables
   - Correlaciones
   - Patrones de abandono

2. **Modelado Predictivo**
   - Preparación de datos
   - Entrenamiento de modelos
   - Evaluación y métricas

## 📝 Licencia
Este proyecto está bajo la Licencia MIT.

## ✉️ Contacto
- Nombre: Eduardo Sánchez


## 🙏 Agradecimientos
- Alura Latam
- ONE