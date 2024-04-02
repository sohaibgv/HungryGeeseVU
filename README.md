# How to run this project

Follow the steps below

## Prerequisites

Our experiments were performed on Windows 11 using Python 3.7.9 in an Anaconda virtual environment,
with a GPU to accelerate computations. We utilized Jupyter Notebook for its interactive interface,
requiring the installation of the CUDA developer toolkit and CUDA cuDNN for GPU acceleration in
deep learning. This setup ensures our experiments can be easily replicated.

### Experimentation setup

- **Step 1:** Clone the Github repository git clone https://github.com/sohaibgv/HungryGeeseVU.git
- **Step 2:** Navigate into the directory
- **Step 3:** Locate the environment.yml
- **Step 3:** Create a python Virtual Environment conda env create -f environment.yml
- **Step 4:** Activate Virtual Environment conda activate hungry geese
- **Step 5:** Confirm installed Dependencies conda env list
- **Step 6:** Start the Jupyter server jupyter notebook
- **Step 7:** Select a notebook and run it to reproduce experiments.
