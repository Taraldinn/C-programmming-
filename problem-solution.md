# Welcome To C programming Solution

    Print All even Numbers from 1- 100

 **Here Is The Solution**  
```c
int main()
{
    int i,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&n);
    
    while(i <= n){
        printf("%d \n",i);
        i++ ; 
        
    }
    
    return 0;
}
```

**2nd Solution** 
```c
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&j);
    
    for(n = i ; n <= j; n++ ){
        
        printf("%d \n",n);
        
    }
        
    
    
    return 0;
}


```
