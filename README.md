# PRML
Here's a `README.md` file for your Adaline Network implementation:

---

## Adaline Network for OR Function with Bipolar Inputs and Targets

This MATLAB script implements an Adaline (Adaptive Linear Neuron) network to solve the OR function using bipolar inputs and targets. The network adjusts its weights and bias based on the input patterns until the error convergence criterion is met.

## Problem Description

The OR function is a basic binary function that outputs 1 when at least one of its inputs is 1. In this implementation, the inputs and targets are represented in bipolar form:
- Input values: 1 or -1
- Target values: 1 or -1

## Script Details

### Input Patterns
- **x1**: [1, 1, -1, -1] (First input pattern)
- **x2**: [1, -1, 1, -1] (Second input pattern)
- **x3**: [1, 1, 1, 1] (Bias input)

### Target Vector
- **t**: [1, 1, 1, -1] (Expected output for OR function)

### Initial Weights and Bias
- **w1**: 0.1 (Weight for x1)
- **w2**: 0.1 (Weight for x2)
- **b**: 0.1 (Bias)

### Learning Rate
- **alpha**: 0.1 (Rate at which weights are updated)

### Error Convergence Criterion
- The loop continues until the total error **e** becomes less than or equal to 1.5.

### Epochs
- The script tracks the number of epochs (iterations) required for the network to converge.

### Weight Updates
- Weights and bias are updated based on the difference between the target output and the actual output for each input pattern.

### Output
- Final updated weights and bias are displayed after the network has converged.


## Author

**Arunachalam U**
