#include <stdio.h>
#include <stdlib.h>

int main() {
int satir, sutun;
    printf("Enter M value: %c",satir );

    scanf("%d",&satir );

    printf("Enter N value: %c",sutun );

    scanf("%d",&sutun );  

    int matris[satir][sutun];

    for(int i=0; i<satir;i++){

        for (int j=0; j<sutun;j++) {   
      
         matris[i][j] = rand()%100;   
        } 
}
FILE *fp=fopen("numbers.txt","w");
     for(int i=0; i<satir;i++) { 
 
        for (int j=0; j<sutun;j++) {

fprintf(fp, "%d\t", matris[i][j]);
 }
       fprintf(fp,"\n");
}
fclose(fp);
  return 0;
}
