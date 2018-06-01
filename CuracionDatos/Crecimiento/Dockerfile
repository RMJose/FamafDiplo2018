FROM jupyter/scipy-notebook

ADD EjercicioTablasCrecimiento.ipynb .
ADD data/lenageinf.csv .
ADD data/wtageinf.csv .

ENTRYPOINT start.sh jupyter nbconvert --execute --to notebook --output-dir=model --output=EjercicioTablasCrecimiento-log EjercicioTablasCrecimiento.ipynb

