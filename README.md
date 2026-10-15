# 🎯 Desafio Criativo - Automação N8N 

## Objetivo
O prompt que criei tem o objetivo de ajudar a criar um fluxo no N8N para registrar as compras feitas no cartão de crédito em uma planilha do Google Sheets. Dessa forma, é possível criar um dashboard com essas informações futuramente.

## 🔃 Prompt para criação do fluxo de Controle Financeiro no N8N
```md
Atue como um especialista em N8N.

Crie uma automação para organizar o controle financeiro pessoal, registrando automaticamente todas as transações do cartão de crédito em uma planilha.

**Público:**  
Usuário individual que deseja acompanhar seus gastos.

**Ferramentas envolvidas:**  
API do banco/cartão de crédito e Google Sheets.
 

**Fluxo:**  
1. Detectar nova transação no cartão  
2. Extrair os dados principais da compra  
3. Registrar cada transação em uma linha da planilha  
4. Atualizar saldo acumulado 

**Regras:**  
- A planilha deve conter: data da compra, nome do cartão, tipo de pagamento (crédito ou débito),categoria, descrição, valor e número de parcelas (se houver).
- Transações de estorno devem ser registradas no mesmo formato, com valor negativo.
- Ignorar transações duplicadas.
- Validar que o valor esteja em formato numérico antes de salvar.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
```
