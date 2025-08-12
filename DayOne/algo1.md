# 1. To print the message "Welcome to the world of C programming"

## Steps
1. Start
2. Print "Welcome to the world of C programming"
3. End

## Code
```c
#include <stdio.h>
#include <conio.h>

void main() {
  clrscr();
  printf("Welcome to the world of C programming");
  getch();
}
```

## Output
```bash
Welcome to the world of C programming
```

# 2. To find the sum of two numbers.

## Steps
1. Start
2. Input first number as a
3. Input second number as b
4. Set sum=a+b
5. Print sum
6. End

## Code
```c
#include <stdio.h>
#include <conio.h>

void main(){
  int a, b, sum=0;
  clrscr();
  printf("Enter first number: ");
  scanf("%d", &a);
  printf("Enter second number: ");
  scanf("%d", &b);

  sum = a + b;

  printf("Sum = %d", sum);
  getch();
}
```

## Output
```bash
Enter first number: 5
Enter second number: 4
Sum = 9
```
