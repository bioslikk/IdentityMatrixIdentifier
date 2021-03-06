# IdentityMatrixIdentifier
Simple 8x3x8 neural network that identifies rows of an identity matrix. Uses Keras with the TensorFlow backend

The main.py file is a program that:
  
  a. Creates and initializes a 8x3x8 neural network
  
  b. Trains the network to learn the 8x8 identity matrix
  
  c. Outputs the neural network prediction for every row of
    the 8x8 identity matrix
    
![Figure 1](https://github.com/bioslikk/IdentityMatrixIdentifier/blob/master/matplotlib.png?raw=true)


### Running main.py
I recommended that you first create a virtual environment (python3.6 venv) to run this project.

Then you can install the requirements and run the script
```bash
pip install -r requirements.txt
python IdentityMatrixIdentifier/main.py
```

### Run in docker
You could also run this project in docker.
However, you will not be able to see the pretty matplotlib graph by running it this way.
```bash
docker run bioslikk/identity_matrix_identifier
```
##### Troubleshoot:

If you get the error "matplotlib module not found error: no module named 'tkinter'" 

Run the following:
```bash
sudo apt-get install python3-tk
```

