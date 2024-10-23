# docker-ev-vre-jupyter
# see https://github.com/EGI-Federation/egi-notebooks-images/blob/master/single-user-sobigdata-itineris/Dockerfile
docker buildx build -t docker-itineris-ev-vre-jupyternotebook -f ./Dockerfile --platform=linux/amd64 .
