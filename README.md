Requirements: Python 3.9, Qiskit 0.30

To run from command line:
python task1.py "input vector"

The "input vector" should be a string of comma separated integer values with no
spaces. Example "input vector":
'10,3,2,5'
'5,10,1,2'
'2,3,4,5,10,6'

It is assumed that there are at least 2 elements in the input vector, and that
there are only 2 elements that contain an alternating bit pattern. It is also
assumed that the base problem is 4 elements within the input vector.

This implementation has been extended such that it can handle input vectors
with more than 4 elements, and generates the circuit using Grover's algorithm
on the address space.

The program prints the resulting Quantum Circuit and the resulting simulation.