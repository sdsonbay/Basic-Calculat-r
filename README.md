# Basic-Calculat-r

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int n1, n2, operator;
        Scanner scanner = new Scanner(System.in);
        n1 = scanner.nextInt();
        n2 = scanner.nextInt();
        operator = scanner.nextInt();

        switch (operator)
        {
            case 1:
                System.out.println(n1 + n2);
                break;
            case 2:
                System.out.println(n1 - n2);
                break;
            case 3:
                System.out.println(n1 * n2);
                break;
            case 4:
                double d1 = n1, d2 = n2;
                System.out.println((d1 / d2));
                break;
            default:
                System.out.println("Wrong input");
        }
    }
}
