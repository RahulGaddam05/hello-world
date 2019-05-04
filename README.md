# include<stdio.h>  
void swap(int a,int b);
void main() 
{ 
int x,y; 
printf("enter the values of x and y"); 
scanf("%d %d",&x,&y); 
swap(x,y);  
}
void swap(int a,int b) 
{ 
int t; 
t=a; 
a=b; 
b=t; 
printf("the value of x is %d",b); 
printf("the value of y is %d",a); 
}

  
  
  
  
  
  
  
  
  
  
  
  
  
