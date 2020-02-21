# ReverseStringProgram

import java.util.Scanner;

 public class  Square{
    public static void main (String Args[]) {
        
        Scanner key=new Scanner(System.in);
        
        
        System.out.print("Enter word --> ");
        String word=key.nextLine();
        
        
        System.out.println();
        
        String wordMe=" ";
        
        
        
        System.out.println(word);
        
        
        
        
        for(int i = 0; i < word.length(); i++){
         
            System.out.println(word.substring(i, i+1) + " ");
            
        }
        
        for(int i = word.length()-1; i>=0; i--){
            String hey=lastIndexOf();
            System.out.println(word.substring(i,i+1) + " "); 
            
        }
        
        
        System.out.println(word);
    }
}
        



