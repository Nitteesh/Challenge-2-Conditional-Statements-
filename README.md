# Challenge-2-Conditional-Statements-
written by Nitteesh M for task 2 (mycapatain)
#include<stdio.h>
int b;
int main()
{
    printf("please Enter the marks out of 100\n\n\n");
    printf("Enter the marks for grades =");
    scanf("%d",&b);
    if(b>=101){
    printf("plze enter marks out of 100");
    }
    else if(b>=85) {
    printf("A grade");
    }
    else if(b>=70) {
    printf("B grade");
    }
    else if(b>=55) {
    printf("C grade");
    }
    else if(b>=40) {
    printf("D grade");
    }
    else if(b>0) {
    printf("F grade");
    }
    else{
    printf("Enter a valid marks");
    }
    return 0;
}
