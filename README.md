# EX-NO-6-Pseudo-Random-Number
# Name:Vaishak.M
# Register No:212224040355
# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Random numbers are:\n");

    for (i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}
```
# OUTPUT:

<img width="1628" height="756" alt="Screenshot 2026-10-28 090533" src="https://github.com/user-attachments/assets/497ba32b-9a79-4aac-a8a9-2d8b6b10b3f8" />

# RESULT:
Thus the implementation of pseudorandom number generation had been executed successfully.
