# creative programme on if and ifelse statement
 creative programme to undersand if and elseif statement
#include<stdio.h>
int main()
{
    int age;
    printf("Enter your age\n");
    scanf("%d", &age);

    printf("You have entered your age %d as your age\n", age);

    if(age>=18){

        printf("you can able to do marriage!");

    }

    else if(age>=10){

        printf("you have enter your age between 10 to 17 you can do BAALVIVAAH ");

    }

    else if(age>=2){

        printf("you have enter your age between 2 to 9 you are dudh peeta bacha");

        
    }

    else{

        printf("you cannot do marriage!");

    }

    return 0;


}