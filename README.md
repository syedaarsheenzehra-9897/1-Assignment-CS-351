 1-Assignment-CS-351

Q#1:-
import java.util.Scanner;
public class PercentageMarks {
    public static void main(String[] args) 
{
        Scanner  sc newScanner(System.in);
        System.out.print("Enter obtained marks: ");
        double obtained = sc.nextDouble();
        System.out.print("Enter maximum marks: ");
        double max = sc.nextDouble();
        double percentage = (obtained / max) * 100;
        System.out.printf("Percentage);
    }
}
Q#2:-
import java.util.Scanner;
public class Circle
 {
    public static void main(String[] args)
 {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter radius: ");
        double r = sc.nextDouble();
        double area = Math.PI * r * r;
        double circumference = 2 * Math.PI * r;
        System.out.printf(area, circumference);
    }
}


Q#3:-
import java.util.Scanner;
public class DiscountedPrice
 {
    public static void main(String[] args) 
{
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter original selling price: ");
        double original = sc.nextDouble();
        System.out.print("Enter discount percentage: ");
        double discount = sc.nextDouble();
        double discountedPrice = original - (original * discount / 100);
        System.out.printf(discounted price);
    }
}


Q#4:-
import java.util.Scanner;
public class OriginalPrice 
{
    public static void main(String[] args)
 {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter discounted selling price: ");
        double discounted = sc.nextDouble();
        System.out.print("Enter discount percentage: ");
        double discount = sc.nextDouble();
        double original = discounted / (1 - discount / 100);
        System.out.println(original);
    }
}


Q#5:-
import java.util.Scanner;
public class PowerConsumption {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter voltage (V): ");
        double volt = sc.nextDouble();
        System.out.print("Enter current (A): ");
        double amp = sc.nextDouble();
        double watts = volt * amp;
        System.out.printf("Power consumption: %.2f Watts\n", watts);



Q#6:-
import java.util.Scanner;
public class TrapezoidArea {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter length of side a: ");
        double a = sc.nextDouble();
        System.out.print("Enter length of side b: ");
        double b = sc.nextDouble();
        System.out.print("Enter height h: ");
        double h = sc.nextDouble();
        double area = h * (a + b) / 2;
        System.out.printf("Area of trapezoid: %.2f\n", area);
    }
}


Q#7:-
import java.util.Scanner;
public class EvenOdd;
 {
    public static void main(String[] args) 
{
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter an integer: ");
        int num = sc.nextInt();
        if (num % 2 == 0) {
            System.out.println("EVEN");
        } 
else 
{
            System.out.println("ODD");
        }
    }
}




Q#8:-
public class HeronsFormula
 {
    public static double calculateArea(double a, double b, double c)
 {
        // Calculate semi-perimeter
        double s = (a + b + c) / 2;
        
        // Calculate area using Heron's formula
        double area = Math.sqrt(s * (s - a) * (s - b) * (s - c));
        return area;
    }

    public static void main(String[] args)
 {
        double a = 3, b = 4, c = 5; 
// Example side lengths
        double area = calculateArea(a, b, c);
        System.out.println("The area of the triangle is: " + area);
    }
}