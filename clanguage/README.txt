--------------------------------------------------------------------------------------------
PARA COMPILAR EN LINUX USAMOS GCC:

1. Ejemplo: 

Si queremos compilar el programa holamundo.c (para poder ejecutarlo) hacemos lo siguiente:
gcc -o holamundo holamundo.c

holamundo es el nombre del ejecutable que creara gcc
holamundo.c es el programa a compilar

Una vez hecho esto, lo podemos ejecutar: 
./holamundo

--------------------------------------------------------------------------------------------
1: Verdadero
0: Falso
--------------------------------------------------------------------------------------------


NUMEROS ENTEROS:					        TAMAÑO EN bytes
char ----> Generalmente para guardar un caracter 			1
short ---> Numeros cortos						
int ---> Numero entero							2
long ---> Numeors muuuuy largos						
NUMEROS REALES(enteros o con coma): 3.1452 9.876 (se utiliza . y no ,)
float ---> Menos precision que double					4
double ---> Mas precision						8
void ---> Sin valor							0

--------------------------------------------------------------------------------------------

int  ---> %d
float ---> %f o %g para eliminar los ceros sobrantes
char ---> %c
