using System;

// Dummy class with a method
public class DummyClass
{
    private string name;

    public DummyClass(string name)
    {
        this.name = name;

    }

    public string Greet()
    {
        return $"Hello, {name}!";
    }

    public static void Main(string[] args)
    {
        // Dummy method to add two numbers
        int result = Add(5, 3);
        Console.WriteLine($"Result of add: {result}");

        DummyClass dummy = new DummyClass("World");
        Console.WriteLine(dummy.Greet());
    }

    public static int Add(int a, int b)
    {
        return a + b;
    }
}
