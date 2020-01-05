Here's what you need in order to run this code:

* Clone this repository somewhere nice
* Create a [Kaggle](https://www.kaggle.com) account, join the [Titanic competition](https://www.kaggle.com/c/titanic) competition, download its data files to the [data](./data) folder(s)
* Make sure you have an [Azure](https://azure.microsoft.com/en-us/) account with _some_ credits. The [free trial](https://azure.microsoft.com/en-us/free/) works great.
* Install either [Miniconda](https://conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/downloads). The Python 3.7 version 🐍
* Run the following commands inside this directory

```shell
conda env create -f env.yml -n titanic_automl
conda activate titanic_automl
python -m ipykernel install --user --name=titanic_automl

jupyter lab
```
* If something fails, let me know about it and I'll do my best to help you out.