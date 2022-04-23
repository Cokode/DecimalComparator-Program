# DecimalComparator-Program
This program checks if two parameters are the same up to 3 decimal number 

public class DecimalComparator {

    public static boolean areEqualByThreeDecimalPlaces(double x, double y) {


        x = (int) x * 1000;
        y = (int) y * 1000;
        if (x == y) {
            return true;
        } else

            return false;
            // this also solves the problem.
        //  public static boolean areEqualByThreeDecimalPlaces(double num1, double num2) {
        //        return (int) (num1 * 1000) == (int) (num2 * 1000);

    }

    public static void main(String[] args) {
            System.out.println(areEqualByThreeDecimalPlaces(154.786, 154.786678));

    }
}
