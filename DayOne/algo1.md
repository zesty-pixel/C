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

# 3. To find the Area of a Rectangle

## Steps

1. Start
2. Input the length as l
3. Input the breadth as b
4. Set area=l*b
5. Print area
6. End

## Code
```c
#include <stdio.h>
#include <conio.h>

int main(){
  int l, b, area=0;
  clrscr();
  printf("Enter the length: ");
  scanf("%d", &l);
  printf("Enter the breath: ");
  scanf("%d", &b);

  area = l * b;

  printf("Area = %d", area);
  getch();
}
```

## Output
```bash
Enter the length: 5
Enter the breadth: 3
Area = 15
```