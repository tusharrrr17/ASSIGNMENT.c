#include <stdio.h>
#include <math.h>

int armCheck(int n) {
    int result=0;
    int rim;
    int OG = num;
    while (OG != 0) {
        
        rim = OG % 10;
        
        result += pow(rim,3);
        OG /= 10;
        
    }
    if (result == n){
        return printf("%d is an Armstrong number.", n);
    }
    else{
        return printf("%d is not an Armstrong number.", n);
    }
}
int main() {
    int n;
    printf("Enter a Three Digit Integer --> ");
    scanf("%d", &n);
    armCheck(n);
    return 0;
}
