# Class_6ThMarch
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
#include<stdio.h>

// Program to print Fibonacci Series
int Fibo(int);

int main(){
	int n;
	printf("Enter the Value of N : ");
	scanf("%d",&n);
	for (int i=0;i<n;i++){
		printf("%d ",Fibo(i));
	}
	return 0;
	
}

int Fibo(int n){
	if (n==0){
		return 0;
	}else if(n==1){
		return 1;
	}
	else{
		return Fibo(n-1)+Fibo(n-2);
	}
}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
// Program to print Sum of N natural Numbers
//int Sum(int);

int main(){
  int n;
  printf("Enter the Value: ");
	scanf("%d",&n);
	printf("The Value is:  %d",Sum(n));
	return 0;

}
//int Sum(int x){
//	if (x==0){
//		return 0;
//	}else{
//		return x+Sum(x-1);
//	}
//}
