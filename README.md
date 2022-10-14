using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)

        {
            string AL;


            SprawdzAL();
        }


        static void SprawdzAL()


        {
            string AL;

            Console.WriteLine("Podaj wartość rejestru AL:");
            string opcjaAL = Console.ReadLine();
            if (opcjaAL == "1")
            {

                Console.Clear();
                Console.Write("Poprawna odpowiedz");
                AL = Console.ReadLine();
                SprawdzAH();
                
            }
            else
            {
                Console.Clear();
                Console.WriteLine("Błędny wybór");
                
            }

            while (opcjaAL != "1")

            {

                SprawdzAL();
                opcjaAL = Console.ReadLine();

            }
        }
        static void SprawdzAH()

        {
            string AH;
            Console.Clear();
            Console.WriteLine("Podaj wartość rejestru AH:");
            string opcjaAH = Console.ReadLine();
            if (opcjaAH == "10") 
            {
                Console.Clear();
                Console.Write("Poprawna odpowiedz");
                AH = Console.ReadLine();
                SprawdzBL();


            }
            else
            {
                Console.Clear();
                Console.WriteLine("Błędny wybór");
                SprawdzAH();
            }

            while (opcjaAH != "10")

            {
                
                Console.ReadLine();
                
                opcjaAH = Console.ReadLine();
            }




        }

        static void SprawdzBL()

        {
            string BL;
            Console.Clear();
            Console.WriteLine("Podaj wartość rejestru BL:");
            string opcjaBL = Console.ReadLine();
            if (opcjaBL == "100")
            {
                Console.Clear();
                Console.Write("Poprawna odpowiedz");
                BL = Console.ReadLine();      


            }
            else
            {
                Console.Clear();
                Console.WriteLine("Błędny wybór");

            }

            while (opcjaBL != "100")

            {

                Console.ReadLine();
                SprawdzBL();
                opcjaBL = Console.ReadLine();
            }




        }

    }
}













