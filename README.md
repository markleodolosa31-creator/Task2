using System;

class Task2
{
    static void Main()
    {
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 }, // Row of even numbers
            new int[] { 1, 3, 5, 7, 9 }  // Row of odd numbers
        };

        Console.WriteLine("The number matrix has been initialized.");

        int digit1 = numberMatrix[1][3]; // 7
        int digit2 = numberMatrix[0][0]; // 2
        int digit3 = numberMatrix[1][4]; // 9

        string finalKey = digit1.ToString() + digit2.ToString() + digit3.ToString();

        Console.WriteLine("The password is: " + finalKey);
    }
}
