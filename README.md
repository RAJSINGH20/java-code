# java-code

public class isDivisibleByFiveAndSeven{
    public static void main(String[] args) {
        int number = 35;
        if (isDivisibleByFiveAndSeven(number)) {
            System.out.println(number + " is divisible by both 5 and 7.");
        } else {
            System.out.println(number + " is not divisible by both 5 and 7.");
        }
    }
    public static boolean isDivisibleByFiveAndSeven(int number) {
        return (number % 5 == 0) && (number % 7 == 0);
    }
}
