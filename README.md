string nome;
decimal nota1, nota2, media;

Console.WriteLine("digite seu nome:");
nome = Console.ReadLine();

Console.WriteLine("digite a nota 1");
nota1 = Convert.ToDecimal(Console.ReadLine());

Console.WriteLine("digite a nota 2:");
nota2 = Convert.ToDecimal(Console.ReadLine());

media = (nota1 + nota2) / 2;

if (media >= 60) 
{
    Console.WriteLine("parabens " + nome + ", voce nao fez mais que a obrigação");

}
else
{
    Console.WriteLine("voce e um merda " + nome);


}


