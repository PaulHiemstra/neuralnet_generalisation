FROM tensorflow/tensorflow

RUN pip install \
  numpy \
  matplotlib \
  jupyterlab \
  pandas \
  sklearn \
  plotnine \
  seaborn

CMD jupyter-lab --ip=0.0.0.0 --no-browser --allow-root
