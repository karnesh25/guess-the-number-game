#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int number, guess, nguess=1;
    srand(time(0));
    number = rand()%50 +1;  //generate random no. between 1 to 50
    //printf("The number is %d\n", number);
   // keep running the loop until the no. is guessed 
   do{
       printf("Guess the number between 1 to 50\n");
       scanf("%d", &guess);
       if(guess>number){
           printf("Lower number please\n");
       }
       else if (guess<number){
           printf("Higher number please\n");
       }
       else {
           printf("You guessed it in %d attempts \n", nguess);
       }
       nguess ++;
         
   }while(guess!=number);
    return 0;
}
