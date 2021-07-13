# Calculating-Simple-Interest-

// program to calculate simple interest
//simple interest =(p*r*t)/100
#include<stdio.h>

int main()
{

    // variable declaration 
 float p,r,t,SI;
printf("please enter p,r,t /n");
scanf("%f%f%f",&p,&r,&t);
SI =(p*r*t)/100;
printf("Simple Intrest=%f/n",SI);
  
    return 0;
}
