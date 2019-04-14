 //pointers
//This program shows the basic integer increment and decrement through pointers
# include<stdio.h>

int main()
{
int a,b,*x,*y;

x = &a;
y = &b;

printf("The initial address for a is :%x\n",x);
printf("The initial address for b is :%x\n",y);

printf("\n");

printf("The new address for a is :%x\n",x+1);
printf("The new address for b is :%x",y+1);

return 0;
}
