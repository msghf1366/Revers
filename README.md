# Revers
revers Wrold



program code
//-----------------------------------
using System;

namespace ConsoleApp3
{
    class Program
    {
        static void Main(string[] args)
        {
             string Read=Console.ReadLine();
             for (int i = Read.Length - 1; i >=0; i--) Console.Write(Read[i]);
             Console.ReadKey();
        }
        

    }
}
