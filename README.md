#include<stdio.h>

int main()
{
int num_start ,sum, num_end , count;
count = 0;sum = 0;
printf("enter starting range ");
scanf("%d" , &num_start);
printf("\n enter closing range");
scanf("%d",&num_end);
for(int i = num_start;i<=num_end;i++)
{
if(i%2==0)
{
printf("\n %d",i);
count = count+1;
sum = sum+i;
}


}
printf("\n\nthere are %d even numbers", count);
printf ("\nsum of even no is %d ", sum);

}
