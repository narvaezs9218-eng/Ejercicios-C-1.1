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

//---------------------------------------------------------------


using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
       int x, y, z;
       x = y = z = 50;
       Console.WriteLine(x + y + z);

    }
}

//------------------------------------------------------------------


using System;

namespace ejercicio7
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine(Math.Max(5, 10));  
     }
  }
}

//----------------------------------------------------

using System;

namespace ejercicio9
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine(Math.Sqrt(64));  
     }
  }
}

//----------------------------------------------------------------------------

using System;

namespace ejercicio10
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine(Math.Abs(-4.7));  
     }
  }
}

//-------------------------------------------------------------------------

using System;

namespace ejercicio11
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine(Math.Round(9.99));
     }
  }
}

//------------------------------------------------------------------------------------

using System;

namespace ejercicio12   
{
  class Program
  {
    static void Main(string[] args)
    {

        double numero = 27.0;
        double resultado = Math.Cbrt(numero);
      Console.WriteLine($"La raiz cubica de {numero} es: {resultado}");
     }
  }
}

//--------------------------------------------------------------------------

using System;

namespace ejercicio13
{
  class Program
  {
    static void Main(string[] args)
    {
      string greeting = "Hello";
      Console.WriteLine(greeting);  
     }
  }
}

//------------------------------------------------------------------------

using System;

namespace ejercicio14
{
  class Program
  {
    static void Main(string[] args)
    {
      string txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
      Console.WriteLine("The length of the txt string is: " + txt.Length);
    }
  }
}

//----------------------------------------------------------------------------------------

using System;

namespace ejercicio15
{
  class Program
  {
    static void Main(string[] args)
    {
      string txt = "Hello World";
      Console.WriteLine(txt.ToUpper());   // Outputs "HELLO WORLD"
      Console.WriteLine(txt.ToLower());   // Outputs "hello world"
    }
  }
}

//----------------------------------------------------------------------------------------------------

using System;

namespace ejercicio16
{
  class Program
  {
    static void Main(string[] args)
    {
      string firstName = "John ";
      string lastName = "Doe";
      string name = firstName + lastName;
      Console.WriteLine(name);
    }
  }
}

//----------------------------------------------------------------------------------------

using System;

namespace ejercicio17
{
  class Program
  {
    static void Main(string[] args)
    {
      string firstName = "John ";
      string lastName = "Doe";
      string name = string.Concat(firstName, lastName);
      Console.WriteLine(name);
    }
  }
}

//------------------------------------------------------------------------------------------------

using System;

namespace ejercicio18
{
  class Program
  {
    static void Main(string[] args)
    {
      int x = 10;
      int y = 20;
      int z = x + y;
      Console.WriteLine(z);
    }
  }
}

//------------------------------------------------------------------------------------

using System;

namespace ejercicio19
{
  class Program
  {
    static void Main(string[] args)
    {
      string x = "10";
      string y = "20";
      string z = x + y;
      Console.WriteLine(z);
    }
  }
}

//-------------------------------------------------------------------------------------------------

using System;

namespace ejercicio20
{
  class Program
  {
    static void Main(string[] args)
    {
      string firstName = "John";
      string lastName = "Doe";
      string name = $"My full name is: {firstName} {lastName}";
      Console.WriteLine(name);
    }
  }
}


//--------------------------------------------------------------------------------------------------


using System;

namespace ejercicio21
{
  class Program
  {
    static void Main(string[] args)
    {
      string myString = "Hello";
      Console.WriteLine(myString[3]);
    }
  }
}

//-------------------------------------------------------------------------------------------

using System;

namespace ejercicio22
{
  class Program
  {
    static void Main(string[] args)
    {
      string myString = "Hello";
      Console.WriteLine(myString.IndexOf("e"));
    }
  }
}

//-----------------------------------------------------------------------------------

using System;

namespace ejercicio23
{
  class Program
  {
    static void Main()
    {
      // Full name
      string name = "John Doe";

      // Location of the letter D
      int charPos = name.IndexOf("D");

      // Get last name
      string lastName = name.Substring(charPos);

      // Print the result
      Console.WriteLine(lastName);
    }
  }
}

//----------------------------------------------------------------------------------------------

using System;

namespace ejercicio24
{
  class Program
  {
    static void Main(string[] args)
    {
      string txt = "We are the so-called \"Vikings\" from the north.";
      Console.WriteLine(txt);
    }
  }
}

//---------------------------------------------------------------------------------------------

using System;

namespace ejercicio25
{
  class Program
  {
    static void Main(string[] args)
    {
      string txt = "It\'s alright.";
      Console.WriteLine(txt);
    }
  }
}

//-----------------------------------------------------------------------------------

using System;

namespace ejercicio26
{
  class Program
  {
    static void Main(string[] args)
    {
      string txt = "The character \\ is called backslash.";
      Console.WriteLine(txt);
    }
  }
}

//--------------------------------------------------------------------------------------------

using System;

public class ejercicio27
{
 
        class Car {
            string color = "red";
            
            static void Main(string[] args) {
                Car myObj = new Car();
                Console.WriteLine(myObj.color);
            
        }
    }
}

