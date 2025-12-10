//Chirag Bharath
/* Write a program to check if a customer wants to buy a car or a bike from u and check the price they have to pay depending on their credit score :
 * 500-600:18%,600-620:16%,620-660:12%,660-690:9%,690+ : 6%
 */
import java.util.*;
public class Nloops
{
    public static void main()
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter what your looking for : \n a)car or b) bike ");
        char ch=sc.next().charAt(0);
        switch (ch){
            case a:
            System.out.println("Enter the price of your car");
            int price=sc.nextInt();
            System.out.println("Enter your credit score");
            int Cscore=sc.nextInt();
            int Irate;
            if(500<=Cscore<600)
            Irate=18;
            else if(600<=Cscore<620)
            Irate=16;
            else if (620<=Cscore<660)
            Irate=12;
            else if (660<=Cscore<690)
            Irate=9;
            else if (Cscore>=690)
            Irate=6;
            else
            Irate=20;
            double Monthly=price*Irate/100;
            System.out.println("Your monthly payment for this car will be : \n" +Monthly);
            break;
            
            case b:
            System.out.println("Enter the price of your bike");
            int price=sc.nextInt();
            System.out.println("Enter your credit score");
            int Cscore=sc.nextInt();
            int Irate;
            if(500<=Cscore<600)
            Irate=18;
            else if(600<=Cscore<620)
            Irate=16;
            else if (620<=Cscore<660)
            Irate=12;
            else if (660<=Cscore<690)
            Irate=9;
            else if (Cscore>=690)
            Irate=6;
            else
            Irate=20;
            double Monthly=price*Irate/100;
            System.out.println("Your monthly payment for this bike will be : \n" +Monthly);
        }
    }
}
