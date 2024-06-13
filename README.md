C#
Basic strucuter of C#

  using System;
   class to_write{                // Class 
    static void Main() {
        Console.WriteLine("It's Hero Time");    // It's output syntax. console is panel that open after program runs. We should use CAPITAL LETTER 
           }
Class and Object

using System;
class Car 
{
  string model;         //Variabel
  string color;
  int year;

  static void Main()    //Main Program to run
  {
    Car Ford = new Car();        //First Object
    Ford.model = "Mustang";
    Ford.color = "red";
    Ford.year = 1969;

    Car Opel = new Car();      //Second Object
    Opel.model = "Astra";
    Opel.color = "white";
    Opel.year = 2005;

    Console.WriteLine(Ford.model);    Calling the object
    Console.WriteLine(Opel.model);
  }
}
