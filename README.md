
#include <stdio.h>

double add(double a, double b);

int main(void)
{
    double res;

    res = add(2.3,4.2);
    printf("res = %f\n", res);
    res = add(20.12,42.12);
    printf("res = %f\n", res);
    system("Pause");
    return 0;
}
double add(double a,double b)
{
 double sum;

 sum = a + b;  

 return sum;
}
