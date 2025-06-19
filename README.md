## 🖥️ Mini Interpretador de Expressões

Este projeto é uma implementação simples de um interpretador de linguagem de script em Java. Ele reconhece e executa comandos básicos de atribuição (let) e impressão (print) com expressões matemáticas contendo soma e subtração.

## 📂 Estrutura do Projeto

Main.java – Contém o ponto de entrada da aplicação.

Parser.java – Analisa a entrada e gera os comandos equivalentes (interpretador).

Scanner.java – Faz a análise léxica, convertendo caracteres em tokens.

Token.java – Representa um token com tipo e valor.

TokenType.java – Enumeração dos tipos de tokens possíveis (como LET, PRINT, NUMBER, etc).

## ⚙️ Como funciona

Análise léxica (Scanner): Converte o código-fonte em tokens.

Análise sintática (Parser): Verifica a estrutura gramatical e emite instruções de execução simuladas.

Execução simulada: Os comandos são impressos como simulação de um interpretador/compilador.

## 🛠️ Extensões possíveis
Suporte a multiplicação e divisão.

Adição de estruturas condicionais (if, else).

Execução real (em vez de só imprimir comandos).

Suporte a tipos como float, string, etc.

## 📃 Licença
Este projeto é open-source e pode ser usado livremente para fins educacionais.
