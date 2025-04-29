# assignment-5th

    public class MinMaxInArray {

    public static void main(String[] args) {
        int[] arr = {15, 3, 9, 28, 6, 19, 2};

        if (arr.length == 0) {
            System.out.println("Array is empty.");
            return;
        }

        int min = arr[0];
        int max = arr[0];

        for (int i = 1; i < arr.length; i++) {
            if (arr[i] < min) {
                min = arr[i];
            }
            if (arr[i] > max) {
                max = arr[i];
            }
        }

        System.out.println("Smallest element: " + min);
        System.out.println("Largest element: " + max);
        }
      }
