# Laboratorio 3

## Integrantes

- Sergio Orellana 221122
- Rodrigo Mansilla 22611

## Entrega preparada

- `lab3_ser_orellana_y_rod_mansilla.ipynb`: partes A y C completas y ejecutadas; partes B y D marcadas para Rodrigo.
- `corpus_paginas_20_21.pdf`: dos páginas consecutivas seleccionadas del corpus original.
- `resultados_atencion_parte_c.csv`: tabla exportada por la parte C.
- `requirements.txt`: dependencias del entorno.

El PDF completo de *La metamorfosis* se conserva localmente, pero se excluye de Git porque la entrega sólo necesita `corpus_paginas_20_21.pdf`. También excluimos `.venv`, cachés, checkpoints y pesos descargados del modelo.

## Ejecución local

En PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m ipykernel install --prefix .venv --name lab3_venv --display-name "Python 3 (Lab 3)"
jupyter lab
```

En este equipo ya se creó `.venv` y se registró el kernel local `lab3_venv`. El modelo se descarga automáticamente desde Hugging Face la primera vez que se ejecuta el notebook en una instalación nueva.
