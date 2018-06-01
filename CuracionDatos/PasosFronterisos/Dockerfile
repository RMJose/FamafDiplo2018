FROM jupyter/scipy-notebook

ADD PasosFronterizos.ipynb .
ADD data/pasos.json .

ENTRYPOINT start.sh jupyter nbconvert --execute --to notebook --output-dir=model --output=PasosFronterizos-log PasosFronterizos.ipynb

