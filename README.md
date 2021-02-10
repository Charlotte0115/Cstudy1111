#include <stdio.h>

int main(void)
{
    int a = 10, b = 20, res = 0;
    add_by_pointer(&a, &b, &res);
    printf("%d", res);
    return 0;
}
