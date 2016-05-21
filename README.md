public static void main()
{
int i,j;
for (i=1;i<=100;i++)
{
for (j=1;j<=i;j++)
{
c=0
if(i%j==0)
c++;
}
if(c==2)
system.out.print("prime numbers are {0}", i);
}
