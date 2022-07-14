# Snack-Shop
// Author solomon Ayoo Omandi
#include <stdio.h>
#include <stdlib.h>
// Relational operators: > < <= >= == !=
// Logical operators: && || !
// Control structures
// 1. selection/decision making/ conditional - if
int menu();
int main()
{
    printf("Welcom to NINE ELEVEN CAFE\n");
    menu();
    return 0;
}
int menu(){
int item;

printf("1. chapati - ksh. 50\n");
printf("2. samosa - ksh. 40\n");
printf("3. coffe - ksh. 100\n");
printf("Enter item No: ");
scanf("%d", &item);

if(item > 0 && item <= 3){
        printf("item added to cart\n");
}

else{
    printf("invalid item\n");
    menu();
    }return item;

}
