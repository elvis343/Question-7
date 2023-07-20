# Question-7
public class TotalNumbers {
    public static void main(String[] args) {
        int start = 20;
        int end = 25;
        int sum = 0;

        for (int i = start; i <= end; i++) {
            sum += i;
        }

        System.out.println("The Total of numbers between " + start + " and " + end + " is: " + sum);
    }
}
