# introduction-to-python-using-the-datascience-library
https://docs.microsoft.com/en-us/learn/modules/introduction-python-using-datascience-library/

## Run through Visual Studio Code with Jupyter plugin
You will need to install Python and run:
pip install jupyter

## How to run Jupyter through Dockerfile
docker run -p 8888:8888 -v ${PWD}:/home/jovyan/data jupyter/datascience-notebook
