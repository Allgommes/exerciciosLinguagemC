Olá! Este é um `README.md` para um repositório GitHub da UFCD 5412 - PROGRAMACAO DE COMPUTADOR - ESTRUTURADA, elaborado com base nas informações fornecidas.

---

# UFCD 5412: Programação de Computador - Estruturada

Este repositório contém exemplos de código, exercícios e projetos desenvolvidos no âmbito da Unidade de Formação de Curta Duração (UFCD) 5412, focada na **Programação Estruturada** utilizando a linguagem **C**.

## Descrição da UFCD

A linguagem C, criada por Dennis Ritchie no início dos anos 70, é uma linguagem de programação de alto nível com características de baixo nível, o que a torna **extremamente poderosa e eficiente**. É a base de muitos sistemas operativos, como UNIX e Linux, e influenciou diretamente o desenvolvimento de outras linguagens populares como C++, Java e C#.

Aprender C solidifica a compreensão sobre **como as linguagens de programação e os computadores funcionam**, oferecendo um controlo direto de hardware, alta performance e portabilidade de código para diversas plataformas. Esta UFCD visa fornecer os fundamentos essenciais para desenvolver programas estruturados, eficientes e robustos em C.

## Tópicos Abordados

Durante esta UFCD, exploramos os seguintes conceitos fundamentais da programação em C:

*   **Conceitos Básicos**:
    *   Estrutura de um programa C (`main()`, `#include <stdio.h>`).
    *   Variáveis e Tipos de Dados (int, char, float, `_Bool`).
    *   Operadores (aritméticos `+`, `-`, `*`, `/`, `%`; relacionais `==`, `!=`, `>`, `<`, `>=`, `<=`; lógicos `&&`, `||`, `!`; atribuição `=`; incremento/decremento `++`, `--`).
    *   Entrada e Saída de Dados (`printf()`, `scanf()`, `getchar()`, `putchar()`).
    *   Diretivas de Pré-processador (`#include`, `#define`).
    *   Comentários (`/* ... */`).

*   **Estruturas de Controle de Fluxo**:
    *   Condicionais (`if`, `else if`, `else`, `switch`).
    *   Laços de Repetição (`for`, `while`, `do-while`).
    *   Comandos de Salto (`break`, `continue`).

*   **Funções**:
    *   Definição e Declaração (Protótipos).
    *   Passagem de Parâmetros por Valor e por Referência.
    *   Variáveis Locais e Globais.
    *   Retorno de Valores (`return`).
    *   Funções com Matrizes e Strings.
    *   Argumentos de Linha de Comando (`argc`, `argv`).

*   **Estruturas de Dados**:
    *   **Matrizes (Arrays)**: Unidimensionais e Multidimensionais.
    *   **Strings**: Arrays de caracteres terminados em `\0`, funções da biblioteca `string.h` (`strlen`, `strcpy`, `strcat`, `strcmp`), arrays de strings.
    *   **Ponteiros**: Declaração (`*`), operador de endereço (`&`), desreferência (`*`), aritmética de ponteiros, ponteiros e arrays, ponteiros e estruturas, ponteiros para ponteiros, operador de acesso a membros de estrutura (`->`).
    *   **Estruturas (Structs)**: Definição, declaração, inicialização, acesso a membros (`.`, `->`), arrays de estruturas, estruturas aninhadas.

*   **Alocação Dinâmica de Memória**:
    *   Funções `malloc()`, `calloc()`, `realloc()`, `free()` para gestão de memória em tempo de execução.
    *   Necessidade de libertar memória para evitar "memory leaks".

*   **Manipulação de Ficheiros (File I/O)**:
    *   Streams, `FILE *`, `fopen()`, `fclose()`.
    *   Leitura/Escrita de caracteres (`fgetc()`, `fputc()`), linhas (`fgets()`, `fputs()`), e formatada (`fscanf()`, `fprintf()`).
    *   Arquivos de texto vs. binários.

## Objetivos de Aprendizagem

