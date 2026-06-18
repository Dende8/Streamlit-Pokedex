# Streamlit Pokedex

Proyecto simple que prepara datos de Pokémon y levanta una aplicación web con Streamlit.

Contenido
- preparar_datos.ipynb: notebook para limpieza y preparación del dataset (descarga, transformación y exportación a CSV/JSON).
- app.py: aplicación Streamlit que muestra la Pokedex interactiva usando los datos preparados.

Requisitos
- Python 3.8+
- Paquetes (instalar con pip):
  - streamlit
  - pandas
  - numpy
  - requests
  - matplotlib (opcional)

Instalación rápida
1. Crear y activar un entorno virtual (opcional pero recomendado):
	python -m venv .venv
	# Windows
	.\.venv\Scripts\activate
2. Instalar dependencias:
	pip install -r requirements.txt

Uso
- Preparar datos (notebook): Abra y ejecute preparar_datos.ipynb en Jupyter/VSCode para descargar y generar el archivo de datos (por ejemplo data/pokedex.csv).
- Ejecutar la app:
	streamlit run app.py

Estructura esperada de archivos de salida
- data/pokedex.csv (o pokedex.json): archivo con la información de los Pokémon preparada por el notebook.

Notas
- Ajuste las rutas de lectura/escritura en preparar_datos.ipynb o app.py si es necesario.
- Si no dispone de requirements.txt, instale manualmente los paquetes listados en "Requisitos".

Licencia
Proyecto de ejemplo para aprendizaje. Use y modifique libremente.

