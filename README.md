# c-daire-cevre-alan
C programlama dilinde  yaptığım projeyi sunuyorum
lm presentıng the project l made on c 
#include <stdio.h>

int main(){
    float r,alan,cevre;
    const float pi = 3.1415;

    printf("Dairenin yaricapini giriniz");
    scanf("%f", &r);

    alan = pi * r * r;
    cevre = 2 * pi * r;

    printf("Alan: %f\n", alan);
    printf("cevre: %f\n", cevre);
    return 0;
}
