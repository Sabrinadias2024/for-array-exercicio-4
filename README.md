#include <stdlib.h>


int main(){

int i, cont=0;

char vet[11];


for (i=0;i<11;i++){

scanf("%c",vet[i]);

}

for(i=0;i<11;i++){

if( vet[i] != 'a' || vet[i] != 'e' || vet[i] != 'i' || vet[i] != 'o' || vet[i] != 'u')

cont ++;

}    

printf ("qtde consoantes: %d\n", cont);


printf ("as consoantes foram:");

for(i=0;i<11;i++){

if( vet[i] != 'a' || vet[i] != 'e' || vet[i] != 'i' || vet[i] != 'o' || vet[i] != 'u'){

printf ("%c ", vet[i]);

}

}

return 0;

}
