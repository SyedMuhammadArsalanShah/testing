/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package ascii_table;

import java.util.Scanner;

/**
 *
 * @author S M Arsalan Shah
 */
public class Ascii_table {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        ////with out Ascii table
         Scanner scan = new Scanner(System.in);
         System.out.println("enter character for method 1");     
         char ch1 =scan.next().charAt(0);
         scan.nextLine();
         if((ch1 >='a'&& ch1 <='z')||(ch1 >='A'&& ch1 <='Z')){ 
         System.out.println("Alpahbet");}
         else  if(ch1 >='0'&& ch1 <='9')
         {System.out.println("Digit");}
         else{System.out.println("symbol");}

        // // method 2 with ascii table but ascii not working because this
        // // is simple addition 
        System.out.println("enter character for method 2");
        int int2 =10;
        int chh1 =scan.nextInt();
        int chh2 = int2+chh1;
        if((chh2 >=65 && chh2 <=90)||(chh2 >=97&& chh2 <=122)){ 
        System.out.println("Alpahbet");}
        else  if(chh2 >=48 && chh2 <=57)
        {System.out.println("Digit");}
        else{System.out.println("symbol");}
        System.out.println("enter your character and check with"+ int2 + " + :"+chh2);
        
        // // method 3 with ascii table sum of decimal value and given decimal value
        System.out.println("enter character for method 3");
        int int3 =10;
        char chhh1 =scan.next().charAt(0);
        int chhh2 =int3+chhh1;//
        if((chhh2 >=65 && chhh2 <=90)||(chhh2 >=97&& chhh2 <=122)){ 
        System.out.println("Alpahbet");}
        else  if(chhh2 >=48 && chhh2 <=57)
        {System.out.println("Digit");}
        else{System.out.println("symbol");}
        System.out.println("enter your character and check with"+int3 + " + :"+chhh2);
         // // method 4 with ascii table sum of decimal value & given character
        System.out.println("enter character for method 4");
        int int4 =10;
        char chhhh1 =scan.next().charAt(0);
        char chhhh2 =(char) (int4+chhhh1);//
        if((chhhh2 >=65 && chhhh2 <=90)||(chhhh2 >=97&& chhhh2 <=122)){ 
        System.out.println("Alpahbet");}
        else  if(chhhh2 >=48 && chhhh2 <=57)
        {System.out.println("Digit");}
        else{System.out.println("symbol");}
        System.out.println("enter your character and check with"+int4 + " + :"+chhhh2);

        } 
        
    }
    

