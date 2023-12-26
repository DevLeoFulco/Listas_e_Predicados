

## Introdução

Este repositório contém um programa Java que demonstra o uso de listas, predicados e métodos de manipulação de listas em Java. O programa foi desenvolvido como parte do estudo da linguagem Java, com foco em práticas de programação orientada a objetos e manipulação de coleções.

## Funcionalidades Principais

### 1. Leitura de Dados de Funcionários

O programa permite que o usuário insira informações sobre vários funcionários, incluindo ID, nome e salário. Para garantir que cada ID seja único, o programa verifica se o ID fornecido já está em uso antes de permitir a inserção.

### 2. Atualização de Salário de Funcionário

O usuário pode selecionar um funcionário pelo ID e atualizar o salário dele com um aumento percentual fornecido pelo usuário.

### 3. Listagem de Funcionários

Após inserir todos os dados e realizar as atualizações necessárias, o programa exibe uma lista de todos os funcionários registrados, incluindo seus IDs, nomes e salários atualizados.

## Estrutura do Código

### Classe Employee

A classe `Employee` representa um funcionário e possui os seguintes atributos:

- `id`: Identificador único do funcionário.
- `name`: Nome do funcionário.
- `salary`: Salário do funcionário.

Métodos incluem:

- `increaseSalary(double percentage)`: Atualiza o salário do funcionário com base em um aumento percentual fornecido.

### Função `hasId`

A função `hasId` verifica se um determinado ID já está em uso na lista de funcionários. Ela é útil para garantir IDs únicos durante a inserção de dados.

### Principais Conceitos e Técnicas Utilizadas

- **Listas (`List`)**: Utilizadas para armazenar e gerenciar uma coleção dinâmica de objetos `Employee`.
  
- **Predicados**: Utilizados em conjunto com streams para filtrar objetos com base em certas condições, como verificar a existência de um ID específico.

- **Métodos de Manipulação de Listas**: Foram aplicados métodos como `add`, `filter`, `findFirst` e `orElse` para inserir, filtrar e recuperar objetos da lista.

## Como Executar o Programa

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter o JDK (Java Development Kit) instalado.
3. Navegue até o diretório do projeto e compile o código-fonte.
4. Execute o programa e siga as instruções no terminal para interagir com o programa.

## Conclusão

Este projeto serve como um exemplo prático da aplicação de conceitos fundamentais de programação em Java, incluindo manipulação de listas, predicados e programação orientada a objetos. Ele pode ser usado como um ponto de partida para projetos mais complexos ou para estudos adicionais em Java.
