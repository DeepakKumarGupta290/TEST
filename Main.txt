public class Main {

    void add(int i, int j) {
        System.out.println("Sum of two numbers is " + (i + j));
    }

    void add(int i, int j, int k) {
        System.out.println("Sum of three numbers is " + (i + j + k));
    }

    public static void main(String[] args) {
        Main c = new Main();
        c.add(2, 5);        // Calls method with 2 arguments
        c.add(10, 12, 30);  // Calls method with 3 arguments
    }
}