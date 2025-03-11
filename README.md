# c-6
Square pattern
#include <stdio.h>
int main()
{
    int i,j,n;
    printf("enter the size of the matrix;");
    scanf("%d",&n);
for(i=1;i<=n;i++){
    for(j=1;j<=n;j++){
        printf("* ");
    }
    printf("\n");
}
return 0;
}
