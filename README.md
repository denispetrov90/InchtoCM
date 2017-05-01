using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Inches_to_Centimeters
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Inches -  ");
            var a = double.Parse(Console.ReadLine());
            var area = a * 2.54;
            Console.WriteLine("Cantimeters = ");
            Console.WriteLine(area);
        }
    }
}
