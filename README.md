# machine learning project

To enable Jupyter autocomplete via jupyter-tabnine:
```shell script
jupyter nbextensions_configurator enable --user
jupyter nbextension install --py jupyter_tabnine --user
jupyter nbextension enable --py jupyter_tabnine --user
jupyter serverextension enable --py jupyter_tabnine --user
```