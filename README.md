# Multiplication-Table
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Multiplication_Table
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            for (int i = 1; i <= 10; i++)
            {
                int sum = i * n;
                Console.WriteLine($"{n} X {i} = {sum}");
            }
        }
    }
}
