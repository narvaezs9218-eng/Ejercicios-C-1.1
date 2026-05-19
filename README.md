# Ejercicios-C-1.1
using System;

namespace EjercicioApp
{
    class Ejercicio_1
    {
        static void Main(string[] args)
        {
            int myInt = 9;
            double myDouble = myInt;  
            
            Console.WriteLine(myInt);
            Console.WriteLine(myDouble);
        }
    }
}
// ------------------------------------------------------
using System;

namespace EjercicioApp
{
    class Ejercicio_2
    {
        static void Main(string[] args)
        {
            double myDouble = 9.78;  
            // Se corrige la sintaxis del casteo colocando el tipo entre paréntesis
            int myInt = (int)myDouble; 
            
            Console.WriteLine(myInt);
            Console.WriteLine(myDouble);
        }
    }
}
//  -----------------------------------------------------
using System;

namespace EjercicioApp
{
    class Ejercicio_3
    {
        public static void Main(string[] args)
        {
            int myInt = 10; 
            
            Console.WriteLine(Convert.ToString(myInt));
        }
    }
}
// -------------------------------------------------------
using System;

namespace EjercicioApp
{
    class Ejercicio_4
    {
        static void Main(string[] args)
        {
           
            double x = 3.5 + 4.75; 
            
            Console.WriteLine(x);
        }
    }
}
// ------------------------------------------------------

using System;

public class Ejercicio 4.1
{
    public static void Main(string[] args)
    {
        int sum1 = 100 + 50;
        int sum2 = sum1 + 250;
        int sum3 = sum2 + sum2;
        
        Console.WriteLine (sum1);
        Console.WriteLine (sum2);
        Console.WriteLine (sum3);
    }
}
// ----------------------------------------------------------

using System;

public class Ejercicio_5
{
    public static void Main(string[] args)
    {
        int x = 5;
        int y = 3;
        
        Console.WriteLine (x > y);
    }
}
