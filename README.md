# find-armstrong-no.-or-not.c
no. input from the user and then finding no. is armstrong or not.

//C program to find if a given no. is armstrong or not using for loop in c language

#include <stdio.h>

int main() {
    // Write C code here
    int n,r,s=0,p;
    printf("enter no.=");
    for(scanf("%d",&n),p=n;n!=0;r=n%10,s=s+r*r*r,n=n/10);
    {
        if(p==s)
        printf("armstrong no.");
        else
        printf("not an armstrong no.");
    }
    return 0;
}
