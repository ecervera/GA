# Genetic Algorithms

[Jupyter notebooks](https://jupyter.org/) with exercises of [genetic algorithms](https://en.wikipedia.org/wiki/Genetic_algorithm) with [Python](https://www.python.org/) and [Pyevolve](http://pyevolve.sourceforge.net/0_6rc1/).

## Prerequisites

* [Docker](https://docs.docker.com/v17.09/engine/installation/)

## Usage
Run in a terminal:

    git clone https://github.com/ecervera/GA.git
    cd GA
    docker build --rm -t ga .
    docker run -it --rm --volume="$(pwd):/home/jovyan/work:rw" \ 
      -p 8888:8888 ga start.sh jupyter lab --NotebookApp.token=''
      
Open this URL in your favourite browser: [http://localhost:8888/lab/tree/work/index.ipynb](http://localhost:8888/lab/tree/work/index.ipynb)
