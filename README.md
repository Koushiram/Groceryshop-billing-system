#include <stdio.h>

 int
main ()
{
  
int numItems;
  
float price, quantity, total = 0;
  
 
printf ("Enter the number of items: ");
  
scanf ("%d", &numItems);
  
 
for (int i = 1; i <= numItems; i++)
    {
      
printf ("Enter the price of item %d: ", i);
      
scanf ("%f", &price);
      
 
printf ("Enter the quantity of item %d: ", i);
      
scanf ("%f", &quantity);
      
 
total += price * quantity;
    
} 
 
printf ("Total bill amount: $%.2f\n", total);
  
 
return 0;

}


