  private static void Main(string[] args)
    {
        int A, B, C;
        

        Console.WriteLine("Digite o 1º número:");
        A= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Digite o 2º número:");
        B= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Digite  o 3º número:");
        C= Convert.ToInt32(Console.ReadLine());

        if (A > B)
        {
         if (A > C)
            {
                Console.WriteLine("\n O maior número é: " + A);
            }
        }
        else if (B > C) 
        {
            if (B > A)
            {
                Console.WriteLine("\n O maior número é: " + B);
            }
        }
        else 
        {
            Console.WriteLine("\n O maior número é: " + C);
        }
        

        
    }