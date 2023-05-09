#include <stdio.h>

int main() {
    int a=5, b=6;
   b=a+b;
  a=b-a;
  b=b-a;
  printf("%d\n",a);
  printf("%d",b);
    return 0;
}
