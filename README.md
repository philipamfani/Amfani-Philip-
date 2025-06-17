# Amfani-Philip-
Barka's class
import java.util.Scanner;

//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
public class Main {
    public static void main(String[] args) {


        Scanner input = new Scanner(System.in);


        int[] myArray = {1, 3, 5, 7, 9};
        int[] anotherArray = new int[10];
        anotherArray[0] = 1;
        String[] gender = {"Female", "Male"};

        for (int i = 0; i < myArray.length; i++) {
            System.out.println("insert item at: " + i);
            anotherArray[i] = input.nextInt();
        }
        for (int i = 0; i < anotherArray.length; i++){
            if (anotherArray[i] == 13){

            System.out.println("item at:" +i+ " is "+ anotherArray[i]);
        }
    }
}
