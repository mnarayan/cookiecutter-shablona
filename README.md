# Cookiecutter Shablona

This project creates cookiecutter templates based on [shablona](https://github.com/uwescience/shablona). The cookiecutter template structure has been modeled after [cookiecutter-data-science](http://drivendata.github.io/cookiecutter-data-science/)


#### [Project homepage]


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------
If you initialize cookiecutter with the default variables, you will recreate the `shablona` template.


    cookiecutter https://github.com/mnarayan/cookiecutter-shablona



### Installing cookiecutter requirements 
------------

    pip install -r requirements.txt

### Running the tests
------------

    py.test tests
