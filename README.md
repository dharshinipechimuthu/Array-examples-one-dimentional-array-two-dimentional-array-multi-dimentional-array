# Array-examples-one-dimentional-array-two-dimentional-array-multi-dimentional-array
public class ArrayExamples {
    public static void main(String[] args){
        System.out.println("One-Dimensional Array Example:");
        int[] oneDArray = {10, 20, 30, 40, 50};
        for (int i = 0; i < oneDArray.length; i++) {
            System.out.println("Element at index " + i + ": " + oneDArray[i]);
        }
        System.out.println("\nTwo-Dimensional Array Example:");
        int[][] twoDArray = {
            {1, 2, 3},
            {4, 5, 6},
            {7, 8, 9}
        };
        for (int i = 0; i < twoDArray.length; i++) {
            for (int j = 0; j < twoDArray[i].length; j++)
  {       System.out.print(twoDArray[i][j] + " ");
            }
            System.out.println();
        }
        System.out.println("\nThree-Dimensional Array Example:");
        int[][][] threeDArray = {
            {
                {1, 2},
                {3, 4}
            },
            {
                {5, 6},
                {7, 8}
            }
        };
        for (int i = 0; i < threeDArray.length; i++) {
            System.out.println("Block " + (i + 1) + ":");
            for (int j = 0; j < threeDArray[i].length; j++) {
                for (int k = 0; k < threeDArray[i][j].length; k++)
  {                    System.out.print(threeDArray[i][j][k] + " ");
                }
                System.out.println();
            }
        }
    }
}
output:
One-Dimensional Array Example:
Element at index 0: 10
Element at index 1: 20
Element at index 2: 30
