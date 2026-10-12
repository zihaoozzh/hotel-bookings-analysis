# Análisis de reservas hoteleras

Proyecto de aprendizaje de análisis de datos con **pandas**, aplicado a reservas reales de hotel. Estado: **en progreso** (semana 1 de 5).

## Dataset

[Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) (Kaggle): 119.390 reservas y 32 columnas de un hotel urbano y uno vacacional en Portugal, entre 2015 y 2017. Datos originales de Antonio, Almeida y Nunes (2019).

El CSV no está incluido en el repositorio. Descárgalo de Kaggle y colócalo en la raíz de la carpeta como `hotel_bookings.csv`.

## Preguntas que responde el análisis

- ¿Cuántas reservas tiene cada hotel y qué porcentaje se cancela?
- ¿De qué países llegan más reservas?
- ¿Cómo cambia la tasa de cancelación según el mes, el segmento de mercado y la antelación?
- ¿Cómo varía la tarifa media diaria (ADR) a lo largo del año?
- ¿Qué factores se asocian a más cancelaciones?

## Contenido

| Archivo | Descripción | Estado |
|---|---|---|
| `semana1_explorar.ipynb` | Carga y exploración inicial | En curso |
| *(próximos notebooks)* | Agrupación, limpieza, visualización y conclusiones | Pendiente |

## Cómo ejecutarlo

Requiere Python 3.10 o superior.

```
python -m venv .venv
.venv\Scripts\activate
pip install pandas matplotlib jupyter
```

Abre el notebook en VS Code o con `jupyter notebook`, selecciona el entorno `.venv` y ejecuta las celdas de arriba abajo.

## Herramientas

Python, pandas, matplotlib y Jupyter.

## Resultados

Se añadirán al terminar el análisis, con tres gráficos y tres conclusiones de negocio.

## Autor

Zihao Zhou · [LinkedIn](www.linkedin.com/in/zihao-zhou-uc3m)
