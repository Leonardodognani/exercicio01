# :book: Exercício de C# :book:
## Exercício 1
## Crie um algoritmo que retorne se um número é par ou ímpar.

```
namespace exercicio01
{
    class Program
    {


        static void Main(string[] args)
        {
            Console.Write("Olá! Por favor, digite um número: ");
            int numeroDigitado;
            numeroDigitado = Convert.ToInt32(Console.ReadLine());

            if (numeroDigitado % 2 == 0)
            {
                Console.WriteLine($"O número {numeroDigitado} é um número Par.");
            }
            else
            {
                Console.WriteLine($"O número {numeroDigitado} é um número ímpar.");
            }

        }
    }
}
```