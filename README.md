# MADLAB22_201b337
lab exercises

LAB EXERCISE 1

public class Main
{
	public static void main(String[] args) {
	    for(int i=5;i>0;i--)
     {
         for(int j=0;j<5-i;j++)
         {
             System.out.print(" ");
         }
         for(int k=0;k<i;k++)
         {
             System.out.print("*"+" ");
         }
         System.out.println("\n");
     } 
 }
		
	}
--------------------------------------------

LAB EXERCISE 2

public class Main
{
	public static void main(String[] args) {
	    for(int i=1;i<=5;i++)
     {
         for(int j=i;j<=5;j++)
         {
             System.out.print(" ");
         }
         for(int j=1;j<=i;j++)
         {
             System.out.print("* ");
         }
         System.out.println("");
     } 
 }
		
	}

------------------------------------------------

LAB EXERCISE 3

public class Main{
    public static void main(String[] args)
    {
        Mother m=new Mother();
        m.show();
       Child c=new Child();
       c.show();
       Mother m1=new Child();
       m1.show();
    }
}
public class Mother {
    public static void show()
    {
        System.out.println("This is Mother Class");
    }
}
public class Child extends Mother{
   public static void show()
    {
       System.out.println("This is Child");
        
    }
}

------------------------------------------------------

LAB EXERCISE 4

public class Main
{
	public static void main(String[] args) {
	    for(int i=1;i<=5;i++)
     {
         for(int j=i;j<=5;j++)
         {
             System.out.print(" ");
         }
         for(int j=1;j<=i;j++)
         {
             System.out.print("* ");
         }
         System.out.println("");
     } 
 }
		
	}

-------------------------------------------------------------

LAB EXERCISE 5

public class Main{
    public static void main(String[] args)
    {
        Mother m=new Mother();
        m.show();
       Child c=new Child();
       c.show();
       Mother m1=new Child();
       m1.show();
    }
}
public class Mother {
    public static void show()
    {
        System.out.println("This is Mother Class");
    }
}
public class Child extends Mother{
   public static void show()
    {
       System.out.println("This is Child");
        
    }
}


