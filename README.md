# ⚠️ Importante!!!
Você pode escolher qualquer um dos desafios para desenvolver. Sinta-se à vontade para começar pelo desafio que mais lhe interessa.

# Desafio de Xadrez - MateCheck

Bem-vindo ao desafio de Xadrez da MateCheck! Este projeto tem como objetivo testar e determinar os limites de utilização do código dentro do jogo utilizando estruturas de repetição e funções avançadas.

## Níveis do Desafio

Movimentando as Peças do xadrez


Este desafio foca na movimentação das peças de xadrez usando estruturas de repetição em C. Você aplicará o que aprendeu sobre for, while e do-while para simular movimentos no tabuleiro.


O que você vai fazer


Você deverá criar um único programa em C que simule o movimento de três peças: Torre, Bispo e Rainha. Para cada peça, utilize uma estrutura de repetição diferente (for, while ou do-while) para simular seu movimento. O programa deverá imprimir no console a direção do movimento a cada casa percorrida pela peça.

 

Torre: Move-se em linha reta horizontalmente ou verticalmente. Seu programa deverá simular o movimento da Torre cinco casas para a direita.
 
Bispo: Move-se na diagonal. Seu programa deverá simular o movimento do Bispo cinco casas na diagonal para cima e à direita. Para representar a diagonal, você imprimirá a combinação de duas direções a cada casa (ex: "Cima, Direita").
 
Rainha: Move-se em todas as direções. Seu programa deverá simular o movimento da Rainha oito casas para a esquerda.

Requisitos funcionais


Entrada de Dados: Os valores para o número de casas a serem movidas serão definidos diretamente no código através de variáveis ou constantes.
 
Lógica de Movimentação: Cada programa deverá implementar a lógica de movimento específica de cada peça (Torre, Bispo, Rainha).
 
Saída de Dados: O programa deverá imprimir no console a direção do movimento a cada casa percorrida pela peça. Para movimentos na diagonal (Bispo), imprimir a combinação de duas direções. Utilize o comando printf para exibir as informações. As saídas devem seguir o padrão: printf("Cima\n");, printf("Baixo\n");, printf("Esquerda\n");, printf("Direita\n");, printf("Cima Esquerda\n"); printf("Direita\n");

Requisitos não funcionais


Performance: O código deve ser eficiente e executar sem atrasos perceptíveis.
 
Documentação: O código deve ser bem documentado com comentários explicando a lógica de cada parte.
 
Legibilidade: O código deve ser claro, organizado e fácil de entender, com nomes de variáveis descritivos e indentação adequada. Utilize apenas variáveis do tipo inteiro e string.

Simplificações para o nível básico


Não é necessário validar a entrada do usuário.
 
Não é necessário implementar a lógica completa do jogo de xadrez, apenas a simulação do movimento de cada peça individualmente.
 
Utilize apenas as estruturas de repetição for, while e do-while, uma para cada peça do jogo.

### 🏅 Nível Aventureiro
Agora que já conseguimos mover as peças mais simples usando loops, os desenvolvedores pediram para elaborar os loops de outra forma. Para o desafio, moveremos o cavalo, que possui sua movimentação em L. O cavalo deve se movimentar para baixo e para a esquerda, usando pelo menos duas estruturas de repetição: uma deve ser for e a outra pode ser while ou do-while.

**Movimentação do Cavalo:**

Mover o cavalo em L utilizando loops aninhados.
Obs: É obrigatório o uso de loops aninhados.

### 🥇 Nível Mestre
Para o desafio final, as peças que utilizam loops simples terão seus códigos trocados por **funções recursivas**, e a movimentação do cavalo utilizará loops com variáveis múltiplas e/ou condições múltiplas, permitindo o uso de continue e break.

**Movimentação das Peças:**

**Bispo**: 5 casas na diagonal direita para cima
**Torre**: 5 casas para a direita
**Rainha**: 8 casas para a esquerda
**Cavalo**: 1 vez em L para cima à direita
Obs: É obrigatório o uso de loops aninhados na movimentação do bispo e funções recursivas.

Ao concluir este desafio, você terá um conhecimento mais profundo de estruturas complexas e elaboradas, amplamente utilizadas no mercado de trabalho. Boa sorte e boa programação!

Equipe de Ensino - MateCheck

Nível Novato - Movimentação das Peças
   Sugestão: Declare variáveis constantes para representar o número de casas que cada peça pode se mover.

   Implementação de Movimentação do Bispo
   Sugestão: Utilize uma estrutura de repetição para simular a movimentação do Bispo em diagonal.

   Implementação de Movimentação da Torre
   Sugestão: Utilize uma estrutura de repetição para simular a movimentação da Torre para a direita.

   Implementação de Movimentação da Rainha
   Sugestão: Utilize uma estrutura de repetição para simular a movimentação da Rainha para a esquerda.

   Nível Aventureiro - Movimentação do Cavalo
   Sugestão: Utilize loops aninhados para simular a movimentação do Cavalo em L.
   Um loop pode representar a movimentação horizontal e outro vertical.

   Nível Mestre - Funções Recursivas e Loops Aninhados
   Sugestão: Substitua as movimentações das peças por funções recursivas.
   Exemplo: Crie uma função recursiva para o movimento do Bispo.

   Sugestão: Implemente a movimentação do Cavalo utilizando loops com variáveis múltiplas e condições avançadas.
   Inclua o uso de continue e break dentro dos loops.

