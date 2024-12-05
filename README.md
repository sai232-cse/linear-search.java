# linear-search.java
import java.util.Scanner;

public class Main{

    public static void main(String args[]){
    
        Scanner snr=new Scanner(System.in);
    
        int n=snr.nextInt();
        
        int a[]=new int[n],sv,i;
        
        for(i=0;i<n;i++){
        
            a[i]=snr.nextInt();
        
        }
        
        sv=snr.nextInt();
        
        for(i=0;i<n;i++){
        
            if(a[i]==sv){
            
                System.out.println(i);
                
                break;
            
            }
        
        }
        if(i==n){
            System.out.println("not exist");
        }
    }
}
