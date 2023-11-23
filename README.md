import java.util.Scanner;

public class Solution {


public static void add(int a,int b){ 
    
System.out.print(" sum  =   ");

    int c = a+b;
System.out.print(c);}

public static void mul(int a,int b){

    
    int c = a*b;
    System.out.print("mul =  ");
System.out.print(c);}

public static void div(int a,int b){
 
    System.out.print("div = ");
    int c = a/b;
System.out.print(c);}

public static void neg(int a,int b){
    System.out.print("neg = ");
    int c = a-b;
System.out.print(c);}



public static void main(String [] args){
    Scanner sc = new Scanner(System.in);
    System.out.print("enter the first num ");
    int a = sc.nextInt();
        System.out.print("enter the second num ");

      int b = sc.nextInt();
          System.out.print("enter the symbol  ");

      char q = sc.next().charAt(0);
             
      if(q=='+')   {   add(a,b);}
            if(q=='*') mul(a,b);
            if(q=='-') neg(a,b);
            if(q=='/')    div(a,b);
    
        }}
