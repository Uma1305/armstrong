#include <stdio.h>
int main(){
    int num,no,rem,sum=0;
    
    printf("enter the num:");
    scanf("%d",&num);
    num=no;
    while(num!=0)
    {
       rem=num%10;
       sum=sum+(rem*rem*rem);
       num=num/10;
    }
    if(no==sum)
    printf("armstrong");
    else{
    printf("not armstrong");}
    return 0;
    
   
    
}
output:
enter the number:153
armstrong number
