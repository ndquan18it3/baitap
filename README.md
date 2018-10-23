# baitap
kiemtra
#include<stdio.h>
#include<conio.h>
int main (){
	int mang[10];
	int n;
	printf("nhap n");
	scanf("%d", &n);
	for (int i=0; i<n; i++){
	   printf("mang[%d]=", i);
	   scanf("%d", &mang[i]);
      }
      printf("\n");
    for (int i=0; i<n; i++){
       printf("mang[%d]=%d \n", i,mang[i]);
   }
   printf("\n");
   int tong = 0;
   for (int i=0; i<n; i++){
   	   if (mang[i]%2==0)
		   tong = tong + mang[i];
   }
   printf("tong mang la %d", tong);
   printf("\n");
   
   int min;
   min = mang[0];
   for (int i=0; i<n; i++){
        if (mang[i]<min)
           mang[i]=min;
   }
   printf("phan tu nho nhat la %d", min);
}
   
   
   
   
   
