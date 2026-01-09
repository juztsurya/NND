import math
def relu(x):
return max(0, x)
def sigmoid(x):
return 1 / (1 + math.exp(-x))
free = 1
win = 0
offer= 1
h1_input = (free * 0.5) + (win* -0.2) + (offer * 0.3)
h1_output = relu(h1_input)
h2_input = (free * 0.4) + (win* 0.1) + (offer* -0.5)
h2_output = relu(h2_input)
print("H1 input:", h1_input)
print("H1 output (ReLU):", h1_output)
print("H2 input:", h2_input)
print("H2 output (ReLU):", h2_output)
output_input = (h1_output * 0.7) + (h2_output * 0.2)
final_output = sigmoid(output_input)
print("Output neuron input:", output_input)
print("Final output (Sigmoid):", final_output)
