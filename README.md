- 👋 Hi, I’m @aaronvmeprathu
- 👀 I’m interested in web developement
- 🌱 I’m currently learning -react.js , Next.js 
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me instagram- https://www.instagram.com/aaronvmeprathu/

<!---
aaronvmeprathu/aaronvmeprathu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->



Import java.util.*;
Public class Goldboach
{
    Public static void main()
    {
        Scanner in =new Scanner(System.in);
        Int n,I,j,a,b,s=0;
        System.out.println(“Enter a number”);
        N=in.nextInt();
        If(n>9&&n<50)
        {
        If(n%2!=0)
        {
            System.out.println(“INVALID INPUT: NUMBER IS ODD”);
        }
        If(n%2==0)
        {
        For(a=1;a<=n;a++)
        {
            For(b=1;b<=n;b++)
            {
              Int c=0,c2=0;
                For(i=1;i<=a;i++)
                {
                    If(a%i==0)
                    {
                    C=c+1;
                }
            }
           
            For(j=1;j<=b;j++)
                {
                    
                    If(b%j==0)
                    {
                    
                    C2=c2+1;
                }
            }
                         
                If(c==2&&c2==2)
                {
                    
                    S=a+b;
                    If(s==n)
                    System.out.println(“prime pairs are “+a+”,”+b);
                }
            
            }
       
        }
    }
}
Else
{
    System.out.println(“INVALID INPUT: NUMBER OUT OF RANGE”);
}
System.out.println();
