## javastack
## ASSIGNMENT 1
## QN 1.PRINT SUM,MULTIPLE,DIVIDE,SUB,REMAINDER OF TWO NUMBER
  ```
  import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        int a,b,add,sub,div,mul,rem;
        Scanner in = new Scanner(System.in);
        a = in.nextInt();
        b = in.nextInt();
        add=a+b;
        sub=a-b;
        mul=a*b;
        div=a/b;
        rem=a%b;
        System.out.println("Addition = "+add);
        System.out.println("Subtraction = "+sub);
        System.out.println("Multiply = "+mul);
        System.out.println("Divide = "+div);
        System.out.println("Remainder = "+rem);
    }
}
```
OUTPUT:
![QN 1](https://user-images.githubusercontent.com/123354092/224596507-9e0b1047-ffaa-4f17-96f3-fec47293cc26.PNG)

### QN 2.COMPARE TWO NUMBERS
  ```
  import java.util.Scanner;
public class Main 
{
    public static void main(String[] args)
    {
        int a,b;
        Scanner in = new Scanner(System.in);
        a = in.nextInt();
        b = in.nextInt();
        if(a==b)
        {
            System.out.println("Two Numbers are Equal");
        }
        if(a!=b)
        {
            System.out.println("Two Numbers are Not Equal");
        }
        if(a>b)
        {
            System.out.println("A is Greater than B");
        }
        if(a<b)
        {
            System.out.println("A is Less than B");
        }
        

}
}
 ```
OUTPUT:
![QN 2](https://user-images.githubusercontent.com/123354092/224597040-f6f05392-7c83-45d4-a6bc-4bce08cbac7f.PNG)



