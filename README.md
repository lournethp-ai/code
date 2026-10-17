# code
hello
public class Main {

    public static void tryToDouble(int x) {
        x = x * 2;
    }

    public static void main(String[] args) {
        int num = 7;
        tryToDouble(num);
        System.out.println(num); // prints 7
    }
}
