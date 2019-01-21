//# c-program
//Write a program to print no. of vowels and consonants of a given input string.
#include<stdio.h>
#include<string.h>
int main()
{
    char a[50];
    int i,v=0,c=0;
    printf("enter string \n");
    gets(a);
    for(i=0;i<strlen(a);i++)
    {
        if(a[i]=='a'||a[i]=='i'||a[i]=='e'||a[i]=='0'||a[i]=='u')
        {
            v++;
        }
        else
        {
            c++;
        }
    }
    printf("no of vowels are  %d",v);
    printf("no of consonent %d",c);
    return(0);
}
