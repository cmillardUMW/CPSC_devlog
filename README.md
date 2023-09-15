# CPSC_devlog
### A record of all the coding I do for my computer science class
In order of most recent

### Week 2 Pairing Practice
9/11/23
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter the 3 diameter values of the garden plots:");
        float diam1 = input.nextFloat();
        float diam2 = input.nextFloat();
        float diam3 = input.nextFloat();
        System.out.println("Enter the 2 unit price of the border materials to compare:");
        float mat1 = input.nextFloat();
        float mat2 = input.nextFloat();
        System.out.println("\nhere is your cost comparison report:\n");
        System.out.format("Circle   Circumference   Cost of Material1  Cost of Material 2");
        System.out.format("\nA %20f %20f %20f",(diam1*3.14),(diam1*mat1*3.14),(diam1*mat2*3.14));
        System.out.format("\nB %20f %20f %20f",(diam2*3.14),(diam2*mat1*3.14),(diam2*mat2*3.14));
        System.out.format("\nC %20f %20f %20f",(diam3*3.14),(diam3*mat1*3.14),(diam3*mat2*3.14));
    }
}
```

### Project 1 Phase 1 Plan
I didn't really know how to plan for this project so I wrote the easier half of the code and tried to make since of how the Diffie-Hellman Key Exchange works 
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner inRead = new Scanner(System.in);
        System.out.print("Enter your Base: ");
        int base = inRead.nextInt();
        System.out.print("Enter your Modulus: ");
        int mod = inRead.nextInt();
        System.out.print("Enter your name: ");
        String n1 = inRead.next();
        System.out.print("Enter your private number: ");
        int n1n = inRead.nextInt();
        System.out.print("Enter your partner's name: ");
        String n2 = inRead.next();
        System.out.print("Enter your partner's private2 number: ");
        int n2n = inRead.nextInt();
        System.out.print(n1 + "'s keys are:")
        int
    }
}
```

### Week 1 Pairing Practice
9/6/23 (I think?)
```
import java.util.*;

public class Main {
	public static void main(String[] args) {
        Scanner stdin = new Scanner(System.in);
        System.out.println("Please enter a tempurature in Fahrenheit: ");
        double Df = stdin.nextDouble();
        double Dc;
        Df = Df - 32;
        Df = Df / 9;
        Dc = Df * 5;
        System.out.println("The equivalent tempurature in Celsius is: " + Dc);
    }
}
```
