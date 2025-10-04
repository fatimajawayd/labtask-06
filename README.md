# labtask-06

## PROBLEM:01
Print even numbers from 2 to 20 using a for loop

```c
#include <stdio.h>

int main(void){
  int i;
  //print even numbers from 2 to 20
  printf("Even numbers:\n");

  for(i=1; i<=20; i++) {
        if(i%2 == 0){
            printf("%d\n", i);
        }      
    }
}
```

## PROBLEM:02
Print odd numbers from 1 to 20 using a while loop.

```c
#include <stdio.h>
int main(void){
  int i=1;
  printf("Odd numbers:\n");

  while(i<=20){
      if(i%2 != 0){
            printf("%d\t", i);
        }
        i++;
    }
}
```

## PROBLEM:03 
Print numbers from 10 down to 1 using a for loop.

```c
#include <stdio.h>
int main(void){
    int i;
    printf("Numbers from 10 to 1\n");

    for(i=10; i>=1; i--){
        printf("%d\t", i);
    }
}
```

## PROBLEM:04
Find the sum of numbers from 1 to 100 using a for loop.

```c
#include <stdio.h>
int main(void){
    int i;
    int sum = 0;
    printf("Sum of numbers from 1 to 100: ");

    for(i=1; i<=100; i++){
        sum +=i;
    }
    printf("%d", sum);
}
```

## PROBLEM:05
Find the factorial of a number (n=5) using a for loop.

```c
#include <stdio.h>
int main(void){
    int factorial = 1;
    int n = 5;
    int i;

    for(i=1; i<=n; i++){
        factorial *= i;
    }
    printf("The factorial of 5 is: %d", factorial);
}
```

## PROBLEM:06
Check if a number is prime (n=7) using a for loop.

```c
