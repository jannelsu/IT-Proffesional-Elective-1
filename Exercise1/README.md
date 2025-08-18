public class Main {
    public static void main(String[] args) {
        int num1 = 18;
        int num2 = 13;

        int sum = num1 + num2;
        int difference = num1 - num2;
        int product = num1 * num2;
        int quotient = num1 / num2;
        
        if (sum > 30) {
            System.out.println("The sum is greater than 30. Sum = " + sum);
        } else {
            System.out.println("The sum is not greater than 30. Sum = " + sum);
        }

        if (difference == 10) {
            System.out.println("The difference is exactly 10. Difference = " + difference);
        } else {
            System.out.println("The difference is not 10. Difference = " + difference);
        }

        if (product > quotient) {
            System.out.println("The product is greater than the quotient. Product = " + product + ", Quotient = " + quotient);
        } else {
            System.out.println("The quotient is greater or equal to the product. Product = " + product + ", Quotient = " + quotient);
        }
    }
}
