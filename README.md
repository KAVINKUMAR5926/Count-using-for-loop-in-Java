# Count-using-for-loop-in-Java
import java.util.Scanner;
public class Main
{
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int count=0;
        for(; n>0; n/=10, count++);
        System.out.println(count);
        
    }
}
