# shopping-list
#include <stdio.h>
#include <stdlib.h>

int main()
{
   char item1[2],item2[2];
   double item1_price,item1_quantity,item2_price,item2_quantity,total_cost,cash_to_pay,cash_paid ;
   printf("_____________\n");
   printf("POINT OF SALE\n");
   printf("_____________\n");


   printf("ENTER ITEM 1:");
   scanf("%s", &item1);
   printf("QUANTITY IN KGS:");
   scanf("%if",item1_quantity);
   printf("price per kg:");
   scanf("%if",&item1_price);
   printf("TOTAL COST: %.2if\n",item1_quantity*item1_price);

   printf("ENTER ITEM 2:");
   scanf("%s", &item2);
   printf("QUANTITY IN KGS:");
   scanf("%if",item2_quantity);
   printf("PRICE PER KG:");
   scanf("%if",&item2_price);
   printf("TOTAL COST: %.2if\n",item2_quantity*item2_price);
   printf("ALL ITEMS COST: %.2if\n",item1_quantity*item1_price+item2_quantity*item2_price);

   printf("ENTER CASH TO PAY::");
   scanf("%if",&cash_to_pay);
   printf("ENTER CASH PAID::");
   scanf("%if",&cash_paid);
   printf("CHANGE: %.2if",cash_paid);





    return 0;
}
