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
    if (opcjaAH == "2")
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
    while (opcjaAH != "2")
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
    if (opcjaBL == "3")
    {
        Console.Clear();
        Console.Write("Poprawna odpowiedz");
        BL = Console.ReadLine();
        SprawdzBH();
    }
    else
    {
        Console.Clear();
        Console.WriteLine("Błędny wybór");
    }
    while (opcjaBL != "3")
    {
        Console.ReadLine();
        SprawdzBH();
        opcjaBL = Console.ReadLine();
    }
}
static void SprawdzBH()
    {
        string BH;
        Console.Clear();
        Console.WriteLine("Podaj wartość rejestru BH:");
        string opcjaBH = Console.ReadLine();
        if (opcjaBH == "4")
        {
            Console.Clear();
            Console.Write("Poprawna odpowiedz");
            BH = Console.ReadLine();
            SprawdzCL();
    }
        else
        {
            Console.Clear();
            Console.WriteLine("Błędny wybór");

        }

        while (opcjaBH != "4")

        {

            Console.ReadLine();
            SprawdzBH();
            opcjaBH = Console.ReadLine();
        }
    }
static void SprawdzCL()
{
    string CL;
    Console.Clear();
    Console.WriteLine("Podaj wartość rejestru CL:");
    string opcjaCL = Console.ReadLine();
    if (opcjaCL == "5")
    {
        Console.Clear();
        Console.Write("Poprawna odpowiedz");
        CL = Console.ReadLine();
        SprawdzCH();
    }
    else
    {
        Console.Clear();
        Console.WriteLine("Błędny wybór");
    }
    while (opcjaCL != "5")
    {
        Console.ReadLine();
        SprawdzBH();
        opcjaCL = Console.ReadLine();
    }
}
static void SprawdzCH()
{
    string CH;
    Console.Clear();
    Console.WriteLine("Podaj wartość rejestru CH:");
    string opcjaCH = Console.ReadLine();
    if (opcjaCH == "6")
    {
        Console.Clear();
        Console.Write("Poprawna odpowiedz");
        CH = Console.ReadLine();
        SprawdzDL();
    }
    else
    {
        Console.Clear();
        Console.WriteLine("Błędny wybór");
    }
    while (opcjaCH != "6")
    {
        Console.ReadLine();
        SprawdzCH();
        opcjaCH = Console.ReadLine();
    }
}
static void SprawdzDL()
{
    string DL;
    Console.Clear();
    Console.WriteLine("Podaj wartość rejestru DL:");
    string opcjaDL = Console.ReadLine();
    if (opcjaDL == "7")
    {
        Console.Clear();
        Console.Write("Poprawna odpowiedz");
        DL = Console.ReadLine();
        SprawdzDH();
    }
    else
    {
        Console.Clear();
        Console.WriteLine("Błędny wybór");
    }
    while (opcjaDL != "7")
    {

        Console.ReadLine();
        SprawdzDL();
        opcjaDL = Console.ReadLine();
    }
}
static void SprawdzDH()
{
    string DH;
    Console.Clear();
    Console.WriteLine("Podaj wartość rejestru DH:");
    string opcjaDH = Console.ReadLine();
    if (opcjaDH == "8")
    {
        Console.Clear();
        Console.Write("Poprawna odpowiedz");
        DH = Console.ReadLine();
    }
    else
    {
        Console.Clear();
        Console.WriteLine("Błędny wybór");
    }
    while (opcjaDH != "8")
    {
        Console.ReadLine();
        SprawdzDH();
        opcjaDH = Console.ReadLine();
    }
}




