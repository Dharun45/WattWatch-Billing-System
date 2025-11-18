import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Note: Current reading must be greater than or equal to previous reading.\n");
        System.out.print("Enter number of households: ");
        int n = scanner.nextInt();
        scanner.nextLine();

        for (int i = 0; i < n; i++) {

            System.out.println("\nEnter details for Household " + (i + 1));

            System.out.print("Consumer Number: ");
            int consumerNo = scanner.nextInt();
            scanner.nextLine();

            System.out.print("Consumer Name: ");
            String consumerName = scanner.nextLine();

            System.out.print("Previous Meter Reading: ");
            int prevReading = scanner.nextInt();

            System.out.print("Current Meter Reading: ");
            int currReading = scanner.nextInt();
            scanner.nextLine();

            System.out.print("Connection Type (Domestic/Commercial): ");
            String connType = scanner.nextLine();

            Assets bill = new Assets(
                    consumerNo, consumerName, prevReading, currReading, connType
            );

            bill.displayBill();
            scanner.close();
        }

        
    }
}
