# Tensorflow Examples

This is a collection of Tensorflow examples. Currently, all the examples are submodules of git.

## Checkout

    git clone --recursive https://github.com/YaleHuang/tensorflow-examples.git
    
## Run Docker Instance

    nvidia-docker run -it -p 8888:8888 -p 6006:6006 -v /home/user/work/tensorflow_examples:/notebooks/tensorflow_examples -v /home/user/data:/data:ro --name tensorflow tensorflow/tensorflow:latest-gpu /run_jupyter.sh --NotebookApp.token=''
