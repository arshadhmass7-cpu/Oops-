import java.util.Scanner;
public class FibonacciCalculator {

    public int fibonacci(int n) {
        if (n <= 1) {
            return n;
        }
        return fibonacci(n - 1) + fibonacci(n - 2);
    }
    public static void main(String[] args) {
        FibonacciCalculator calculator = new FibonacciCalculator();

        Scanner sc = new Scanner(System.in);
	System.out.print("Enter the number:");
        int s = sc.nextInt(); 
        System.out.println("Fibonacci Series up to " + s + " terms:");
        for (int i = 0; i < s; i++) {
            System.out.print(calculator.fibonacci(i) + " ");
        }
    }
}
