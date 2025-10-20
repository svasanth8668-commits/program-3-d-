# program-3-d-
C module 3

EX NO:3-d) Search element in an array.



Date:19/10/2025 


Name: VASANTH S 


Ref no: 25017538

AIM:
To write a C program to get an array and a element as input and search the element in that array.

ALOGORITHM:
1) Get an array as input from the user.
2) get an element to search.
3) Search the element in that array using for loop.
4) Print the index position of the element.

PROGRAM:

```
#include<stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    int arr[num];
    for(int i=0;i<num;i++)
    {
        scanf("%d",&arr[i]);
    }
    
    
    for(int i=0;i<num;i++)
    {
        if(arr[i]==5)
        printf("5 is found at position %d",i+1);
    }
}
```

OUTPUT:

<img width="800" height="112" alt="Screenshot 2025-10-20 105522" src="https://github.com/user-attachments/assets/2c1e58f3-3b08-4213-b44c-c72469ab6b29" />

RESULT:
Thus the c program to get an array as input and search an element in that array is executed succesfully.











