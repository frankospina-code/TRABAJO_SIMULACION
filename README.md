# Simulación de Yahtzee con Monte Carlo

Simulación de una partida de Yahtzee para dos jugadores, con selección de dados y categorías mediante Monte Carlo, además de análisis y gráficos.

## Requisitos

- Python 3
- Dependencias de Python listadas en `requirements.txt`
- Graphviz opcional para generar el diagrama de flujo PNG. Sin el ejecutable `dot`, se guarda el fuente `.dot`.

## Instalación y ejecución

Desde la carpeta del proyecto, crea y activa un entorno virtual, instala las dependencias y ejecuta el script:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python "YATSI método de Montecarlo.py"
```

Los gráficos estadísticos se muestran en ventanas. Si no aparece una ventana gráfica, ejecuta el script en un entorno con soporte gráfico y sin configurar `MPLBACKEND=Agg`.
