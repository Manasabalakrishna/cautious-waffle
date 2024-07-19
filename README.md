#include <stdio.h>
void cbr(int x, int y); 
int main()
{
    int a = 5, b = 10;
    printf("first a=%d, b=%d\n", a, b);
    cbr(a, b);
    printf("second a=%d, b=%d\n", a, b);
    return 0;
}
void cbr(int x, int y)
{
    x=11;
    y=12;
    printf("third x=%d, y=%d\n", x, y);
}
