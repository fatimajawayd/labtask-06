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
```

## PROBLEM:07
Print fibonacci series upto 10 terms using a for loop.

```c
#include <stdio.h>
int main(void){
  int limit= 10;
  int i, n1=0, n2=1, n3;
    
  printf("Enter the limit for number of terms: ");
  scanf("%d", &limit);

  for(i= 1; i <= 10; i++){
     printf("%d\t", n1);
      n3 = n1 + n2;
      n1 = n2;
      n2 = n3;
  }
  return 0;
}
```

## PROBLEM:08
Check if a number is palindrome n = 121 using a while loop.

```c







## PROBLEM:09
Print multiplication table of a number entered by the user.

```c
#include <stdio.h>
int main(void){
  int num, i;

  printf("Enter the number: ");
  scanf("%d", &num);

  for(i = 14; i <= 10; i++){
    printf("%d\tx\t%d\t=\t%d\n", num, i, num*i);
  }
  return 0;
}
```

### PROBLEM:10
keep taking input until user enter zero

```c
#include <stdio.h>
int main(void){
  int num;
  printf("Enter number: ");
  scanf("%d", &num);

  while(num!=0){
    printf("Enter the number again: ");
    scanf("%d", &num);
  }
  printf("You entered zero\n");
}
```


