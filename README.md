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

### QN 3.CONVERT A STRING TO AN INTEGER
   ```
   public class Main 
{
    public static void main(String[] args)
    {
        String a="50";
        int b=Integer.parseInt(a);
        System.out.println("Convert a string to an integer "+b);
}
}
   ```
   OUTPUT:
   ![QN3](https://user-images.githubusercontent.com/123354092/224598171-a41ff026-5383-489b-a793-1ec4b19179c9.PNG)
   
   ### QN 4FIND AREA OF RHOMBUS
   ```
      public class Main
{
    public static void main(String args[])
    {
        float a=10,b=20;
        float Area_of_rhombus;
        Area_of_rhombus=(a*b)/2;
        System.out.println("Area of Rhombus is "+Area_of_rhombus);
    }
}

   ```
  OUTPUT:
  
  ![QN4](https://user-images.githubusercontent.com/123354092/224598804-284e0534-9625-4701-bcb1-30697240cf34.PNG)
  
  ### QN 5FIND THE NUMBER OF DAYS IN A MONTH
  ```
  import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {

        Scanner input = new Scanner(System.in);

        int Days=0;
        String Name = " ";

        System.out.print("Enter the month number: ");
        int month = input.nextInt();

        System.out.print("Enter the year: ");
        int year = input.nextInt();

        switch (month) {
            case 1:
                Name = "January";
                Days = 31;
                break;
            case 2:
                Name = "February";
                if ((year % 400 == 0)||((year % 4 == 0)&&(year % 100 != 0))) {
                    Days= 29;
                } else {
                    Days = 28;
                }
                break;
            case 3:
                Name = "March";
                Days = 31;
                break;
            case 4:
                Name = "April";
                Days = 30;
                break;
            case 5:
                Name = "May";
                Days = 31;
                break;
            case 6:
                Name = "June";
                Days = 30;
                break;
            case 7:
                Name = "July";
                Days = 31;
                break;
            case 8:
                Name = "August";
                Days = 31;
                break;
            case 9:
                Name = "September";
                Days = 30;
                break;
            case 10:
                Name = "October";
                Days = 31;
                break;
            case 11:
                Name = "November";
                Days = 30;
                break;
            case 12:
                Name = "December";
                Days = 31;
        }
        System.out.println(Name + " " + year + " has " + Days + " days");
    }
}
```
OUTPUT:
![image](https://user-images.githubusercontent.com/123354092/224599498-7004e9cf-daaf-45c4-b6ca-bf91ea1a8900.png)

 ### QN 6 PRINT THE EVEN NUMBERS 1 TO 20
 ```
 import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
            Scanner input = new Scanner(System.in);
            int a = input.nextInt();
            for (int i=1; i<=a; i++)
            {
                if (i%2==0)
                {
                    System.out.print(i+" ");
                }
            }
        }
    }
 ```
 OUPUT:
 ![image](https://user-images.githubusercontent.com/123354092/224600039-f8936a20-8813-4150-9c69-7087ab684ba2.png)



      




