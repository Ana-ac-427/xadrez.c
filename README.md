♟️ Desafio Final — Criando Movimentos Complexos (Xadrez em C)
🧩 Descrição do Projeto

Este projeto é o desafio final do módulo de Estruturas de Repetição em C, cujo objetivo é aplicar recursividade e loops aninhados/complexos para simular os movimentos das principais peças do xadrez.

O código implementa o comportamento das peças Torre, Bispo, Rainha e Cavalo, de forma individual e didática, com foco no uso de técnicas avançadas de programação.

🧠 Funcionalidades Implementadas
♜ Torre

Movimento em linha reta (horizontal ou vertical).

Implementação recursiva para imprimir cada passo.

Exemplo de saída:

Direita
Direita
Direita

♝ Bispo

Movimento nas diagonais do tabuleiro.

Utiliza recursividade combinada com loops aninhados (vertical e horizontal).

Exemplo de saída:

Diagonal Cima Direita
Diagonal Baixo Esquerda

♛ Rainha

Combina os movimentos da Torre e do Bispo.

Implementação recursiva simples, simulando deslocamentos em múltiplas direções.

Exemplo de saída:

Esquerda
Esquerda

♞ Cavalo

Movimento em “L”: duas casas para cima e uma para a direita.

Implementado com loops aninhados, utilizando continue e break para controle de fluxo.

Exemplo de saída:

Cima
Cima
Direita

⚙️ Estrutura do Código

O programa principal (xadrez.c) contém:

Funções separadas para cada peça (torre(), bispo(), rainha(), cavalo()).

Chamada das funções a partir da main().

Impressões organizadas e separadas por seções.

Comentários explicativos sobre lógica e funcionamento dos loops e recursões.

🧾 Requisitos Atendidos

✅ Recursividade: implementada na Torre, Bispo e Rainha.
✅ Loops aninhados: utilizados no Bispo e Cavalo.
✅ Controle de fluxo: uso de continue e break.
✅ Saída formatada: direções claras e legíveis no console.
✅ Código documentado: comentários descritivos em cada função.
✅ Performance e legibilidade: sem loops infinitos, indentação e nomes adequados.

💻 Execução

Compile o programa:

gcc xadrez.c -o xadrez


Execute:

./xadrez


Observe a saída no console mostrando os movimentos de cada peça.

🧑‍💻 Autor

Ana Clara do Nascimento de Oliveira
Disciplina: Introdução à Programação de Computadores
Desafio Final — Criando Movimentos Complexos
