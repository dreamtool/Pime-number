# Pime-number


#include<stdio.h>
 
main()
{
   int n, c = 2;
 
   printf("Enter a number to check if it is prime\n");
   scanf("%d",&n);
 
   for ( c = 2 ; c <= n/2; c++ )
   {
      if ( n%c == 0 )
      {
         printf("%d is not prime.\n", n);
	 break;
      }
   }
   printf("%d is prime.\n", n);
   return 0;
}
