#include <stdio.h>
#include<string.h>
int main()
{
    char str[100],t;
    int i,j,n;
    scanf("%[^\n]s",str);
    n=strlen(str);
    for(i=0;i<n;i++)
    {
        if(str[i]=='a' || str[i]=='e' || str[i]=='i' || str[i]=='o' || str[i]=='u')
        {
           for(j=i+1; j<n; j++)
            {
                 if(str[j]=='a' || str[j]=='e' || str[j]=='i' || str[j]=='o' || str[j]=='u')
                 {
                     if(str[i]>str[j])
                     {
                         t=str[i];
                         str[i]=str[j];
                         str[j]=t;
                     }
                 }
                
            } 
            
        }
        
    }
    printf("%s",str);
    return 0;
}
