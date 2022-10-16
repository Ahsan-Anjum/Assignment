import java.util.Scanner;

public class Rectangle {
	public static void main(String[] args) {
		// Area = length * Breadth
		// Perimeter = 2 * (length + width)
		
		Scanner scanner = new Scanner (System.in);
		
		int length = 0;
		int width = 0;
		int area = 0;
		int perimeter = 0;
		
		System.out.println("Enter the length of Rectangle : ");
		length = scanner.nextInt();
		
		System.out.println("Enter the width of Rectangle : ");
		width = scanner.nextInt();
		
		area = length * width;
		perimeter = 2 * (length + width);
		
		System.out.println("The Area of Rectangle is : " + area);
		System.out.println("The Perimeter of Rectangle is : " + perimeter);
		
		
	}
}
