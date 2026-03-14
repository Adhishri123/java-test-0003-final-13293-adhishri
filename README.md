# java-test-0003-final-13293-adhishri
Final Project Assignment - This repository contains the complete final project code and documentation.
public class BinaryTrianglePattern {
    public static void main(String[] args) {
        int rows = 6;

        for (int i = 1; i <= rows; i++) {        // Outer loop for rows
            for (int j = 1; j <= i; j++) {       // Inner loop for columns
                
                if ((i + j) % 2 == 0)
                    System.out.print("1 ");
                else
                    System.out.print("0 ");
            }
            System.out.println();               // Move to next line
        }
    }
}
