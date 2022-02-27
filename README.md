# CSharp-Fibonacciseries

using System;

namespace Fibonacci
{
    public class Example
    {


        public static void Main(string[] args)
        {
            int n1 = 0, n2 = 1, n3, i, number;
            Console.WriteLine("Enter Range");
            number = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine(n1 + "" + n2 + "");
            for (i = 1; i < number;i++)
            {
                n3 = n1 + n2;
                Console.WriteLine(n3 + "");
                n1 = n2;
                n2 = n3;
            }
        }
    }
}
