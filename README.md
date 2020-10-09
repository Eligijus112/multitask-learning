# multitask-learning

Multitask learning implementation in python using tensorflow.

# Activating the virtual environment

For the creation of virtual environments (VE) anaconda is used. You can download anaconda via here: https://www.anaconda.com/distribution/

```
# Creating the base for the environment
conda create python=3.7 --name multitask

# Activating it 
conda activate multitask

# Populating the environment with packages
pip install -r requirements.txt
```

# Building the docker image 

The environment creation is automated through docker. 

```
sudo docker-compose build 
sudo docker-compose up 
```

This will create a jupyter instance that can be accesed via port 8080. 

# Analysis 

The full analysis and code is located in **multitask-learning.ipynb**.