#include <stdio.h>

int main(){
   float Nbr1 ,Nbr2 ,result;

    printf("Entrer la valeur de Nbr1 : %f",Nbr1);
    scanf("%f",&Nbr1);

    printf("Entrer la valeur de Nbr2 : %f",Nbr2);
    scanf("%f",&Nbr2);

    if(Nbr1 == Nbr2){
        result = (Nbr1 + Nbr2)*3;
        printf("result : %.2f",result);
    }else{
        result = Nbr1 + Nbr2;
        printf("result : %.2f",result);
    }

}