# Function---C
C program performing the addition using Function.


#include<stdio.h>
#include<conio.h>
int fun(int , int );
int main()
{
  int a, b , sum;
  printf("enter the two values:");
  scanf(" %d %d ", &a , &b );
  sum = fun(a,b);
  printf("sum is %d",sum);
  return 0;
}
  int fun(int x, int y)
  { int c; 
    c = x + y;
    return(c);
  }
  
  
  
