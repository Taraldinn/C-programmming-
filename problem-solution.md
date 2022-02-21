# Welcome To C programming Solution

```bash
Print All even Numbers from 1- 100
```

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

```bash
print all even numbers from 1 - 100 
```

**here is the solution **

```c
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&j);
    
    for(n = i ; n <= j  ; n++ ){
        
        if(n%2 == 0){
        
            printf("%d \n",n);
            
        }   
    }
    
    return 0;
}

```

**Here is The 2nd Solution**

```c
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&j);
    // i = i ;
    while(i <=j  ){
        
        if (i %2==0)
        {
            printf("%d\n", i);
        }
        i++;
    }

    
    return 0;
}
```



```bash
Print All Odd Number 1 - 100 
```

**1st Solution Is here**

```c
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&j);
    
    for(n = i ; n <= j  ; n++ ){
        
        if(n%2 == 1){
        
            printf("%d \n",n);
            
        }   
    }
    
    return 0;
}
```

**2nd Solution Is Here**

```c
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&j);
    // i = i ;
    while(i <=j  ){
        
        if (i %2==1)
        {
            printf("%d\n", i);
        }
        i++;
    }

    
    return 0;
}
```

```
Print sum of all numbers be
```
**Here Is The 1st Solution**
```c
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("give You number 1st number: ");
    scanf("%d",&i);
    printf("give You number 2nd number: ");
    scanf("%d",&j);
    // i = i ;
    n = 0;
    while(i <=j  ){
        
        n = n + i;
        ++i;
        // or
        // i++
    
    
    }
    printf("%d",n);

    
    return 0;
}
```

**Here Is The 2nd Solution**

```
```

```c
calculate of Avarage of 5 numbers and print 
```

```c
#include <stdio.h>

int main() {

        int sum=0,i,n;
        float average;
        
        printf("enter your 5 number at serial\n");
        
        for(i=1;i<=5;i++){
        
                scanf("%d",&n);
                sum=sum+n;
                }
        
        average = sum/5;
        printf("%f",average);

return 0;

}
```







```c
print n number of line , each line will contain i number of '*' where  i >= 1 && i <= n 
```

```c
#include <stdio.h>

int main() {
    int i , j , n; 
    printf(" Enter Nunmers of Line ");
    scanf("%d",&n);
    for(i = 1 ;i >= 1 && i <= n; ++i){
        for (j = 1 ; j <= i ; j++){
            printf(" *");
        }
        printf("\n");
    }
    
    return 0;
}

```

