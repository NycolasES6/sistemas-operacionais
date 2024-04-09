# Processos

## Definição de um Processo

Um processo é caracterizado por um programa em execução. Um processo é uma instância de um programa e possui dados de entrada,  dados de saída e um estado (executando, bloqueando, pronto).

## Programa vs processo

 - Um programa pode ter várias instâncias em execução (em diferentes processos).
 - É um algoritimo codificado.
 - Forma como o programador vê a tarefa a ser executada.

 - Um processo é único.
 - Código acompanhado de dados e estado.
 - Forma pela qual o SO vê um programa e possibilita a sua execução.

## Processo em primeiro plano

Interage com o usuário.

 - Ler um arquivo
 - Iniciar um programa (linha de comando ou um duplo clique no mouse).

## Processo em segundo plano

Processos com funções específicas que independem de usuários - daemons:

 - Recepção e envio de emails.
 - Serviços de impressão.

## Cada processo possui

1. Conjunto de instruções
2. Espaço de endereçamento (espaço reservado para que o processo possa ler e escrever - 0 até max)
3. Contexto de hardware (valores nos registradores, como PC, ponteiro de pilha, e reg. de prop gerais)
4. Contexto de software (atributos em geral, como lista de arquivos abertos, variáveis, etc. )

## Espaço de endereçamento

1. Texto: Código executável do(s) programa(s);
2. Dados: As variáveis;
3. Pilha de execução do processo;







