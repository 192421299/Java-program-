# Java-program-
import java.io.*;

class Market {
    public static void main(String[] args) {
        int ricePrice = 50;
        int oilPrice = 150;
        int sugarPrice = 40;

        int riceQty = 10;
        int oilQty = 2;
        int sugarQty = 5;

        int total = (ricePrice * riceQty) + (oilPrice * oilQty) + (sugarPrice * sugarQty);
        System.out.println("Total Price: " + total);

        int discount = total - (total / 10);  // 10% discount
        System.out.println("Price after 10% discount: " + discount);
    }
.}