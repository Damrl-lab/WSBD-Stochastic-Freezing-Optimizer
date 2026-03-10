The code in this folder is only for the MNIST problem using SGD and WSBD-SGD. 

We reccomend running the pennylane version in the Pennylane/MNIST folder as it runs significantly faster, having access to GPU acceleration (you can use lightning.gpu instead of default.qubit as device), and having all comparison optimizers like the WSBD variants or the gradient free methods. 

However if you are planning on using an IBM Quantum device this code will be more useful. 