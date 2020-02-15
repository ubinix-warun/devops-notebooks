# devops-notebooks


```
docker run -it --rm --name devops-notebooks -v `pwd`/aws:/root/.aws -v `pwd`/notebooks:/opt/notebooks -p 8888:8888 ubinix5warun/jupyter-devops /bin/bash -c "/opt/conda/bin/conda install jupyterlab -y --quiet && /opt/conda/bin/jupyter lab --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root"

```
