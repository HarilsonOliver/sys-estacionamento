
---

# Sistema de Estacionamento - Desafio do módulo de fundamentos, da trilha .NET da DIO.

Este é um projeto de console em C# que simula o funcionamento básico de um sistema de estacionamento. O sistema permite que o usuário adicione, remova e liste veículos estacionados, além de calcular o valor a ser pago com base no tempo de permanência.

## Funcionalidades

- **Adicionar Veículo**: Permite que o usuário registre a placa de um veículo ao estacionamento.
- **Remover Veículo**: Permite que o usuário remova um veículo, informando a quantidade de horas que ele permaneceu estacionado. O sistema calcula e exibe o valor a ser pago.
- **Listar Veículos**: Exibe a lista de todos os veículos atualmente estacionados.

## Pré-requisitos

- [.NET 6 SDK](https://dotnet.microsoft.com/download) ou superior

## Estrutura do Projeto

O projeto possui a seguinte estrutura:

- **Estacionamento.cs**: Classe principal com os métodos para gerenciar os veículos estacionados, incluindo `AdicionarVeiculo`, `RemoverVeiculo` e `ListarVeiculos`.
- **Program.cs**: Ponto de entrada do programa, onde são exibidos os menus e opções para o usuário interagir com o sistema.

## Como Executar

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd nome-do-repositorio
   ```

3. Compile e execute o programa:
   ```bash
   dotnet run
   ```
