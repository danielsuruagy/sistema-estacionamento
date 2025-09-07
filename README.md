# Sistema de Estacionamento - Console App

Um sistema simples de gerenciamento de estacionamento desenvolvido em C#. Permite cadastrar, remover e listar veículos, calculando o valor a ser cobrado de acordo com o tempo estacionado.

## Funcionalidades

- **Cadastrar veículo:** Adiciona a placa de um veículo ao estacionamento.  
  - Valida se a placa já está cadastrada.  
  - Verifica se a placa está no padrão Mercosul (`ABC1D23`).  

- **Remover veículo:** Remove um veículo do estacionamento e calcula o valor total a ser pago com base no tempo de permanência.  
  - Fórmula: `Preço Inicial + (Preço por Hora × Horas Estacionadas)`  

- **Listar veículos:** Exibe todas as placas cadastradas no estacionamento.  

- **Encerrar:** Finaliza o programa.  

## Como Usar

1. Abra o projeto em um IDE compatível com C# (Visual Studio, Rider, VS Code).  
2. Execute o programa.  
3. No menu, escolha uma das opções:  
   - `1` para cadastrar veículo.  
   - `2` para remover veículo e calcular o valor.  
   - `3` para listar veículos estacionados.  
   - `4` para encerrar o programa.  

4. Siga as instruções do console.  

## Regras de Validação

- Placas devem estar no formato Mercosul: `ABC1D23`.  
- Não é permitido cadastrar a mesma placa duas vezes.  
- Ao remover um veículo, o tempo de estacionamento deve ser um número positivo.  
