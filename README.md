### NAME: SURYA P <br>
### REG NO: 212224230280

# EX 2 : BOOLEAN FUNCTION MINIMIZATION

## AIM : 

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## EQUIPMENTS REQUIRED :

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## THEORY :

Boolean function minimization is a fundamental concept in digital logic design aimed at reducing the complexity of logical expressions while maintaining their functionality. Here are a few theoretical perspectives on Boolean function minimization:

**Karnaugh Maps (K-Maps) :**

Karnaugh Maps provide a graphical method for minimizing Boolean functions. They visually represent all possible combinations of input variables and their corresponding output values. By identifying adjacent groupings of 1s (or 0s) in the map, you can derive simplified expressions. This method is particularly useful for functions with a small number of variables, as it can become impractical for larger functions.

**Quine-McCluskey Algorithm :**

The Quine-McCluskey algorithm is a systematic approach to minimizing Boolean functions. It involves systematically combining minterms (or maxterms) to identify prime implicants, which are the smallest possible groupings that cover all essential terms. These prime implicants are then used to derive the minimized expression. While more computationally intensive compared to K-Maps, the Quine-McCluskey algorithm is efficient for functions with a larger number of variables.

**Implicant-Based Minimization :**

Boolean function minimization can also be approached by identifying essential prime implicants and eliminating redundant terms. Essential prime implicants are those that cover output states not covered by any other implicant. Redundant terms, on the other hand, can be eliminated if they are subsumed by other terms or combinations of terms. This approach is often used in combination with K-Maps or the Quine-McCluskey algorithm.

**Algebraic Manipulation :**
Boolean functions can also be minimized using algebraic manipulation techniques. These techniques involve applying Boolean algebra laws such as absorption, distribution, and complementation to simplify expressions. While algebraic manipulation can be intuitive for some functions, it may not always result in the most optimized expressions, especially for functions with many variables.

## TRUTH TABLE :

![tt1](https://github.com/user-attachments/assets/bb2c6e4e-e451-468a-8c83-0169e2858e6b)

![tt2](https://github.com/user-attachments/assets/a7c8cde3-a8e4-4a87-874f-7292621bf221)


## PROCEDURE :

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM :

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

![Screenshot 2025-03-20 113633](https://github.com/user-attachments/assets/31314b27-57dd-46ad-a0d9-66949c1ca878)

## OUTPUT :

## RTL REALISATION :

![Screenshot 2025-03-20 112605](https://github.com/user-attachments/assets/c97e1d50-3d37-48c0-9511-311f388f0019)

## TIMING DIAGRAM :

![Screenshot 2025-03-20 113523](https://github.com/user-attachments/assets/75d87c42-4dd3-4320-9125-cbf217dbdabf)


## RESULT :

Thus the given logic functions are implemented and their operations are verified using Verilog programming.
