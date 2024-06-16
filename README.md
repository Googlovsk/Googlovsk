{

    using System;
    
    class Program
    {
        static void Main(string[] args)
        {
            public bool hasCoffee = true;
            var thisPotatoProgrammer = new Programmer()
            {
                Name = "Igor",
                Age = "18",
                Languages = new string[] { "C#", "Java", "JavaScript", "Python" }
            };
            if (hasCoffee)
            {
                thisPotatoProgrammer.IsCoding();
            }
            else
            {
                Console.WriteLine("Больше кода не будет, Милорд, запасы кофе пожрал долгоносик.");
            }
        }
    }
}
