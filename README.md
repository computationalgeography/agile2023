# Geosimulation using fields and agents

This repository holds a Jupyter notebook demonstrating the Daisyworld model implementation in Campo,
a YAML file to create the Python environment required to run the model,
and necessary scripts for pre- and postprocessing.

You can run the Jupyter notebook either online using Google Colab, or locally on your own computer.

More information will be given in the [Agile 2023 workshop](https://agile-online.org/conference-2023/programme-2023/agile-workshops-2023).


## Running online in Google Colab

You need a Google account to run the notebook.

 1. Open the notebook using the following link: [Colab notebook](https://colab.research.google.com/drive/1CulW5WUEbzsvqkiuGtiuehf4vq8OYlkA?usp=sharing)

 2. Create a copy of the notebook in your own Google Drive by using the *Copy to Drive* button.

 3. After copying you can run the notebook. The first code cell will install the required software and may take a few minutes to complete.


## Running on your local machine

### How to install

A few steps are required to run the Jupyter notebook.
General information on Jupyter notebooks and manuals can be found [here](https://jupyter.readthedocs.io/en/latest/).
The user guide and short reference on Conda can be found [here](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html).

 1. You will need a working Python environment, we recommend to install Miniconda. Follow their instructions given at:

    [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)

 2. Open a terminal (Linux/macOS) or Miniconda command prompt (Windows) and browse to a location where you want to store the course contents.

 3. Clone this repository, or download and uncompress the zip file. Afterwards change to the `agile2023` folder.

 4. Create the required Python environment:

    Linux/macOS:

    `conda env create -f environment/environment.yaml`

    Windows:

    `conda env create -f environment\environment.yaml`


The environment file will create a environment named *agile2023* using Python 3.11. In case you prefer a different name or Python version you need to edit the environment file.


### How to run

Activate the environment in the command prompt:

`conda activate agile2023`

Then change to the `notebook` folder.
You can now start the Jupyter notebook from the command prompt. The notebook will open in your browser:

`jupyter lab course.ipynb`


## Further reading

Background on DaisyWorld:

  [https://en.wikipedia.org/wiki/Daisyworld](https://en.wikipedia.org/wiki/Daisyworld)

Scientific literature about Campo and LUE:

  M.P. de Bakker, K. de Jong, O. Schmitz, D. Karssenberg (2017). Design and demonstration of a data model to integrate agent-based and field-based modelling. Environmental Modelling & Software, 89, 172-189, DOI: [10.1016/j.envsoft.2016.11.016](https://doi.org/10.1016/j.envsoft.2016.11.016).

  K. de Jong, D. Karssenberg (2019). A physical data model for spatio-temporal objects. Environmental Modelling & Software, 122, 104553, DOI: [10.1016/j.envsoft.2019.104553](https://doi.org/10.1016/j.envsoft.2019.104553).

  K. de Jong, D. Panja, M. van Kreveld, D. Karssenberg (2021). An environmental modelling framework based on asynchronous many-tasks: Scalability and usability. Environmental Modelling & Software, 139, 104998, DOI: [10.1016/j.envsoft.2021.104998](https://doi.org/10.1016/j.envsoft.2021.104998).


[https://campo.computationalgeography.org/](https://campo.computationalgeography.org/)
