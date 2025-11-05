// Task2.cs
using System;

class Task2
{
    static void Main()
    {
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 }, //Rows of even numbers
            new int[] { 1, 3, 5, 7, 9 } //Rows of odd numbers
        };

        Console.WriteLine("The number matrix has been initialized.");

        int digit1 = numberMatrix[1][3];
        int digit2 = numberMatrix[0][0];
        int digit3 = numberMatrix[1][4];

        string finalKey = digit1.ToString() + digit2.ToString() + digit3.ToString();

        Console.WriteLine("The password is: " + finalKey);
    }
}
