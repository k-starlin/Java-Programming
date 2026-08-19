# Java-Programming
Java programs and practice problems while learning Java

*HelloWorld program*
#Code:

public class HelloWorld
  {
    public static void main(String[] args)
    {
      System.out.print("Hello,World!");
    }
  }
  
>>Output:
Hello World

*Addition program*
#Code:

public class Addition
{
  public static void main(String[] args)
  {
    int a = 10;
    int b = 20;
    System.out.println("sum " + (a + b));
  }
}

>>Output:
sum 30

*Square program*
#Code:

import java.util.Scanner;

public class Square {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();

        System.out.println(n * n);
    }
}

>>Output:
5
25


