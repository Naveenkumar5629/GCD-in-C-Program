# GCD-in-C-Program
#include <stdio.h>

int main() {
    int a,b,GCD;
    scanf("%d%d",&a,&b);
    for(int i=1;i<=a && i<=b;i++){
        if(a%i==0&&b%i==0){
            GCD=i;
        }
    }
    printf("%d",GCD);
    return 0;
}
