public class Main {
    public static void main(String[] args) {
        int sum = 0;
        for (int i = 1; i <= 100; i++) {
            System.out.print(i + "\t");
            if (i % 2 == 0) {
                System.out.println("even");
            } else {
                System.out.println("odd");
            }
            sum += i;
        }
        System.out.println("The sum of all numbers from 1 to 100 is " + sum + ".");
    }
}
