
# TAREA IA 2 - KEVIN ANDRES MUÑOZ G.

## Estructura del proyecto 
| Carpeta | Contenido | Descripción |
|----------|------------|-------------|
| **assets/** | Imágenes, diagramas y recursos visuales | Contiene los diagramas de arquitectura (`rnn_diagram.png`, `lstm_diagram.png`). |
| **data/** | Archivos JSON y dataset procesado | Incluye los datos de entrada capturados con Edge Impulse (`.json`) y el dataset final (`dataset_windows_json.npz`) generado tras el preprocesamiento. Las subcarpetas representan las clases de movimiento (`caminar`, `correr`, `saltar`, `girar`, `quieto`). |
| **model/** | Modelos entrenados (RNN y LSTM) |Contiene los archivos de exportación de los modelos RNN y LSTM. |
| **notebooks/** | Código en Jupyter Notebooks |Contiene los notebooks de procesamiento y entrenamiento: <br> - `data_prep_edge_impulse_json.ipynb` → Limpieza, normalización y segmentación de datos. <br> - `rnn_lstm_timeseries_classification.ipynb` → Entrenamiento, evaluación y visualización de resultados. |


## 1. Crear un entorno virtual

Crear entorno virtual
```
python -m venv venv
```

Activar entorno windows 
```
venv\Scripts\activate
```
Descargar librerias necesarias 
```
pip install -r requirements.txt
```

## 2. Instalar Graphviz

Entrar a la pagina de [Graphviz](https://graphviz.gitlab.io/download/) y instalar el recuerso.

**!!! IMPORTANTE MARCAR INCLUIR EN EL PAHT EN LA INSTALACION !!!**

## 3. Instalar Pydot
```
pip install pydot
```

## 4. Diagramas
### Modelo LTSM. 
![Model LSTM](/assets/lstm_diagram.png)
---
### Modelo RNN
![Model RNN](/assets/rnn_diagram.png)
---

## 5. Video de la explicacion

Este es el link para ver el video [VIDEO DE EXPLICACION](https://drive.google.com/drive/folders/118xlAPfZBIVB7nMTjVDgamq2PuTv26uu?usp=sharing).

## 6. Author
<table style="border-collapse: collapse; border: none;">
  <tr>
    <td align="center" width="150" style="border: none;">
      <a href="https://github.com/KevinMG1601">
        <img src="https://avatars.githubusercontent.com/u/143461336?v=4" width="100px" alt="Kevin Muñoz"/><br />
        <span style="color: black; font-weight: bold;">Kevin Muñoz</span>
      </a>
    </td>
    <td style="border: none; vertical-align: top;">
      Created by <b>Kevin Muñoz</b>. I would like to know your opinion about this project. You can write me by <a href="mailto:kevin.andres2636@gmail.com">email</a> or connect with me on <a href="https://www.linkedin.com/in/kevin-mu%C3%B1oz-231b80303/">LinkedIn</a>.
    </td>
  </tr>