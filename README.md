# Test_1
using System;

namespace Exam_1
{
    class Program
    {
        static void Main(string[] args)
        {
            //int i, j, k;
            //for (i = 1; i < 5; i++)
            //{
            //    Console.WriteLine(i);


            //    {
            //   Console.WriteLine(i+j);
            //   }
            //  Console.ReadLine();
            //}
            Console.WriteLine("Welcome to Employee Management");
            Console.WriteLine("1. Add Employee");
            Console.WriteLine("2. Edit Employee");
            Console.WriteLine("3. Search for Employee");
            Console.WriteLine("4. Show all Employees");
            Console.WriteLine("5. Delete Employee");
            Console.WriteLine("6. Exit");

            Console.Write("Enter Your Choice");
            int Choices = Convert.ToInt32(Console.ReadLine());
            //Console.ReadLine();
            if (Choices == 1)
            {
                Console.Write("Enter Employee ID");
                String EMPID = Console.ReadLine();
                Console.WriteLine(EMPID);
            }
            else if (Choices == 2)
            {
                Console.Write("Enter Employee Name");
                String EMPName = Console.ReadLine();
                Console.WriteLine(EMPName);
            }
            else if (Choices == 3)
            {
                Console.Write("Enter Employee Phone No");
                String EMPPNO = Console.ReadLine();
                Console.WriteLine(EMPPNO);
            }
            else if (Choices == 4)
            {
                Console.Write("Enter Employee City");
                String EMPCTY = Console.ReadLine();
                Console.WriteLine(EMPCTY);
            }

        }
    }
}
