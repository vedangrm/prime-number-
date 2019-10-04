# prime-number
#include<stdio.h>
int main ()
{
    int i,m,n,j,p=0;
    printf("enter the two limits\n");
    scanf("%d%d",&m,&n);
    for(i=m;i<=n;i++)
    {
        p = 1;
        for(j=2;j<i;j++)
        {
            if(i%j==0)
            {
                p=0;
            }

        }
        if(p==1)
        {
            printf("%d",i);
        }

    }
    return 0;

}
