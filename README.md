#ASP Challenge 2019 Implementation

This is my solution for the Automated Warehouse Scenario proposed by the [ASP Challenge 2019](https://sites.google.com/view/aspcomp2019/problem-domains). I have successfully implemented the solution. Below, you'll find the directory structure of the project:

- Instances
  - This folder contains various initialization files used to check the system's functionality.
    - inst1.asp
    - inst2.asp
    - inst3.asp
    - inst4.asp
    - inst5.asp

- convert_input.asp
  - This file converts the input file schema into a more readable and understandable form, which we used to implement the project's constraints.

- parsing.asp
  - This file contains code for obtaining various values, such as the number of objects and their types in the system.

- demo.asp
  - This is the main file where the code for all the constraints resides.

- description.pdf
  - This PDF file contains the problem statement and a description of the system.

- script.py
  - This is a Python file that facilitates the execution of the program.

## How to Run
1. Ensure that you have **Python** configured on your system.
2. Make sure you have **clingo** configured on your system.
3. Download the project into a suitable folder on your local computer.
4. Run the **script.py** file to test the project.

## Command Lines and Outputs of All the Instances

#### Instance 1
After running the command: `python script.py` and selecting instance 1:

- The program outputs the following result:

```
| code   |  Instance File    |
|--------:|:----------------:|
| 1      |  inst1.asp        |
| 2      |  inst2.asp        |
| 3      |  inst3.asp        |
| 4      |  inst4.asp        |
| 5      |  inst5.asp        |

Please enter the code for the instance file: 1

---------- RUNNING ----------

[Detailed output of the clingo solver for Instance 1]
```

#### Instance 2
After running the command: `python script.py` and selecting instance 2:

- The program outputs similar information as for instance 1, but with the detailed output of the clingo solver specific to instance 2.

#### Instance 3, 4, 5
The process is repeated for instances 3, 4, and 5, with the program displaying similar information and detailed solver outputs for each instance.

This implementation provides a systematic approach to solving the Automated Warehouse Scenario using Answer Set Programming (ASP) concepts and tools.