Ao concluir esta UFCD, o participante deverá ser capaz de:
*   Compreender e aplicar os fundamentos da linguagem C para resolver problemas computacionais.
*   Desenvolver programas modulares e bem estruturados utilizando funções.
*   Manipular diferentes tipos de dados, incluindo arrays, strings e estruturas personalizadas.
*   Gerir a memória de forma eficiente através do uso de ponteiros e alocação dinâmica.
*   Realizar operações de entrada/saída de dados via consola e ficheiros.
*   Implementar algoritmos e resolver desafios de programação de forma estruturada.

## Pré-requisitos

*   Conhecimentos básicos de lógica de programação e algoritmos.
*   Familiaridade com o uso de um ambiente de linha de comando.

## Ambiente de Desenvolvimento

Para compilar e executar os programas em C, é necessário ter um ambiente de desenvolvimento configurado:

1.  **Editor de Texto**: Utilize um editor como VS Code, Sublime Text, Atom, Notepad, vim ou vi.
2.  **Compilador C**: Instale um compilador compatível com C, como GCC (GNU Compiler Collection). No Windows, pode usar MinGW ou Cygwin. No macOS, o Xcode Command Line Tools inclui o Clang.
3.  **Compilação**:
    *   Salve o seu código com a extensão `.c` (ex: `meu_programa.c`).
    *   Abra o terminal/prompt de comando.
    *   Para compilar: `gcc meu_programa.c -o meu_programa`.
4.  **Execução**:
    *   No Linux/macOS: `./meu_programa`.
    *   No Windows: `meu_programa.exe`.

## Estrutura do Repositório (Exemplo)

```
.
├── README.md
├── .gitignore
├── fundamentos/
│   ├── ola_mundo.c
│   ├── variaveis_operadores.c
│   └── entrada_saida.c
├── estruturas_controle/
│   ├── if_else.c
│   ├── switch_case.c
│   ├── laco_for.c
│   ├── laco_while.c
│   └── laco_do_while.c
├── funcoes/
│   ├── definicao_prototipo.c
│   ├── passagem_valor_referencia.c
│   └── funcoes_globais_locais.c
├── arrays_strings/
│   ├── array_unidimensional.c
│   ├── matrizes_multidimensionais.c
│   ├── manipulacao_strings.c
│   └── array_de_strings.c
├── ponteiros/
│   ├── ponteiros_basicos.c
│   ├── aritmetica_ponteiros.c
│   ├── ponteiros_e_arrays.c
│   └── ponteiros_e_structs.c
├── structs/
│   ├── definicao_struct.c
│   ├── arrays_de_structs.c
│   └── structs_aninhadas.c
├── alocacao_dinamica/
│   ├── malloc_free_exemplo.c
│   └── realloc_exemplo.c
├── fich_io/
│   ├── ler_escrever_texto.c
│   └── ler_escrever_binario.c
├── projetos_praticos/
│   └── jogo_do_galo/  (Exemplo:)
│       ├── main.c
│       └── ...
└── docs/
    └── materiais_ufcd.pdf (se aplicável)
```

## Como Usar este Repositório

1.  **Clonar o Repositório**:
    ```bash
    git clone https://github.com/SeuUtilizador/UFCD5412_ProgramacaoEstruturada.git
    cd UFCD5412_ProgramacaoEstruturada
    ```
2.  **Navegar pelos Tópicos**: Explore os diretórios para encontrar exemplos e exercícios relacionados a cada tema.
3.  **Compilar e Executar**: Siga as instruções no ficheiro `.c` individual ou compile e execute a partir do terminal.

## Contribuições e Feedback

Contribuições, sugestões e feedback são bem-vindos! Se encontrar algum erro, tiver uma melhoria ou quiser adicionar um exemplo, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Autor

**Álvaro Faria**

---
*(Baseado nos materiais da UFCD 5412 - PROGRAMACAO DE COMPUTADOR - ESTRUTURADA.)*

---
