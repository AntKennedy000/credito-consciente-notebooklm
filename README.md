# Crédito consciente — Juros, CET e endividamento

Miniguia de educação financeira desenvolvido com apoio do **NotebookLM**, curadoria de fontes do Banco Central do Brasil e revisão crítica das respostas geradas por inteligência artificial.

Projeto do bootcamp **Bradesco – GenAI, Dados & Cyber**, da DIO, para o desafio **“Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM”**.

> Material educativo. Não constitui recomendação individual de crédito, investimento ou orientação jurídica. Os exemplos históricos das fontes não representam ofertas ou taxas atuais.

## 1. Contexto e objetivos

O tema escolhido foi o uso consciente do crédito, com foco na compreensão dos juros, do Custo Efetivo Total (CET) e dos riscos do endividamento excessivo.

A proposta foi utilizar a IA como ferramenta de aprendizagem ativa: formular perguntas, consultar evidências, identificar respostas imprecisas e revisar o conteúdo antes de consolidá-lo.

Objetivos de estudo:

- Compreender como o crédito afeta o orçamento futuro.
- Diferenciar juros, CET, valor financiado e saldo devedor.
- Identificar critérios para comparar propostas de crédito.
- Estudar cuidados para prevenir o endividamento excessivo.
- Desenvolver prompts que exijam fontes, referências e reconhecimento de limitações.

## 2. Ferramentas utilizadas

- **NotebookLM:** consulta às fontes e geração das versões do miniguia.
- **ChatGPT:** apoio à elaboração dos prompts e à revisão crítica.
- **GitHub e Markdown:** organização e apresentação do projeto.
- **Conferência das fontes e dos cálculos:** validação complementar às respostas da IA.

O projeto não envolveu treinamento ou ajuste de um modelo de IA. O NotebookLM foi utilizado para consultar e sintetizar documentos selecionados.

## 3. Curadoria de fontes

Foram importadas e selecionadas três fontes abertas do Banco Central do Brasil.

