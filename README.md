# Repo-43
Check +ve number and -ve number
//Check number is positive or negative
import java.util.Scanner;
class Check{
    public static void main(String[] args) {
    int n;
    System.out.println("Enter any number");
    Scanner r = new Scanner(System.in);
    n = r.nextInt();
    
    if (n>0)
    {
       System.out.println("+ve number");
    }
    else if(n<0)
    {
       System.out.println("-ve number");
    }
    else
    {
       System.out.println("Niether +ve nor -ve number"); 
    }
}
}
