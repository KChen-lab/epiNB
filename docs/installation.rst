Installation
=======================

Right now epiNB is avaialbe on GitHub. Before installation, we highly recommend that you create a new virtual environment by::

    conda create -n epinb python=3.9

If conda is not yet installed, you can refer to https://docs.conda.io/en/latest/miniconda.html for ways to install. After creating the environment, entering it by::

    conda activate epinb

Then you can run::

    git clone https://github.com/KChen-lab/epiNB.git
    cd epiNB
    pip install .

to install the package from GitHub. 

You can rerun the tutorails in docs to verify your installation. However, we only included minimal dependencies in the installation. Thus, to run the tutorials, you may need additional packages. You can install them by running::

   conda install jupyter matplotlib scikit-learn
   conda install -c conda-forge wordcloud
   conda install -c bioconda logomaker

