# Custom Swish Activation Implementation

This project implements a custom Swish activation function using PyTorch’s autograd.Function.
The forward and backward passes were defined manually to control how gradients are calculated.

The correctness of the gradients was verified using torch.autograd.gradcheck.
The custom activation was then used in a small neural network and trained on a simple dataset.
The training loss decreased over epochs, showing that the custom autograd function works correctly.

## Project Created By  
**Shubhangi Yadav**   
---

## DELIVERABLES
Custom Swish autograd function

Gradient checking code using gradcheck

Training script using the custom activation


---

## HOW TO SET UP AND RUN 

pip install torch numpy


python easy_swish.py


