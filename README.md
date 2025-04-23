# EX-NO-6-Pseudo-Random-Number
## Name: Jackson Raj A
## Reg no: 212223040071

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
### Step1- Start the program and import the required libraries.
### Step2- Seed the random number generator using the current time(i.e) rand(time(0));
### Step3- Get the number of randon number to generate.
### Step4- Pass the value for number of iterations and print the numbers.
### Step5- End the program.

# PROGRAM:
```
 #include <stdio.h>
 #include <stdlib.h>
 #include <time.h>
 int main()
 {
 int count, min, max;
 printf("Enter the number of random numbers to generate: ");
 scanf("%d", &count);
 printf("Enter the minimum value: ");
 scanf("%d", &min);
 printf("Enter the maximum value: ");
 scanf("%d", &max);
 srand(time(NULL));
 printf("Pseudorandom numbers:\n");
 for (int i = 0; i < count; i++)
{
 int random_number = (rand() % (max- min + 1)) + min;
 printf("%d\n", random_number);
 }
 return 0;
 }
```

# OUTPUT:

![image](https://github.com/user-attachments/assets/b6edf87a-4095-4b89-b1eb-467929738932)


# RESULT:
The Program Excuted Successfully
