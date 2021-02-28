#include<stdio.h>
main()
{
printf("pick a food item :\n1. Sandwich,Rs-149\n2. French Fries,Rs-99\n3. Pasta,Rs-179\n4. Burger,Rs-129\n5. pizza,Rs-239");
int choice=0;
scanf("%d",&choice);
switch(choice)
{
case1:printf("you picked sandwich,Rs-149.");
break;
case2:printf("you picked Freanch Fries,Rs-99.");
break;
case3:printf("you picked Pasta,Rs-179.");
break;
case4:printf("you picked Burger,Rs-129.");
break;
case5:printf("you picked pizza,Rs-239.");
break;
default:printf("invalid choice") ;
}
}
