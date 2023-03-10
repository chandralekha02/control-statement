#include<stdio.h>
int main(){
    int num;
    printf("Enter first number :");
    scanf("%d", &num);
    if(num%3==0 && num%5==0){
        printf("Number is good number : %d", num);
    }
    else if(num%3==0 && num%5!=0){
        printf("Number is bad number : %d", num);
    }
    else if(num%3!=0 && num%5==0){
        printf("Number is poor number : %d", num);
    }
    else{
        printf("-1");
    }
    return 0;
}
