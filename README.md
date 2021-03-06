
# Welcome to Quzzi

- π Here you will find uses of the [DWave Quantum Annealer (QA)](https://cloud.dwavesys.com/leap) to solve various optimization problems.
- π± The work published here is for the purpose of demonstrating how I use the QA to solve real-world problems. Some of the real-world use cases includes βοΈ **airline crew planning optimization problems**. 
- Everything I learned since 2018 about coding for DWave can be found on the [DWave site](https://www.dwavesys.com/learn/resource-library/) and code examples after [signing up](https://cloud.dwavesys.com/leap/signup/)
- π‘ I aim to explain how I go about modeling a problem for the QA from a practical perspective. 
- ποΈ Iβm looking to collaborate with others who are looking at creating practical solvers to real work optimization problems.
- π« You can reach me at QuzziCode@gmail.com
- β€οΈ [Sponsor Quzzi!](https://github.com/sponsors/Q-Zee)

Some of the work will be open to collaborators.
Questions and comments welcomed.

### π₯ Start -> [here](https://q-zee.github.io)

# Why use a Quantum Annealer for optimization?

Quantum Annealing allows finding solutions to large combination problems that are hard to solve with classical computing and offers opportunities for breakthoughs in both speed and solution quality. Furthermore, to code solvers using such a Quantum computer does not require knowledge of physics (although it helps understand why it works). 

Where there are multiple "choices" to be made with consequences on cost/time as these choices interact with each other ... there is an opportunity to use the QA to find the best fit solutions where Classical computing can fail.

# What is the difference between Classical computing and Quantum Annealing solvers?

Here is a simplistic analogy: 

- πΆββοΈ One **tells** a classical computer **"how"** to solve a problem by **telling it the steps** (code) needed to construct a solution. It is like walking through a labyrinth until the exit is found. You might get exhausted before the end and never find the exit.

- π₯ The Quantum Annealer **"knows"** how to solve the problem by using a **quality rating function** one gives it (code) to compare its solutions. The paths to the labyrinth _"manifest"_ themselves and the ones leading to exits rank at the top of the list of possible solutions.

