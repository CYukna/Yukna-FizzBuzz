# Yukna-FizzBuzz
FizzBuzz Assignment

#include <stdio.h>
{
  int i;
  for (i=1;i<=100;i++)
  {
    if(i%3==0)
      printf("Fizz\n");
    if(i%5==0)
      printf("Buzz\n");
    if((i%3 !=0) && (i%5 !=0))
      printf("%d\n",i);
   }
  return 0;
 }
