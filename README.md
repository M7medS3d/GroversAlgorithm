# GroversAlgorithm
The Grover's Search algorithm is a quantum algorithm for searching an unsorted database with N entries in $O(\sqrt{N})$ time. Classically, it would take O(N) time where we would need to search all entries in order to find the desired one. While this is only a quadratic speedup, it is quite significant when $N$ is large.

Unlike many other quantum algorithms that solve a 'blackbox' problem, the Grover's Search Algorithm solves a searching problem wherein the purpose is the locate on particular state with a measurement, out of $2^N$ possible states. While it's described as a 'searching' algorithm, a more accurate description would be 'inverting' a function. Essentially, given function $y=f(x)$, the algorithm allows us to calculate $x$ (input into database) when given $y$ (output of database).

Use Cases for Grover's Algorithm
Estimating the mean and media of a set of numbers
Solving the collision problem
Solving NP complete problems
May have interesting applications in DNA Structure
Below, I'll implement the Grover's Search algorithm on 3, and 4 qubits. In quantum computing (unlike classical computing), the number of possible states is $2^N$ so 2 qubits = 4 states, 3 qubits = 8 states, and 4 qubits = 16 states.
