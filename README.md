# CPSC_devlog
A record of all the coding I do for my computer science class
In order of most recent

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
