#include <stdio.h>
#include <string.h>
#include <stdlib.h>

#define MAXLEN 20
 int n;
    int a;
    int k;
    int i;
    double r;
    int disposizione_menu;
    int combinazione_menu;
    int permutazione_menu;
    int disposizione_ripetuta;
    int combinazione_semplice;
    int combinazione_ripetuta;
    int permutazione_semplice;
    int permutazione_ripetuta;
int mostraMenu(void);

 main() {
    int scelta;

    do {
        system("clear");
        printf("\n\n");
        printf ("\t\t************************************************\n");
        printf ("\t\t*               ERIKA CELLA SARTOR             *\n");
        printf ("\t\t*                 CLASSE: 3°AC                 *\n");
        printf ("\t\t*               A.S. 2022 - 2023               *\n");
        printf ("\t\t************************************************\n");
        printf("\t\t************************************************\n");
        printf("\t\t*  RISOLUZIONE ESERICIZI CALCOLO COMBINATORIO  *\n");
        printf("\t\t************************************************\n");
        printf("\t\t*\tMenu' utente principale                     *\n");
        printf("\t\t************************************************\n");
        printf("\t\t*   premere 1 per DISPOSIZIONI                  *\n");
        printf("\t\t*   premere 2 per COMBINAZIONI                  *\n");
        printf("\t\t*   premere 3 per PERMUTAZIONI                  *\n");
        printf("\t\t*   premere 4 per USCITA                        *\n");
        printf("\t\t************************************************\n\n\n");

        printf("\t\tInserire scelta (1, 2, 3 oppure 4)   :    ");
        scanf("%d", &scelta);

        if ((scelta < 1) || (scelta > 4)) {
            printf("\n\nERRORE Digitare la scelta corretta.....\n\n");
            scanf("%*c"); // clear input buffer
            system("PAUSE");
        }
    } while ((scelta < 1) || (scelta > 4));

    // do something with scelta...

    return 0;
}
int menuDisposizioni(void);
int main()
{
int scelta;

do
   {
   system("clear");
   printf ("\n\n");
   printf ("\t\t************************************************\n");
   printf ("\t\t*  Benvenuti nel menu scelta delle disposizioni*\n");
   printf ("\t\t************************************************\n");
   printf ("\t\t************************************************\n");
   printf ("\t\t*    premere 1 per DISPOSIZIONI SEMPLICI                   *\n");
   printf ("\t\t*    premere 2 per DISPOSIZIONI RIPETUTE                   *\n");
   printf ("\t\t*    premere 3 per USCITA                         *\n");
   printf ("\t\t************************************************\n\n\n");

   printf("\t\tInserire scelta (1, 2, 3 oppure 4)   :    ");
        scanf("%d", &scelta);

   if ((scelta < 1) || (scelta > 3))
      {
      printf("\n\nERRORE Digitare la scelta corretta.....\n\n");
            scanf("%*c"); // clear input buffer
            system("PAUSE");
      }
   else;
   } while ((scelta < 1) || (scelta > 3));
return 0;
}
int disposizione_semplice (void);
int D;
int disposizione();
system("clear");
   printf ("\t\t***************************************************************************\n");
   printf ("\t\t* DISPOSIZIONI SEMPLICI                                                   *\n");
   printf ("\t\t***************************************************************************\n");
   printf ("\t\t* Definizione:                                                            *\n");
   printf ("\t\t* Una disposizione semplice è una sequenza ordinata di k elementi distinti*\n"); 
   printf ("\t\t* sono tutti i gruppi di k elementi scelti fra gli n, che differiscono per*\n");
   printf ("\t\t* almeno un elemento o per l'ordine con cui gli elementi sono collocati   *\n");
   printf ("\t\t***************************************************************************\n\n\n");
   printf ("\t\t* Formla:                                                                 *\n");
   printf ("\t\t* Dn,k=n!/(n-k)!   oppure Dn,k=n*(n-1)*(n-2)*...*(n-k+1)                  *\n"); 
   printf ("\t\t***************************************************************************\n\n\n")
   printf ("\t\t***************************************************************************\n");
   printf("\t\tInserire scelta è stat disposizione semplice    ");
        scanf("%d", &disposizione_semplice);
   
   
                    if (k>=n)
                    {
                int a=1
                for (int i=1;
                i>k-n;
                i-)
                {
                a=a*i;
                }
                return a;
                }
                       
    system("PAUSE");
    return 0; 
    }
    
    int disposizione_ripetuta (void);

system("clear");
   printf ("\n\n");
   printf ("\t\t***************************************************************************\n");
   printf ("\t\t* DISPOSIZIONI RIPETUTE                                                   *\n");
   printf ("\t\t***************************************************************************\n");
   printf ("\t\t* Definizione:                                                            *\n");
   printf ("\t\t* Una disposizione ripetuta è un raggruppamento ordinato di k elementi    *\n"); 
   printf ("\t\t* formato a partire da n elementi distinti, nel quale uno stesso elemento *\n");
   printf ("\t\t* può essere ripetuto fino a k volte                                      *\n");
   printf ("\t\t***************************************************************************\n\n\n");
   printf ("\t\t* Formula:                                                                *\n");
   printf ("\t\t* D’n,k = n k                                                             *\n");
   printf ("\t\t***************************************************************************\n\n\n");
   printf("\t\tInserire scelta è stat disposizione ripetuta    ");
        scanf("%d", &disposizione_ripetuta);
         {
        r=pow(n,k);  
        }
        return r;
        }
     system("PAUSE");
    return 0; 
        


int permutazione_semplice (void);
int P
system("clear");
   printf ("\n\n");
   printf ("\t\t***************************************************************************\n");
   printf ("\t\t* PERMUTAZIONE SEMPLICE                                                   *\n");
   printf ("\t\t***************************************************************************\n");
   printf ("\t\t* Definizione:                                                            *\n");
   printf ("\t\t* Una permutazione semplice è un raggruppamento ordinato di k elementi    *\n");
   printf ("\t\t* distinti con cui gli elementi si susseguono sia irrilevante             *\n");
   printf ("\t\t***************************************************************************\n\n\n");
   printf ("\t\t* Formula:                                                                *\n");
   printf ("\t\t* P n = n*(n−1)*(n−2)⋅ ⋯ ⋅ 2 ⋅ 1 = n !                                     *\n");
   printf ("\t\t***************************************************************************\n");
   printf("\t\tInserire scelta è stat disposizione semplice    ");
        scanf("%d", &disposizione_semplice);
        {
	if(a>=0)
{
while (a>=0)
	{
	 fattoriale *=a;
	 a--;	}
printf (“ fattoriale ha un valore di: %d\n”, fattoriale);
}
	else
	    {
	        printf("non posso calcolare il fattoriale di un un numero negativo\n");
		}
		system ("pause");
}
return 0;
