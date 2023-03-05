# Quantum Computing and Quantum Machine Learning-

Quantum Computing helps us to extend the set of physical laws computer act upon by accessing quantum aspects of physical world.One of the very important phenomenon which allows quantum computers to access many possibilites at
once is superposition. However, one major obstacle in the development of quantum computing is the need for a scalable and fault-tolerant device capable of implementing quantum algorithms. Current quantum hardware is either small or noisy, making error correction a critical challenge.Quantum devices for useful algorithms require error correction, and architectures that can correct errors faster than they occur are called fault-tolerant.One of the things that had a major impact on quantum computing recently was Google's work Supressing the quantum errors by scaling code on logical qubit.


When we group multiple physical qubits together to create a logical qubit, the result is often that the logical error rate of the group is worse than the error rate of a single physical qubit because every additional qubit that is added is another potential source of error.Google implemented a distance-3 error correction code in their Sycamore processor by grouping 17 qubits together to acheive logical error rate of 3.028%. On grouping
49qubits using distance-5 code they got an logical error rate of 2.914%.This work demonstrates that with enough care, we can produce the logical qubits necessary for a large-scale error-corrected quantum computer.
This work could help to revolutionize the field of Quantum machine learning and may help us solve complex problems that are beyond the reach of classical machine learning algorithms.

# Familiar Quantum Algorithms-

I have been reading about quantum computing on qiskit and pennylane websites. Qiskit's textbook Learn Quantum Computation using Qiskit has introduced me to various quantum algorithms like Deutsch-Jozsa Algorithm,Simon's Algorithm,Shor's Algorithm,Grover's Algorithm and more.
I liked Shor's algorithm and how it could do factoring of integers in polynomial time when the best known classical algorithm needed superpolynomial time to factor the product of two primes.It uses the concept of quantum phase estimation on Unitary operator to find the period of a periodic function, which can be used to factor a number into its prime factors.Shor's Algorithm has found many uses in cryptographic systems like RSA.

# Familiar Quantum Software-
I have used pennylane , qiskit and torchquantum the most in quantum libraries.For the tasks in QML HEP I have used pennylane to solve them.I have quite little experience in Cirq and Tensorflow quantum.Since I have machine learning experience in both PyTorch and Tensorflow/Keras I feel learning Cirq and Tensorflow quantum wouldn't take much time. One of the reasons why I liked pennylane and qiskit a lot is because of pennylane's support with both PyTorch and Tensorflow/Keras and their huge open source community support.Also both of them have a very good  documentation providing very good insights for those who are totally new to quantum computing and quantum machine learning.

# References-
[Learn Quantum Computation using Qiskit]

[Learn Quantum Computation using Qiskit]:https://qiskit.org/textbook/preface.html

[Pennylane]

[Pennylane]:https://pennylane.ai/

Google's Blog on [Suppressing quantum errors using by scaling code on logical qubit]

[Suppressing quantum errors using by scaling code on logical qubit]: https://r.search.yahoo.com/_ylt=AwrPoa8kgwRkNocD4CC7HAx.;_ylu=Y29sbwNzZzMEcG9zAzIEdnRpZAMEc2VjA3Ny/RV=2/RE=1678046116/RO=10/RU=https%3a%2f%2fai.googleblog.com%2f2021%2f08%2fdemonstrating-fundamentals-of-quantum.html/RK=2/RS=BE7zTRL2R9kxYNaFDw6axQalOcc-

[Google’s improved quantum processor good enough for error correction]

[Google’s improved quantum processor good enough for error correction]: https://arstechnica.com/science/2023/02/google-shows-current-generation-qubits-good-enough-for-error-correction/
