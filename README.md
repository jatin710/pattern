# pattern
#include <stdio.h>

int main() {
    	int i, j, k , n;
	printf("Enter the number\n");
	scanf("%d",&n);
	for( i = 1; i<(2*n);i++)
	{
	    if(i<=n)
	    {
	        for(j = i; j < n; j++ )
	        {
	            printf(" ");
	        }
	        for( k = 0; k < i ; k++ )
	        {
	            printf("* ");
	        }printf("\n");
	    }
	    else
	    {
	        for( j = i; j>n; j--)
	        {
	            printf(" ");
	        }
	        for(k = i; k<(2*n); k++)
	        {
	            printf("* ");
	        }printf("\n");
	    }
	}
	return 0;
}
