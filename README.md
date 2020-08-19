#include<stdio.h>
int main()
{
	int m;
	/*m = Marks*/
	printf("Please enter the score");
	scanf("%d",&m);
	if(m<40)
	{
		printf("Grade F");
		
	}
	else if(m>=40 && m<=50)
	{
		printf("Grade E");
	}
		else if(m>50 && m<=60)
		{
			printf("Grade  d");
		}
			else if(m>60 && m<=70)
			
		{
			printf("Grade C");
			}
		   else	if(m>70 && m<=80)
		{
			printf("Grade  B");
			}
		
		else if(m>80 && m<=90)
		{
			printf("Grade  A");
		}
		else if(m>90 && m<=100)
			{
				printf("Grade A+");
			}
			
			
		

return 0;
}
