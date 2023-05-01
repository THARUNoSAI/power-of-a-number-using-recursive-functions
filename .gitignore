#include <stdio.h>

int power(int x, int n) {
   if (n == 0) { 
      return 1;
   } else {
      return x * power(x, n-1);
   }
}
int main() {
   int x;
   printf("Enter the value of x: ");
   scanf("%d", &x);
   for (int n = 0; n <= 5; n++) {
      printf("%d to the power of %d is: %d\n", x, n, power(x, n));
   }
   return 0;
}
