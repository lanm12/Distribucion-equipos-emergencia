# Distribución de Equipos de Emergencia — Antioquia

App Streamlit para distribuir equipos de emergencia entre municipios
del departamento de Antioquia según perfil histórico de accidentalidad.

## Instalación
```bash
pip install -r requirements.txt
```

## Uso
```bash
streamlit run app.py
```

## Estructura
- `app.py`: aplicación principal
- `modelo_kmeans.pkl`: modelo K-Means entrenado
- `scaler_kmeans.pkl`: scaler StandardScaler
- `perfil_municipios.csv`: perfil de municipios con clusters y scores