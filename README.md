//# Let-Us-C-chapter1-question5
#include<stdio.h>
int main()
{
int length,breadth,radius;
printf("Enter the length of rectangle:");
scanf("%d",&length);
printf("Enter the breadth of rectangle:");
scanf("%d",&breadth);
printf("Enter the radius of circle:");
scanf("%d",&radius);
printf("Area of rectangle is : %d",length*breadth);
printf("Perimeter of rectangle is:%d",2*(length+breadth));
printf("Area of circle is: %f",3.14*radius*radius);
printf("Circumference of circle is:%f",2*3.14*radius);
return 0;
}
