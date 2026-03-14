# java-test-0004-final-16431-shivani
Final Project Assignment - This repository contains the complete final project code and documentation.
```java
public class ConcentricPattern {
    public static void main(String[] args) {
        int n = 4;
        int size = 2 * n - 1;
        for (int i = 0; i < size; i++) {
            for (int j = 0; j < size; j++) {
                 int top = i;
                int left = j;
                int bottom = size - 1 - i;
                int right = size - 1 - j;
                int min = Math.min(Math.min(top, bottom), Math.min(left, right));
                System.out.print((n - min) + " ");
            }
            System.out.println();
        }
    }
}
```
