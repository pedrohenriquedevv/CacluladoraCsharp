# 🧮 Calculadora Simples em C#

Um aplicativo de console robusto desenvolvido em **C#** que realiza operações matemáticas básicas, focado em experiência do usuário e tratamento de exceções.

## 🚀 Funcionalidades

O projeto vai além de uma calculadora comum, incluindo validações essenciais para um sistema de informação:

* **Operações Básicas:** Soma, Subtração, Multiplicação e Divisão.
* **Validação de Dados:** O sistema utiliza `double.TryParse` para garantir que o usuário insira apenas números válidos, evitando que o programa quebre.
* **Tratamento de Erros Matemáticos:** Verificação automática para impedir a divisão por zero.
* **Interface Interativa:** Uso de `Thread.Sleep` para dar um tempo de resposta mais natural ao usuário e loops que permitem realizar várias operações sem fechar o programa.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** C#
* **Plataforma:** .NET Console Application
* **Namespaces:** `System`, `System.Globalization`, `System.Threading`

## 📖 Como Funciona o Código

1. **Entrada de Dados:** O programa solicita dois valores numéricos. Se o usuário digitar letras, o sistema exibe um alerta e solicita o número novamente.
2. **Escolha da Operação:** O usuário seleciona o operador (`+`, `-`, `/`, `*`).
3. **Processamento:** Utiliza uma estrutura `switch` para decidir qual cálculo realizar.
4. **Continuidade:** Ao final de cada cálculo, o programa pergunta se você deseja continuar ou encerrar a execução.

## 💻 Exemplo de Uso

```text
Insira o seu primeiro valor: 10
Insira o seu segundo valor: 5
Escolha o tipo de operação( + - / * ): *
O resultado da sua multiplicação é 50

Quer realizar outra operação? (s/n)
