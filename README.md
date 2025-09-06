# Graficos‑acicidentes‑viales‑Medellin

Visualizaciones geoespaciales de incidentes viales en Medellín.

## 📂 Estructura del Repositorio

- **shapefile/** — Archivos geoespaciales para representar los límites de las comunas de Medellín.
- **shapefile_comunas_medellin/** — Versión específica de los shapefiles centrados en las comunas.
- **Incidentes_georreferenciados_2019.csv** — Datos tabulados de accidentes de tránsito geocodificados en Medellín durante 2019.
- **gráficos_accidentes.ipynb** — Notebook de Jupyter que contiene el procesamiento, análisis y visualización de datos.
- **accidentes_viales.html** — Salida renderizada del notebook, con gráficos interactivos listos para visualizar.

##  Propósito

Este proyecto tiene como objetivo analizar y visualizar los incidentes viales ocurridos en Medellín durante 2019, explorando patrones geoespaciales por comuna y facilitando el análisis visual mediante gráficos interactivos.

##  Requisitos

- Python 3.8 o superior
- Dependencias habitualmente usadas:
  - pandas
  - geopandas
  - matplotlib / seaborn
  - folium o plotly (para mapas interactivos)
  - jupyter / nbconvert (opcional, para ejecutar o convertir el notebook)

Se sugiere crear un entorno virtual para instalar estas bibliotecas:

```bash
python -m venv venv
source venv/bin/activate  # En Windows, usar `venv\Scripts\activate`
pip install pandas geopandas matplotlib seaborn folium notebook
```

(Adapta según tus necesidades o requerimientos específicos.)

##  Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Andresvasq12/Graficos-acicidentes-viales-Medellin.git
   cd Graficos-acicidentes-viales-Medellin
   ```

2. Activa el entorno virtual e instala dependencias (ver sección anterior).

3. Ejecutar el notebook:
   ```bash
   jupyter notebook gráficos_accidentes.ipynb
   ```
   Esto permitirá visualizar de forma interactiva el análisis y los gráficos generados.

4. También puedes abrir directamente:
   - accidentes_viales.html en tu navegador para ver las visualizaciones sin necesidad de ejecutar el notebook.

##  Contenido Destacado

- Mapas geográficos de densidad o calor de incidentes por comuna.
- Histogramas o gráficos de barras por tipo de incidente (por ejemplo: motociclistas, peatones).
- Análisis temporal (si los datos lo permiten: día, mes, hora).
- Visualizaciones interactivas que facilitan el entendimiento de patrones espaciales.

##  Extensiones Sugeridas

- Actualizar los datos para incluir años posteriores a 2019, permitiendo comparaciones a lo largo del tiempo.
- Incluir análisis de factores de riesgo (topografía, tipo de vía, zonas escolares, etc.).
- Crear un panel web interactivo con frameworks como Dash o Streamlit.
- Agregar métricas estadísticas (por ejemplo, densidad de incidentes por km² o por número de habitantes por comuna).

##  Contribuciones

Este es un proyecto en etapa inicial (“scaffold”) para visualizar datos viales. Si deseas colaborar:

1. Haz **fork** del repositorio.
2. Crea una **branch** (`git checkout -b feature/nueva-visualizacion`).
3. Realiza tus cambios y haz **commit** (`git commit -m "Añade gráfico de histograma por hora del día"`).
4. Haz **push** y abre un **Pull Request** para revisión.

##  Licencia

Este proyecto está disponible bajo la [MIT License](LICENSE), o, si aún no has definido una, puedes crear un archivo LICENSE con el texto respectivo.

##  Contacto

Si tienes preguntas o sugerencias, por favor, abre un [issue] o contáctame directamente vía GitHub.
