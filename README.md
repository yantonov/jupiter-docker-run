These scripts help to use python machine learning libraries through docker images.

Docker file provides:
1. [anaconda](https://anaconda.org/anaconda/python)
2. [jupiter](http://jupyter.org/)
3. [gensim](https://radimrehurek.com/gensim/)
4. [pybrain](https://github.com/pybrain/pybrain)
5. [bigartm](https://github.com/bigartm/bigartm)

Usage:  

Add 'python3', 'python2' directories of this repository to PATH variable.

For python 3:
```bash
jupiter-notebook.sh
```
For python 2:
```bash
jupiter-notebook-python2.sh
```
After that you can connect to notebook at localhost:8888, current working directory will be mounted also.

Links:
1. [Anaconda docker files](https://github.com/ContinuumIO/docker-images)
2. [jupiter-python3 at docker hub](https://hub.docker.com/r/yantonov/jupiter-python3/)
3. [jupiter-python2 at docker hub](https://hub.docker.com/r/yantonov/jupiter-python2/)
