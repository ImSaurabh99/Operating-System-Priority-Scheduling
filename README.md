#include<stdio.h>
#include<conio.h>
#include<string.h>
 main()
{
    int et[20],at[10],n,i,j,temp,st[10],ft[10],wt[10],ta[10];
    int totwt=0,totta=0;
    float awt,ata;
    char pn[10][10],t[10];
    
    printf("Enter the number of process: ");
    scanf("%d",&n);
    printf("\nEnter the details: ");
    for(i=0; i<n; i++)
    {
        printf("\nEnter the process id: ");
        scanf("%s",&pn[i]);
        printf("\nEnter the Arrival time: ");
        scanf("%d",&at[i]);
        printf("\nEnter the Burst time: ");
        scanf("%d",&et[i]);
        
    }
