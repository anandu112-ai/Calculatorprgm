#include<stdio.h>
#include<math.h>

void main()
{
    float a,b,c,e,d,f;
    scanf("%f%f%f",&a,&b,&c);
    d=b*b-4*a*c;
    if (d>0)
    {    
        e=-b+sqrt(b*b-4*a*c);
        f=-b-sqrt(b*b-4*a*c);
        printf("The solutions are %f%f" ,e,f);
    }
    else if(d<0)
    {
        printf("It has imaginary roots" );
    }
    else
    {
        e=-b/2*a;
        printf("The solution is %f",e);
    }
}
