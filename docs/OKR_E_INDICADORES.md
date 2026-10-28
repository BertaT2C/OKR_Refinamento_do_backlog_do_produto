# Modelo de OKR e indicadores — Qualidade do Refinamento do Backlog

> **Estudo de caso fictício.** Este documento traduz o problema original em um modelo de gestão por resultados. Não é um relatório de implantação ou de indicadores aferidos em uma organização real.

## 1. Desafio que orienta o OKR

- Uma estrutura descrita no case com **30 colaboradores participando das cerimônias**, mesmo quando parte das pessoas não estava diretamente envolvida na entrega.
- Backlogs inicialmente separados entre **negócios** e **desenvolvimento**, criando risco de perda de contexto e dificuldade de visão única.
- Explicações recorrentes durante os refinamentos e conversas paralelas para esclarecer regras e funcionalidades.
- Necessidade de documentar cenários, regras, fluxos *TO BE*, viabilidade técnica e integrações de modo compreensível para desenvolvimento e QA.

A proposta do estudo é reduzir retrabalho de comunicação e aumentar a prontidão das histórias antes do planejamento.

## 2. OKR proposto

### Objetivo (O)

**Tornar o refinamento do Product Backlog mais claro, colaborativo e eficiente, aumentando o alinhamento entre negócio, desenvolvimento e qualidade.**

Esse objetivo descreve o **resultado desejado**, não a atividade de realizar reuniões ou publicar documentos.

### Resultados-chave (KRs)

| Resultado-chave | Definição e interpretação | Linha de base | Meta | Evidência |
| --- | --- | --- | --- | --- |
| **KR1 — Reduzir o tempo de esclarecimentos e reapresentações** | Dias consumidos com apresentações e dúvidas durante um ciclo de referência do estudo | **7 dias** | **3 dias** | Registro de tempo por ciclo e atas de refinamento |
| **KR2 — Aumentar a cobertura dos cenários detalhados** | Proporção de cenários identificados com regras e critérios de aceite documentados | **A levantar** | **A definir com o time** | Inventário de cenários e histórias |
| **KR3 — Reduzir histórias que retornam ao refinamento por falta de clareza** | Proporção de itens reapresentados exclusivamente por informação ausente ou ambígua | **A levantar** | **A definir com o time** | Histórico de impedimentos / devoluções |
| **KR4 — Reduzir o tempo de preparação dos testes de usuário/QA** | Tempo entre receber a história refinada e conseguir planejar os cenários e dados de testes | **A levantar** | **A definir com QA** | Registros de preparação dos testes |

**Importante:** somente o KR1 usa os valores **7 e 3 dias** já registrados no README original. Os demais são *propostas de mensuração* e **não** possuem resultados apurados ou metas numéricas na fonte.

### Fórmula do indicador principal

```text
Redução relativa (%) = [(Dias antes − Dias depois) / Dias antes] × 100

Aplicação aos números do estudo:
[(7 − 3) / 7] × 100 = 57,14%
```

**Leitura correta:** redução de aproximadamente **57,14% do tempo dedicado a apresentações e esclarecimento de dúvidas**, tomando o cenário hipotético de 7 para 3 dias como referência. Não representa aumento comprovado de 57,14% da produtividade total, nem comprova ganhos financeiros ou redução de duração da sprint.

O estudo também menciona **sprint de quatro semanas**, mas não apresenta registros reais de quantos ciclos foram analisados, amostra, fonte de dados ou validação estatística.

## 3. Distinguir indicadores de resultados das atividades

| Categoria | Exemplos no estudo | Papel no OKR |
| --- | --- | --- |
| **Resultado** | Menos dias de apresentações e esclarecimentos | KR1 |
| **Resultado** | Mais cenários com especificação suficiente para a equipe | KR2 |
| **Resultado** | Menos retornos ao refinamento por dúvidas | KR3 |
| **Resultado** | Menor tempo para preparar os testes | KR4 |
| **Iniciativa** | Documentar regras, exceções e cenários de usuário | Meio para atingir os KRs |
| **Iniciativa** | Revisar e manter o fluxograma TO BE | Meio para atingir os KRs |
| **Iniciativa** | Onboarding, treinamentos e facilitação | Meio para atingir os KRs |
| **Iniciativa** | Refinamento com participantes relacionados às histórias | Meio para atingir os KRs |

O aprendizado-chave é que **um OKR mede mudanças**, enquanto as iniciativas descrevem como a equipe pretende provocá-las.

## 4. Definições operacionais recomendadas para os indicadores

**Cobertura de cenários (KR2)**

```text
(Cenários detalhados e revisados / Cenários identificados no escopo) × 100
```

Para contar um cenário como detalhado, estabelecer com a equipe um acordo mínimo: fluxo, regras de negócio, critérios de aceitação e dependências relevantes. A definição é uma **proposta de trabalho**, não uma regra registrada na fonte.

**Retorno ao refinamento (KR3)**

```text
(Itens que precisaram de novo refinamento por falta de clareza / Itens refinados) × 100
```

Definir antes da coleta o que caracteriza retrabalho de especificação e separar de mudanças legítimas de prioridade ou escopo.

**Preparação de testes (KR4)**

```text
Tempo entre disponibilização da história pronta para QA e preparação dos cenários/massa de teste
```

Medir no mesmo recorte e nas mesmas unidades entre os ciclos comparados.

## 5. Como acompanhar o OKR

1. **Definir o recorte:** produto, time e ciclo de análise, evitando misturar projetos sem características comparáveis.
2. **Construir a linha de base:** registrar quantos dias foram gastos, quantas histórias retornaram, qual cobertura e qual esforço de preparação dos testes.
3. **Executar as iniciativas:** detalhamento de cenários, alinhamento com interessados, revisão de fluxos e facilitação.
4. **Verificar tendências:** comparar períodos equivalentes, olhando para variação do escopo e complexidade.
5. **Revisar prioridades:** aprimorar o fluxo com base em evidências, não apenas na quantidade de cerimônias realizadas.

## 6. Riscos de interpretação

- **Equipe de 30 pessoas** é um dado do cenário; não assumir que todos fazem parte de um único Scrum Team formal ou que basta dividir pessoas para resolver o problema.
- **A redução de 57,14%** é um cálculo correto sobre os números apresentados, mas a fonte classifica todo o projeto como fictício.
- **Redução de dúvidas** e **melhoria da homologação** são benefícios narrados no estudo, sem série histórica, percentuais próprios ou comprovação de testes reais.
- **Qualidade de mensagens de erro da API** aparece como indicador do caso, mas deve ser avaliada apenas quando houver integração e critérios específicos a validar; o estudo não fornece dados técnicos de implementação.

**Material complementar:** [roteiro de refinamento e práticas de alinhamento](./ROTINA_REFINAMENTO.md) · [README](../README.md) · [documentação original](../DOCUMENTACAO_ORIGINAL.md).
