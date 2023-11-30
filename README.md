# calculadora-de-partidas-rankeadas
**Segundoo Desafio proposto pela DIO do Bootcamp Potência Tech ifood-Programação do Zero utilizando a linguagem Javascript e o VS Code.**

# 2️⃣ Calculadora de Partidas Rankeadas
## Objetivo

Crie uma função que recebe como parâmetro a quantidade de vitórias e derrotas de um jogador, depois disso retorne o resultado para uma variável, o saldo de Rankeadas deve ser feito através do calculo (vitórias - derrotas)

Se vitórias for menor do que 10 = Ferro
Se vitórias for entre 11 e 20 = Bronze
Se vitórias for entre 21 e 50 = Prata
Se vitórias for entre 51 e 80 = Ouro
Se vitórias for entre 81 e 90 = Diamante
Se vitórias for entre 91 e 100= Lendário
Se vitórias for maior ou igual a 101 = Imortal

**Ao final deve se exibir uma mensagem:**
"O Herói tem de saldo de **{saldoVitorias}** está no nível de **{nivel}**"

## Conhecimentos aplicados no jogo

**Declaração de Função (function)**: O código define uma função chamada calcularNivelRankeada, que aceita dois parâmetros: vitorias e derrotas.
**Declaração de Variáveis ​​(const e let)**: Utiliza a palavra-chave **const** para declarar a constante saldoVitorias e **let** para declarar a variável nível.
**Operadores Aritméticos (-)**: Calcula o saldo de vitórias **subtraindo** o número de derrotas do número de vitórias (const saldoVitorias = vitorias - derrotas;).
**Estrutura de Controle (if-else if-else)**: Utiliza uma estrutura condicional para determinar o nível do herói com base no número de vitórias. Cada bloco if** ou **else if** contém condições que comparam o número de vitórias com intervenções específicas.
**Literais de modelo**: Utiliza templates literais (delimitados por crases) para criar uma string que inclua o saldo de vitórias e o nível do herói. *Exemplo*: O Herói tem um saldo de ${saldoVitorias} e está no nível: ${nivel}.
**Chamada de Função (calcularNivelRankeada(150, 5);)**: Chama a função calcularNivelRankeadacom os valores 150 e 5 como argumentos para vitoriase derrotas, respectivamente.
**Saída no Console (console.log)**: Imprime no console uma string resultante que inclui o saldo de vitórias e o nível do herói.
**Conceitos Lógicos (&&, <, >=)**: Usa operadores lógicos ( &&, <, >=).
 

  
