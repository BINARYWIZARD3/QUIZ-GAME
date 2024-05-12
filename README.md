# QUIZ GAME


#include<stdio.h>
int main(){
    int i;
    int ans1,ans2,ans3,ans4;
    int point1,point2,point3,point4,point5;
    int point01,point02,point03,point04,point05;
    printf("QUIZ GAME\n\n\n");
    printf("press 7 to start the game:\n\n");
    printf("press 0 to start the game:\n\n");
    scanf("%d",&i);
    if(i==7){
        printf("the game has been started:\n");
    }
    else if (i==0){
        printf("the game has ended:\n");
    }
    else {
        printf("invalid input\n");
    }
    if(i==7){
        printf("1) favourite color of yuvi\n");
        printf("1)BLACK\n");
        printf("2)YELLOW\n");
        printf("3) WHITE\n");
        printf("4)BLUE\n");
        printf("enter your answer:\n");
        scanf("%d",&ans1);
        if(ans1==1){
            printf("correct answer\n");
            point01=5;
            printf("you have scored %d points \n",point01);
            
            
        }
        else{
            printf("wrong answer");
        }
        printf("1) favourite food of yuvi\n");
        printf("1)PAV BHAJI\n");
        printf("2)PASTA\n");
        printf("3)DAL CHAWAL\n");
        printf("4)EVERYTHING\n");
        printf("enter your answer:\n");
        scanf("%d",&ans1);
        if(ans1==4){
            printf("correct answer\n");
            point01=5;
            printf("you have scored %d points \n",point01);
            
            
        }
        else{
            printf("wrong answer");
        }
        printf("1) favourite place of yuvi\n");
        printf("1)HOME\n");
        printf("2)GOA\n");
        printf("3) BOMBAY\n");
        printf("4)GOVINDNAGAR\n");
        printf("enter your answer:\n");
        scanf("%d",&ans1);
        if(ans1==1){
            printf("correct answer\n");
            point01=5;
            printf("you have scored %d points \n",point01);
            
            
        }
        else{
            printf("wrong answer");
        }
        printf("1)favourite clothe of yuvi\n");
        printf("1)lower - tshirt\n");
        printf("2)shirt\n");
        printf("3) skirt\n");
        printf("4)nexus\n");
        printf("enter your answer:\n");
        scanf("%d",&ans1);
        if(ans1==1){
            printf("correct answer\n");
            point01=5;
            printf("you have scored %d points \n",point01);
            
            
        }
        else{
            printf("wrong answer");
        }
        printf("1) which one is the first search engine in the internet?\n");
        printf("1)GOOGLE\n");
        printf("2)ALTAVISTA\n");
        printf("3) WAIS\n");
        printf("4)nexus\n");
        printf("enter your answer:\n");
        scanf("%d",&ans1);
        if(ans1==2){
            printf("correct answer\n");
            point01=5;
            printf("you have scored %d points \n",point01);
            
            
        }
        else{
            printf("wrong answer");
        }
        
    }
    
}
