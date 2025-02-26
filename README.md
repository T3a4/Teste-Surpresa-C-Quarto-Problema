using System;

class Program
{
    static void Main()
    {
        // Solicita ao usuário que insira o raio do círculo
        Console.WriteLine("Digite o raio do círculo:");
        double raio = Convert.ToDouble(Console.ReadLine());

        // Define o valor de pi
        const double pi = 3.14159;

        // Calcula o perímetro do círculo
        double perímetro = 2 * pi * raio;

        // Exibe o reultado
        Console.WriteLine($"O perímetro do círculo é: {perímetro:F2}");
    }
}
