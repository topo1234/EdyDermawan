# EdyDermawan

#include<stdlib.h>
#include<stdio.h>

int main(){
    int a,b,c;

    printf("masukkan nilai a: ",a);
    scanf("%d",&a);
    printf("masukkan nilai b: ",b);
    scanf("%d",&b);
    printf("masukkan nilai c: ",c);
    scanf("%d",&c);
    printf("\n");

    if(a>b){
        if (a>c){
            printf("A adalah yang terbesar",a);
        }else{

                printf("c adalah yang terbesar",c);
            }

        }else{
            if(b>c){
                printf("B adalah yang terbesar",b);
            }else{
            printf("C adalah yang terbesar",c);
            }

        }

        printf("\n");
        system("pause");
        return 0;
    }


#include<stdio.h>

int main(){
    int angka1,angka2;
    printf("Demo Struktur Kondisi\n");
    printf("=====================\n");
    printf("Masukkan bilangan asli 1: ");
    scanf("%d", &angka1);

    printf("Masukkan bilangan asli 2: ");
    scanf("%d", &angka2);
    int pilihan;
    printf("\n\n Jenis operator\n");
    printf("--------------------\n");
    printf(" 1. Contoh Operator Aritmatika\n");
    printf(" 2. Contoh Operator Relasional\n");
    printf(" 3. Contoh Operator Logical \n");
    printf(" Pilihan [1-3]: ");
    scanf("%d", &pilihan);
    if (pilihan == 1)
    {
        printf("\n Contoh Operator Aritmatika\n");
        printf(" Penjumlahan \t: %d + %d = %d \n", angka1,angka2, angka1 + angka2);
        printf(" Perkalian \t: %d * %d = %d \n",angka1,angka2,angka1 * angka2);
    }
    else if (pilihan == 2)
    {
        printf("\n Contoh Operator Relasional\n");
        printf(" Persamaan \t: %d == %d = ",angka1, angka2);
        if (angka1 == angka2)
            printf("TRUE");
        else
            printf("FALSE");

        printf("\n Pertidaksamaan\t: %d != %d = ",angka1,angka2);
        if (angka1 != angka2)
            printf("TRUE");
        else
            printf("FALSE");
    }
    else if (pilihan == 3)
    {
        printf("\n\n Contoh Operator Logical\n");
        printf(" Logika AND \t: %d && %d = %d\n",angka1,angka2, angka1 && angka2);
        printf(" Logika OR \t: %d || %d = %d\n",angka1,angka2,angka1 || angka2);
    }
    else
        printf("\n Harap Masukkan Bilangan Asli ");



    getch();
    return 0;
}










