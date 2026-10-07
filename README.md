# Relatório Semanal de Caixa Automatizado

> 🔒 Código privado (projeto corporativo). Esta página descreve o escopo.

## Problema
Toda semana, a diretoria precisa de uma visão clara do caixa: quanto entrou, quanto saiu e para onde foi, em várias contas e bancos.

## Solução
Skill para o **Claude** que monta o relatório a partir dos extratos **OFX**:
- Consolida todas as contas e mostra as **transferências entre bancos**, para cada saldo fechar
- Agrupa por categoria gerencial (recebimentos, custos, despesas fixas e variáveis, impostos, financeiro)
- **Dicionário de fornecedores que aprende**: fornecedor já classificado é reconhecido sozinho, e fornecedor novo gera uma pergunta
- Entrega em **HTML com gráficos**, pensado para leitura no celular

## Próximos passos
Fechamento mensal com comparativo e acumulado do ano, e um time de agentes (contas a pagar, contas a receber e revisor).

## Tecnologias
Claude (skills) · Python · OFX · HTML/CSS · Excel
