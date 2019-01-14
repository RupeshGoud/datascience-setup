# datascience-setup
Simple Docker setup for data science environment

Based on the image, [`jupyter/datascience-notebook`](https://hub.docker.com/r/jupyter/datascience-notebook)

## Steps to install
- Change the paths as needed in `docker-compose.yml`  Eg: `/path/where/notebooks/to/be/stored:/home/jovyan/`
- `docker-compose up` - This will build as well as run the container
- `jupyter notebook` will be started at 127.0.0.1:8888
        
