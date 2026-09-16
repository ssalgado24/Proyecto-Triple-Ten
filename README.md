# Aplicación Proyecto Samuel Salgado

Aplicación web interactiva construida con **Streamlit** y **Plotly** para explorar un conjunto de datos de anuncios de venta de vehículos usados (`vehicles_us.csv`).

🔗 **Aplicación desplegada:** [https://proyecto-triple-ten.onrender.com/](https://proyecto-triple-ten.onrender.com/)

## Descripción

Esta aplicación permite visualizar dos tipos de gráficos a partir del dataset de vehículos:

- **Histograma**: muestra la distribución del kilometraje (`odometer`) de los vehículos.
- **Gráfico de dispersión**: muestra la relación entre el kilometraje (`odometer`) y el precio (`price`) de los vehículos.

Ambos gráficos se generan de forma interactiva al hacer clic en los botones correspondientes.

## Tecnologías utilizadas

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) — manejo y lectura de datos
- [Plotly](https://plotly.com/python/) — creación de gráficos interactivos
- [Streamlit](https://streamlit.io/) — construcción de la interfaz web

## Requisitos previos

- Python 3.8 o superior
- pip

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repo.git
   cd nombre-del-repo
   ```

2. Crea y activa un entorno virtual (opcional, pero recomendado):
   ```bash
   python -m venv venv
   ```
   En Windows:
   ```bash
   venv\Scripts\activate
   ```
   En Mac/Linux:
   ```bash
   source venv/bin/activate
   ```

3. Instala las dependencias:
   ```bash
   pip install pandas plotly streamlit
   ```

## Uso

Asegúrate de que el archivo `vehicles_us.csv` esté en el mismo directorio que el script de la aplicación. Luego, ejecuta:

```bash
streamlit run app.py
```

(Reemplaza `app.py` por el nombre real de tu archivo si es diferente).

Esto abrirá la aplicación en tu navegador predeterminado, normalmente en `http://localhost:8501`.

## Funcionalidades

| Botón | Acción |
|---|---|
| **Construir histograma** | Genera un histograma de la distribución del odómetro de los vehículos. |
| **Construir gráfico de dispersión** | Genera un gráfico de dispersión entre el odómetro y el precio de los vehículos. |

## Estructura del proyecto

```
├── app.py                 # Script principal de la aplicación Streamlit
├── vehicles_us.csv         # Dataset de anuncios de venta de vehículos
└── README.md               # Este archivo
```

## Autor

Samuel Salgado

## Licencia

Este proyecto se distribuye con fines educativos como parte del bootcamp de TripleTen.
