# Caixa Eletrônico Simulado

## Descrição
Aplicação de console em C# que simula um caixa eletrônico, permitindo gerenciar contas Corrente e Poupança.

## Funcionalidades
- **Seleção de Conta:** Conta Corrente (1) ou Conta Poupança (2).
- **Operações Disponíveis:**
  1. Depósito
  2. Saque
  3. Consulta de Saldo
  4. Extrato
  5. Transferência
  6. Sair

## Estrutura do Código
Loop principal com menu interativo gerido por switch, atualizando saldo e extrato conforme operações.

## Variáveis Principais
- `saldoC`: Saldo da Conta Corrente.
- `saldoP`: Saldo da Conta Poupança.
- `extratoC`: Extrato da Conta Corrente.
- `extratoP`: Extrato da Conta Poupança.

## Instruções para Uso
1. Execute o programa em ambiente C#.
2. Selecione o tipo de conta.
3. Escolha a operação (1 a 6).
4. Siga as instruções do console.
5. Para sair, escolha a opção 6.

## Exemplo de Uso
1. Escolha "1" para Conta Corrente.
2. Escolha "1" para Depósito e insira um valor.
3. Verifique o saldo com a opção "3".
4. Para sair, escolha "6".

## Notas
- Verificações de validade para valores inseridos.
- Saques e transferências limitados ao saldo disponível.
- Teste em ambiente de desenvolvimento recomendado.

## Contribuições
Sugestões de melhorias e novas funcionalidades são bem-vindas!
