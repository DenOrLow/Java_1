# Java_1
package com.company;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        System.out.println("Hello world");
        int num, sum = 0;
        Scanner obj = new Scanner(System.in);
        num = obj.nextInt();
        int[] arr = new int[num];
        for (int i = 0; i < num; i++)
            arr[i] = obj.nextInt();
        System.out.println("Sum of array elements you entered are: ");
        for (int i = 0; i < num; i++)
            sum += arr[i];
        System.out.println(sum);
        sum = 0;
        int i = 0;
        while (i < num)
        {
            sum += arr[i];
            i++;
        }
        System.out.println(sum);
        sum = 0;
        i = 0;
        do {
            sum += arr[i];
            i++;
        } while (i < num);
        System.out.println(sum);
    }
}
