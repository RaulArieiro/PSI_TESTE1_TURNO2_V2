# Teste de PSI 1 - Turno 2 - Versão 2

## Informação do aluno

    Nome: Raul

Teste termina às 13:25.

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Indica o que é impresso pelo seguinte código. Justifica a tua resposta

    ulong uL = ulong.MaxValue;

    Console.WriteLine(uL + 1);

P1 - Resposta

    Imprime 0 pois "ulong.MaxValue + 1" é o valor maximo que poderia ser 16 (sei que não é é apenas um exemplo) 16 + 1 seria 17 mas a variavel não tem capacidade para ter mais de 16 então volta para o valor 0.

### P2. Considera o seguinte código com um *bug*

    float f = double.MaxValue;

    Console.WriteLine(f);

### Indica uma possível correção para que o código não apresente erros. Explica porque foi necessário fazer essa correção

P2 - Resposta

    float f = float.MaxValue;

    Console.WriteLine(f);     Tive e substituir o double.MaxValue por float.MaxValue pois a variavel "f" é do tipo float e o float não suporta o valor maximo de double.

### P3. Escreve um programa que solicite ao utilizador dois números reais e apresente o resultado do segundo (base) elevado ao primeiro (expoente). Não podes usar um método da classe Math para obter o resultado

P3 - Resposta

    double re;
    double nr;
    
    Console.WriteLine("Escrava um numero ");
    re = Convert.ToDouble(Console.ReadLine());
    Console.WriteLine("Escrava um numero ");
    nr = Convert.ToDouble(Console.ReadLine());

    for(int i = 0; i<= re; i++){
      re *= re; 
    }
    Console.WriteLine($"{re}");
  }

### P4. Estás na pasta raiz do teu repositório local, onde atualizaste um ficheiro de nome 'Perks.cs'. Queres enviar **apenas** esta atualização para o teu repositório remoto. Indica os comandos necessários. A mensagem de commit deve ser apropriada

P4 - Resposta

    git status / para ver o como está o programa e se posso dar commit / git add Perks.cs / para adicionar o ficheiro já alterado / git commit -m "Atualizei o ficheiro com as alterações" / um commit com o que foi feito para dar conteisto /  git push / para guardar no GitHub. /
