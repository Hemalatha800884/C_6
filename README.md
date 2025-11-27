# C_6
Swaping 5 number
#include <stdio.h>
#include <stdlib.h>
int main(void){
FILE *fp = fopen("hema.txt", "w");
if (!fp) {perror("fopen"); return 1;}
printf(fp,"Johnny Johnny Yes papa!!!!");
fclose(fp);
printf("the poem is transferred to hema.txt");
return 0;
}
    
