# 🏍️ Controle Financeiro para Motoboys — Estudo de Caso em Excel

## 📄 Resumo do Projeto
Este projeto apresenta o levantamento de requisitos e o desenvolvimento de uma ferramenta prática em **Microsoft Excel** voltada para entregadores autônomos (motoboys) que trabalham com plataformas de entrega. 

O objetivo principal foi solucionar a dificuldade que esses profissionais enfrentam para separar o **valor bruto recebido** do **saldo líquido real** (o que realmente sobra no bolso após descontar combustível, alimentação na rua e manutenção da motocicleta).

---

## 🔍 Contexto e Levantamento de Requisitos
A rotina de entregas envolve ganhos variáveis todos os dias e custos imediatos durante o turno de trabalho. A partir de uma reunião com três entregadores (meus irmãos), realizei uma etapa de escuta e diagnóstico para entender como eles organizavam suas finanças.

**Problemas identificados na entrevista:**
1. Olhar apenas para o valor repassado pelo aplicativo criava uma falsa percepção de ganho.
2. Pequenos gastos diários na rua (água, refeições, abastecimentos) não eram anotados de forma estruturada.
3. Despesas de manutenção (troca de óleo, pneu, relação) impactavam o orçamento sem um acompanhamento claro por período.

---

## ⚙️ Estrutura da Solução Entregue
Em vez de um sistema complexo que não se adaptasse à correria dos entregadores, desenvolvi uma planilha direta e automatizada no Excel, dividida em **3 abas**:

1. **`Lançamentos Diários`:**
   - Painel superior com 5 cartões de resumo rápido (Total de Entradas, Gastos na Rua, Manutenção, Total de Despesas e Saldo Líquido).
   - Tabela simplificada onde o usuário preenche apenas os dados do dia e as fórmulas calculam automaticamente o total gasto e o saldo líquido diário.
2. **`Visão Semanal e Mensal`:**
   - Consolidação automática por período (`Semana 1` a `Semana 5` e total do mês) utilizando funções condicionais (`SOMASE`).
   - Indicadores operacionais automáticos: **Margem líquida (%)**, **Ganho líquido médio por entrega** e **Custo por KM rodado**.
   - Gráfico comparativo entre Entradas, Despesas e Saldo Líquido por semana.
3. **`Sobre o Projeto (Case)`:**
   - Documentação técnica do projeto e nota de privacidade.

---

## 📊 Mapeamento: Necessidade vs. Solução

| Necessidade Identificada | Resposta da Solução |
| :--- | :--- |
| Acompanhar os valores recebidos | Registro diário de entradas e quantidade de entregas |
| Identificar os custos do trabalho | Separação clara entre gastos na rua (combustível/alimentação) e manutenção |
| Visualizar quanto realmente sobra | Cálculo automatizado do saldo líquido diário, semanal e mensal |
| Comparar períodos | Aba de acompanhamento consolidado por semanas com gráfico visual |

---

## 🛠️ Habilidades e Ferramentas Utilizadas
- **Levantamento de Requisitos:** Entrevista com usuários, identificação de dores reais e definição de escopo.
- **Microsoft Excel:** Fórmulas automáticas (`SOMA`, `SOMASE`, `SE`, `CONT.VALORES`), validação de dados (listas suspensas), formatação condicional e criação de gráficos.
- **Organização de Dados e Negócios:** Categorização de receitas/despesas e criação de indicadores de desempenho (KPIs).

---

## 📌 Limites e Privacidade dos Dados
- **Status:** Solução entregue aos usuários e projeto acadêmico aprovado (2026).
- **Limites do Estudo:** A entrega focou na disponibilização da ferramenta funcional para organização financeira. Não houve medição formal posterior sobre aumento de renda ou frequência de uso contínua.
- **Privacidade:** Os dados reais dos participantes foram preservados. O arquivo `.xlsx` disponível neste repositório está preenchido com **dados fictícios** exclusivamente para demonstração do funcionamento das fórmulas e gráficos.
