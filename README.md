# student-information
#include<stdio.h>{ int main() 
char name[50];
int age;
char address[100]; 
printf("enter the name of the student\n") ;
scanf("%s",name );
printf("enter the age of the student\n ");
scanf("%d",&age);
printf("enter the address of the student\n ") ;
scanf("%s[^\n]",address);
printf("\n the student information\n");
printf("name:\n",name);
printf("age:\n",age );
printf("address:\n",address);
return 0;}
