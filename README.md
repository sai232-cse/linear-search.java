# linear-search.java

import java.util.Scanner;

public class Main{

    public static void main(String args[]){
    
        Scanner snr=new Scanner(System.in);
    
        int n=snr.nextInt();
        
        int a[]=new int[n],searchvalue,i;
        
        for(i=0;i<n;i++){
        
            a[i]=snr.nextInt();
        
        }
        
        searchvalue=snr.nextInt();
        
        for(i=0;i<n;i++){
        
            if(a[i]==searchvalue){
            
                System.out.println(i);
                
                break;
            
            }
        
        }
        if(i==n){
            System.out.println("element does not exist");
        }
    }
}
