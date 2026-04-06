# Exercício 1 - C# Primeiros Passos: Lógica de Programação e Algoritmos

Este repositório contém a solução para o primeiro exercício do curso de **C# Primeiros Passos: Lógica de Programação e Algoritmos** da Udemy. O objetivo deste projeto foi colocar em prática conceitos fundamentais de desenvolvimento de software, como entrada e saída de dados no console e processamento aritmético.

## 📝 Descrição do Problema

O programa é projetado para ler as medidas de um terreno retangular e o valor do metro quadrado. Com esses dados, o algoritmo realiza os seguintes cálculos e exibe o resultado formatado com duas casas decimais:

1.  A **Área total** do terreno.
2.  O **Preço total** de venda do terreno.

### 📊 Exemplo de Entrada e Saída

O comportamento esperado do programa é ilustrado na tabela abaixo:

| Entrada (Input) | Saída (Output) |
| :--- | :--- |
| `10.0` (Largura) | `AREA = 300.00` |
| `30.0` (Comprimento) | `PREÇO = 60000.00` |
| `200.00` (Valor por m²) | |

## 🛠️ Detalhes Técnicos e Tecnologias

Este projeto foi desenvolvido utilizando as versões mais recentes das ferramentas, garantindo compatibilidade e performance:

* **Linguagem:** C#
* **Framework:** .NET 10.0
* **IDE:** Microsoft Visual Studio 2026 Community (Versão 18.4.1)
* **Versionamento:** Git e GitHub

### 🪐 Diferencial Técnico: Formatação Internacional com `CultureInfo`

Um ponto crucial implementado neste código foi o uso da biblioteca `System.Globalization` através do `CultureInfo.InvariantCulture`.

Esta implementação garante que o programa trate números decimais usando o ponto (`.`) como separador, independentemente das configurações regionais do computador do usuário. Isso previne erros comuns de execução (exceções de formato) em sistemas configurados em Português ou outras regiões que utilizam a vírgula.

---

Este projeto foi desenvolvido por Marco Guidorizzi como parte da jornada de aprendizado em desenvolvimento de software com tecnologias Microsoft.
