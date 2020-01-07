# SetiProject

### prerequisites

first of all, you need to install the dependencies : 

```
pip install -r requirements.txt
```


### training

to train the model, run :

```
python3 train.py
```

this training process will generate a _"mymodel.h5"_ file.

you can also run the jupyter notebook by opening _notebookVersion.ipynb_. The notebook will generate a "my_model_89.h5": file.


### testing

Open "notebookVersion_test.ipynb" with jupyternotebook and run all cells.

by default this task will test "my_model_89.h5" model from training with jupyternotebook, if you train the model with the first option and want to test the model please change the model name on test section.

### simulation

run the following command :

```
python3 simulation.py
```
