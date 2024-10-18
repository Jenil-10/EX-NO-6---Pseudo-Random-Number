# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM
```
NAME: jenil pio j
REG NO: 212223220040

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
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d ", random_number);
    }
    return 0;
}
```

# OUTPUT
![Screenshot 2024-10-18 082551](https://github.com/user-attachments/assets/45238c9d-7128-429e-9414-f743e020992f)


# RESULT
   Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed successfully
