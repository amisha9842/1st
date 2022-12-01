In case of an array, a and &a are the same thing but when it comes to pointers, q and &q are different.&q prints the base address where pointer q is stored while q prints the value of pointer.

one int takes 4 bytes.32 bits

dereferencing operator-> '*'(used when we have to find value at that particular address.

int a[5],i;
int *q=a;
for (i=0;i<5;i++)
{
scanf("%d',&a[i]);
}
for(i=0;i<5;i++)
{
printf("%d",*(q+i))
}




