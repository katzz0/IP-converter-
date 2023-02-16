                                                    TRI-PLINK

This program was made by our team Tri-PLink.We are software engineer students and this is our project for A semester in C.
We created a program that will take as input an ip to decimal or binary format and will be converted to decimal or binary
respectively.

![218562224-5f84be40-8bba-45e4-b0cd-9a52280c2867](https://user-images.githubusercontent.com/116751641/219417315-33b12c44-3a79-495f-91e1-2b45237448a1.png)




With this project we wanted to be more experienced using:

1-C programming language syntax and structure

2-Functions and how to call them

3-Data types, such as int and char

4-Scanf and printf functions to input and output data

5-Loops, such as while and for loops

6-Basic mathematics, specifically powers and remainders

7-Arrays and how to store and manipulate data in arrays

8-The basic concept of IP addresses and their binary and decimal representations

First we see the menu of this C program where the user is prompted to enter a choice of 'a' or 'b'. If the user enters 'a', the program will ask for an IP address in decimal format, validate its format and range, and then convert it to binary. If the user enters 'b', the program will ask for the octets of an IP address in binary format, validate their range, convert each of the octets from binary to decimal, and then print the IP address in decimal format. The menu is implemented using an if-else statement, and the conversion between decimal and binary is done using two functions, decimal_to_binary() and binary_to_decimal().


![219124202-1877a3af-c9de-47a9-b8a1-07b4014c04a6](https://user-images.githubusercontent.com/116751641/219417454-0613f413-bad2-497f-9925-1df7099b934a.png)



The program has two main functions,a)decimal to binary  and b)binary to decimal.

A)The decimal to binary function takes a decimal number as an argument and prints its binary equivalent. This is achieved by repeatedly dividing the decimal number by 2 and storing the remainder, which is the next most significant bit of the binary number. The bits are stored in an array and then printed in reverse order, starting from the most significant bit to the least significant bit.


![219147191-6eabdd79-9314-42dd-90fb-0106a545d6a8](https://user-images.githubusercontent.com/116751641/219417510-e4e2759d-6227-4c58-90d9-b17a6b5b11f7.png)





B)The binary to decimal function takes a binary number as an argument and returns its decimal equivalent. This is achieved by converting each digit of the binary number to its corresponding power of 2 and summing these values up. The binary number is first divided by 10 to extract its last digit, which is then multiplied by 2^0, since the last digit is the least significant bit. This process is repeated until the entire binary number has been processed.


![219147191-6eabdd79-9314-42dd-90fb-0106a545d6a8](https://user-images.githubusercontent.com/116751641/219422553-8e1ce5f6-3e6b-4a08-8e8e-16ea1a11daf7.png)





The main function first displays an ASCII art header and then prompts the user to enter either 'a' to convert from decimal to binary or 'b' to convert from binary to decimal. If the user enters 'a', the program asks for an IP address in decimal format, and the IP address is then converted to its binary equivalent using the decimal_to_binary function. If the user enters 'b', the program asks for each of the four octets of the IP address in binary format, converts each of them to decimal using the binary to decimal function, and then prints the IP address in decimal format. If the user enters an invalid choice, the program prints an error message and terminates.


<h1 style="font-size:36px">Getting Started</h1>

- &nbsp;&nbsp;&nbsp;These instructions will get you a copy of the project up and running on your local machine.

<h1 style="font-size:36px">Prerequisites</h2>

- &nbsp;&nbsp;&nbsp;A C compiler (e.g. GCC).


<h1 style="font-size:36px">Installing</h3>

- &nbsp;&nbsp;&nbsp;Clone the repository to your local machine.

To clone this repository

```
git clone https://github.com/<Vgvg777>/IP-Converter.git
```

<h1 style="font-size:36px">Compile the source code.</h4>

```
gcc IP-Converter.c -o IP-Converter
```

<h1 style="font-size:36px">Usage.</h5>

- &nbsp;&nbsp;&nbsp;Run the compiled program.

```
./IP-Converter
```

<h1 style="font-size:36px">Contributing</h5>

- &nbsp;&nbsp;&nbsp;If you would like to contribute to the development of this program, feel free to submit a pull request.


