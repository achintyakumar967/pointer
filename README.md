# pointer
// Online C compiler to run C program online
#include <stdio.h>

int main() {
   int a=10,*ptr;
   printf("enter the value of a :");
   scanf("%d",&a);
   ptr=&a;
   printf("value of a=%d\n",a);
   printf("address of a=%p\n",a);
   printf("value of ptr(address of a)=%p\n",ptr);
   printf("value of ptr(Dereferencing ptr)=%d",*ptr);
    return 0;
}
