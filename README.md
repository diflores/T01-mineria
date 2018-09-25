# Tarea 1: implementación del algoritmo Apriori

##### Por: Daniela Flores Villanueva

## Descripción

```
.
├── README.md
├── Tarea 1 – Apriori.ipynb
└── requirements.txt
```



### *Overview*

| Archivo                   | Descripción                                   |
| ------------------------- | --------------------------------------------- |
| `README.md`               | Este archivo.                                 |
| `Tarea 1 – Apriori.ipynb` | *Notebook* con la implementación de la tarea. |
| `requirements.txt`        | Archivo con librerías de Python requeridas.   |
| `README.txt`              | *Readme* en versión texto plano.              |



## Requerimientos

Las librerías requeridas para ejecutar esta tarea se encuentran en `requirements.txt`. Los requerimientos se pueden instalar fácilmente con:

```bash
pip install -r requirements.txt
```



## Ejecución

Para ejecutar el *notebook*:

1. Verificar que se cuenta con las librerías requeridas (ver sección de Requerimientos)
2. Situarse vía terminal en la carpeta donde se encuentra este instructivo y ejecutar lo siguiente: `jupyter notebook`.
3. En la ventana del navegador que se abrirá, hacer click sobre `Tarea 1 – Apriori.ipynb`.

### Sobre la librería Altair

La librería funciona mejor con [`jupyter lab`](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) en vez de `jupyter notebook`. De decidir usar la primera opción, se debe comentar la línea `alt.renderers.enable('notebook')`. En el caso de la segunda opción, antes de abrir `jupyter notebook` se debe ejecutar lo siguiente:

```
pip install -U altair vega_datasets notebook vega
```

