# Class-Calculator 4th assignment

public class Calculator {

    // Method to add two integers
    public int add(int a, int b) {
        return a + b;
    }

    // Main method to test the add function
    public static void main(String[] args) {
        Calculator calc = new Calculator();

        int result = calc.add(10, 20);
        System.out.println("The sum is: " + result);
    }
}