| Fonte | Contribuição para o estudo |
|---|---|
| [Caderno de Educação Financeira — Gestão de Finanças Pessoais](https://www.bcb.gov.br/pre/pef/port/caderno_cidadania_financeira.pdf) | Conceitos de orçamento, juros, crédito e exemplos numéricos. Destaque para os módulos 2 e 3. |
| [FAQs — Empréstimos e financiamentos](https://www.bcb.gov.br/meubc/faqs/s/emprestimos-e-financiamentos) | Informações sobre operações de crédito, documentação e comparação de custos. |
| [É possível sair do superendividamento](https://www.bcb.gov.br/pre/pef/port/folder_serie_II_%C3%A9_possivel_sair_do_superendividamento.pdf) | Orientações educativas sobre prevenção e enfrentamento do endividamento excessivo. |

### Critérios de seleção e limites

As fontes foram escolhidas pela autoria institucional, pelo acesso público e pela relação direta com o tema.

O Caderno é uma publicação de **2013**. As FAQs apresentam datas de atualização próprias, que não devem ser confundidas com a edição dos materiais educativos.

As três fontes pertencem à mesma instituição: isso favorece a consistência institucional, mas não representa diversidade de perspectivas.

## 4. Processo de desenvolvimento

1. Criação do notebook **“Crédito consciente — Juros, CET e endividamento”**.
2. Importação e seleção das três fontes.
3. Execução de um prompt inicial amplo.
4. Refinamento das instruções para exigir evidências e evitar generalizações.
5. Auditoria das respostas e abertura de citações no NotebookLM.
6. Geração da primeira versão do miniguia.
7. Geração da V2 e comparação com os ajustes solicitados.
8. Consolidação editorial do conteúdo neste README.

## 5. Engenharia de prompts e resultados

### Teste 1 — Pergunta ampla

**Prompt utilizado:**

> Explique o que é crédito consciente, qual é a diferença entre juros e Custo Efetivo Total (CET) e quais cuidados ajudam a evitar o endividamento excessivo.

**Resultado observado:** resposta organizada, mas com afirmações excessivamente abrangentes. Um trecho sugeria que o uso consciente poderia garantir que o crédito não comprometesse o consumo futuro.

**Aprendizado:** uma resposta clara e bem estruturada ainda precisa de verificação conceitual.

### Teste 2 — Refinamento

O segundo prompt delimitou o público iniciante, restringiu a resposta às três fontes e solicitou citações, estrutura definida e revisão de afirmações absolutas.

**Resultado observado:** houve correção sobre o comprometimento do orçamento futuro. Entretanto, a resposta afirmou que os materiais não apresentavam simulações numéricas para analisar o total pago.

**Aprendizado:** pedir que a IA declare limitações não impede que ela descreva incorretamente o conteúdo disponível.

### Teste 3 — Auditoria direcionada

O terceiro prompt solicitou a verificação das páginas impressas 27–29 do Caderno e a revisão de três pontos:

- Existência de simulações numéricas.
- Diferença entre valor contratado e saldo devedor.
- Possibilidade, e não certeza, de uma proposta com juros menores apresentar CET maior.

**Resultado observado:** o NotebookLM reconheceu erros e apresentou referências. As citações abertas mostraram trechos do exemplo do veículo e da explicação do CET.

**Aprendizado:** indicar uma seção relevante e exigir comparação entre afirmação e evidência tornou a revisão mais verificável.

### Testes 4 e 5 — Miniguia e revisão

Foram solicitados objetivos, resumos, glossário, perguntas de revisão, prompts reutilizáveis e limitações.

A V2 incorporou melhorias, mas a leitura do arquivo revelou problemas remanescentes: números internos de referência, uma comparação invertida no gabarito e generalizações que o resumo da ferramenta dizia ter eliminado.

**Aprendizado:** é necessário revisar o arquivo entregue, não apenas a mensagem que anuncia sua conclusão.

## 6. “Cicatrizes” e revisão crítica

| Problema observado | Tratamento adotado |
|---|---|
| Negação da existência de exemplos numéricos | Consulta direcionada à seção 3.4 do Caderno. |
| Confusão entre valor contratado e saldo devedor | Separação dos conceitos na redação final. |
| Afirmações absolutas sobre CET e crédito pré-aprovado | Inclusão de condições e retirada de generalizações. |
| Referências internas sem links no Markdown | Substituição por fontes identificáveis e links públicos neste README. |
| Todas as fontes descritas como sendo de 2013 | Distinção entre a edição do Caderno e as atualizações das FAQs. |
| Divergência entre a mensagem de revisão e o arquivo V2 | Conferência do conteúdo efetivamente exportado. |

### Conferência numérica

No exemplo do veículo, o Caderno informa entrada de R$ 16.000,00, 60 parcelas de R$ 657,41 e gasto de R$ 55.444,43.

O cálculo com os valores exibidos resulta em:

**R$ 16.000,00 + 60 × R$ 657,41 = R$ 55.444,60.**

Foi registrada uma diferença de **R$ 0,17**, sem atribuir uma causa não demonstrada. O valor informado pela fonte e o cálculo derivado foram mantidos distintos. Referência: [Caderno, seção 3.4, páginas 28–29](https://www.bcb.gov.br/pre/pef/port/caderno_cidadania_financeira.pdf).

## 7. Miniguia de estudo

### 7.1 Crédito e orçamento

O crédito permite antecipar o uso de recursos de terceiros, mas gera compromissos futuros. Planejar sua utilização envolve avaliar necessidade, custos e capacidade de pagamento.

O endividamento excessivo não decorre apenas de hábitos de consumo: imprevistos, como perda de renda e problemas de saúde, também podem contribuir. Referências: Caderno, seção 3.4, e folder sobre superendividamento, disponíveis na curadoria.

### 7.2 Juros e CET

**Juros** representam o custo do uso do capital ao longo do tempo. No regime composto, os juros são incorporados ao capital a cada período de capitalização.

**CET** consolida os encargos e despesas da operação. Uma proposta com juros menores pode apresentar CET maior, dependendo dos demais custos. Referências: [Caderno, seções 3.3–3.4](https://www.bcb.gov.br/pre/pef/port/caderno_cidadania_financeira.pdf) e [FAQs, cuidados na contratação](https://www.bcb.gov.br/meubc/faqs/s/emprestimos-e-financiamentos).

### 7.3 Checklist para comparar propostas

Síntese de estudo baseada nas fontes:

- Verificar o valor contratado e o valor efetivamente disponibilizado.
- Comparar prazos e condições equivalentes.
- Conferir o valor e a quantidade das parcelas.
- Comparar o CET na mesma base temporal.
- Considerar o desembolso total, incluindo entrada quando houver.
- Avaliar o impacto no orçamento e nas despesas essenciais.

Não escolher uma operação somente pela parcela menor ou pela aprovação prévia.

### 7.4 Prevenção do endividamento excessivo

- Registrar receitas e despesas.
- Planejar gastos sazonais.
- Formar uma reserva para imprevistos, conforme as possibilidades.
- Não tratar limites de crédito como renda.
- Avaliar os custos antes de contratar.

Referência: [É possível sair do superendividamento](https://www.bcb.gov.br/pre/pef/port/folder_serie_II_%C3%A9_possivel_sair_do_superendividamento.pdf).

### 7.5 Glossário

Definições didáticas sintetizadas a partir das fontes; não constituem um glossário jurídico.

| Conceito | Significado |
|---|---|
| Crédito | Recursos de terceiros disponibilizados com compromisso de pagamento. |
| Juros simples | Juros calculados sobre o capital inicial. |
| Juros compostos | Juros incorporados ao capital por período de capitalização. |
| CET | Indicador consolidado dos encargos e despesas da operação. |
| Valor financiado | Montante original financiado na operação. |
| Valor líquido recebido | Quantia disponibilizada após eventuais deduções iniciais. |
| Saldo devedor | Valor da dívida em determinado momento. |
| Orçamento | Planejamento e acompanhamento de receitas e despesas. |
| Despesas sazonais | Gastos concentrados em determinadas épocas. |
| Troca intertemporal | Escolha entre utilizar recursos no presente ou no futuro. |

### 7.6 Perguntas de revisão

**1. Juros menores garantem uma proposta mais barata?**  
Não. Os demais encargos podem resultar em CET maior.

**2. Valor financiado e saldo devedor são sinônimos?**  
Não. Um se refere ao financiamento original; o outro, à dívida em determinado momento.

**3. Limite de crédito deve ser somado ao salário?**  
Não. Crédito não é renda própria.

**4. Por que conferir as citações?**  
Porque a existência de uma referência não garante que ela sustente toda a afirmação.

**5. Exemplos antigos representam taxas atuais?**  
Não. Devem ser utilizados como ilustrações educativas, respeitando seu contexto histórico.

## 8. Prompts reutilizáveis

Estes prompts são propostas para revisões futuras; não representam testes adicionais já executados.

1. **Conceitos:** “Usando somente as fontes selecionadas, explique juros e CET para iniciantes. Cite os trechos que sustentam a explicação e declare eventuais limitações.”

2. **Comparação:** “Elabore um checklist para comparar propostas de crédito considerando valor, prazo, parcelas, CET e desembolso total. Diferencie orientação explícita das fontes de síntese didática.”

3. **Orçamento:** “Explique como compromissos de crédito afetam o orçamento futuro. Use referências das fontes e não invente percentuais universais de comprometimento de renda.”

4. **Auditoria:** “Revise a resposta anterior em busca de generalizações e afirmações sem apoio. Apresente afirmação, evidência, limitação e redação corrigida.”

5. **Revisão ativa:** “Faça cinco perguntas sobre crédito consciente, uma por vez. Aguarde minha resposta, forneça feedback com citações e indique o trecho que devo revisar.”

## 9. Limitações e conclusão

As respostas geradas por IA foram tratadas como material preliminar, sujeito a conferência.

As exportações continham referências numéricas que não funcionavam como links independentes. Por isso, esta documentação apresenta fontes públicas identificáveis e registra os testes sem afirmar que todas as citações foram verificadas individualmente.

O principal aprendizado foi combinar **curadoria, formulação de perguntas, leitura das evidências e revisão editorial**. Refinar um prompt melhora o processo, mas não elimina a necessidade de checar o resultado.

## Autor

**Antony Kennedy Ribeiro de Araújo**

Projeto desenvolvido no bootcamp **Bradesco – GenAI, Dados & Cyber**, da **DIO**.
