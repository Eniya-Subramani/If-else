# If-else
import java.util.Scanner;
Public class IFELSE {
Public static void main(String[]args){
Scanner sc = new Scanner(System.in);
System.out.println(&quot;Enter a number:&quot;);
int n = sc.nextInt();
if (n&gt;0)
{
System.out.println(&quot;The number is Positive&quot;);
}
else if(n&lt;0)
{
System.out.println(&quot;The number is Negative&quot;);

}
else
{
System.out.println(&quot;The number is zero&quot;);
}
}
}
OUTPUT:
Enter a number:
0
The number is zero
Enter a number:
6
The number is Positive
Enter a number:
-9
The number is Negative
