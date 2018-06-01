----- BUILD
docker build -f Dockerfile -t Laboratorio .
----- TEST
docker run -it --rm -v $PWD/data:/home/jovyan/data -v $PWD/model:/home/jovyan/model -e NB_UID=`id -u` Laboratorio
