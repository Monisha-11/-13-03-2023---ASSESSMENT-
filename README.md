# -13-03-2023---ASSESSMENT-
## MONDAY - PROGRAMS -[ PATTERNS ] 

## NAME :- Monisha T
## REGISTER NUMBER :- 212221240029

### 1) Program to print square pattern using star(*)

#### PROGRAM :-

```java

import java.util.Scanner;
public class Main {
   public static void main(String[] args)
   {
       Scanner sc=new Scanner(System.in);
       System.out.print("Enter the Number : ");
       int a=sc.nextInt();
       for(int i =1;i<=a;i++)
       {
           for(int j=1;j<=a;j++)
           {
               System.out.print("* ");
           }
           System.out.print("\n");
       }


   }
}

```
#### OUTPUT :-

<img width="278" alt="SQUARE" src="https://user-images.githubusercontent.com/93427240/224884703-dae7074b-6a3c-4e70-917f-fe08dab8ded4.png">

### 2) Program to print inverted pyramid pattern using star(*) 

#### PROGRAM :-

```java 

import java.util.Scanner;
public class BOTTOM_DIAMOND {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the Number : ");
        int a=sc.nextInt();
        for(int i=0;i<=a;i++)
        {
            for(int j=0;j<=i;j++)
            {
                System.out.print(" ");
            }
            for(int k=0;k<=a-1-i;k++)
            {
                System.out.print("*" + " ");
            }
            System.out.print("\n");
        }


    }

}

```

#### OUTPUT :-

<img width="284" alt="BOTTOM" src="https://user-images.githubusercontent.com/93427240/224885255-8f3f5f90-3cd2-4b70-8cef-2b0ddec5065f.png">

### 3) Program to print right half diamond pattern using star(*) 

#### PROGRAM :-

```java

import java.util.Scanner;
public class SIDE_DIAMOND{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the Number : ");
        int a=sc.nextInt();
        for(int i=0;i<=a-1;i++)
        {
            for(int j=0;j<=i;j++)
            {
                System.out.print("*" + " ");
            }
            System.out.print("\n");
        }
        for(int i=a-1;i>=0;i--)
        {
            for(int j=0;j<=i-1;j++)
            {
                System.out.print("*" + " ");
            }
            System.out.print("\n");
        }

    }
}

```

#### OUTPUT:-

<img width="289" alt="SIDE" src="https://user-images.githubusercontent.com/93427240/224885428-2f7ace09-6f0e-4c5d-88ee-b5d9e7397a6c.png">



