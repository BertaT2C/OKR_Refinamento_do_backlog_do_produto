# Prática de refinamento do Product Backlog — proposta para o estudo de caso

> Material complementar de **Análise de Negócios e Product Ownership** elaborado sobre um caso **fictício**. As etapas e critérios abaixo são uma proposta didática de organização; não representam cerimônias comprovadamente executadas.

## 1. Situação apresentada no estudo original

- Cenário com **30 colaboradores** envolvidos em cerimônias, incluindo participantes não diretamente ligados a algumas entregas.
- Divisão do backlog entre a frente de **negócios** e a frente de **desenvolvimento**.
- O Product Owner encaminhava a necessidade de um novo sistema ou evolução de sistema existente.
- Analista de Projetos e negócio avaliavam a solicitação, elaboravam requisitos funcionais e não funcionais, mapeavam o processo e promoviam brainstorming.
- Stakeholders eram envolvidos para verificar a viabilidade de serviços e integrações.
- Era desenvolvido um fluxo **TO BE** para compartilhar com desenvolvimento.
- Repetidas dúvidas e explicações em reuniões geravam necessidade de novos refinamentos e perda de tempo.

O objetivo da melhoria é **criar entendimento compartilhado sobre o mesmo produto** sem descartar o conhecimento das duas frentes.

## 2. Fluxo de trabalho proposto

| Etapa | Atividade e perguntas essenciais | Artefato esperado |
| --- | --- | --- |
| **1. Identificar o problema** | Qual necessidade o PO apresenta? Quem será beneficiado? O que muda no produto? | Problema e objetivo de negócio |
| **2. Entender o processo atual** | Como ocorre hoje? Há falhas, desperdícios, tarefas manuais ou obstáculos? | Contexto / AS IS, quando aplicável |
| **3. Explorar a solução** | Quais regras, alternativas, stakeholders e restrições existem? | Discovery / levantamento |
| **4. Desenhar o fluxo futuro** | Como o usuário percorre a jornada? Onde estão decisões e exceções? | Processo **TO BE** |
| **5. Detalhar cenários de usuário** | Quais ações, caminhos alternativos, regras e dados de entrada/saída? | Histórias, regras e exemplos |
| **6. Analisar dependências** | Serviços, integrações e condições técnicas têm viabilidade conhecida? | Pendências, riscos e responsáveis |
| **7. Refinar colaborativamente** | Negócio e tecnologia compreenderam escopo e critérios? Há dúvidas que impeçam estimar? | Backlog compartilhado e itens esclarecidos |
| **8. Preparar a validação** | QA e negócio conseguem antecipar cenários e dados necessários? | Critérios de aceite e plano de testes |
| **9. Observar o resultado** | Quantos esclarecimentos se repetem? Qual o tempo consumido? | Indicadores de refinamento e melhorias |

O roteiro é **uma sugestão de organização**, não uma afirmação de que todas essas etapas eram adotadas pela equipe do estudo.

## 3. Acordos para conduzir refinamentos

### Antes da reunião

- Enviar previamente a visão do problema, fluxograma TO BE e histórias candidatas.
- Indicar quais decisões precisam ser tomadas e quais informações ainda não estão disponíveis.
- Convidar pessoas que tenham contribuição específica na análise da história, evitando a participação de 30 pessoas por padrão em toda discussão.
- Manter o **Product Backlog visível e compreensível** para as diferentes frentes. Quando houver visões de trabalho de negócio e tecnologia, alinhar como ambas se conectam às prioridades do produto.

### Durante o refinamento

- Começar pelo **objetivo de negócio e valor** da funcionalidade.
- Apresentar a jornada, os principais cenários e as regras relevantes.
- Tratar impactos de integrações e de APIs em parceria com as pessoas técnicas; não atribuir ao PO a definição de arquitetura.
- Registrar dúvidas, decisões e dependências com responsáveis e próximos passos.
- Verificar o entendimento de desenvolvimento e QA antes de encerrar.

### Depois do refinamento

- Atualizar histórias, fluxos, critérios e pendências.
- Reavaliar prioridade e prontidão dos itens.
- Acompanhar dúvidas recorrentes e itens que precisaram ser reapresentados.
- Compartilhar as decisões com quem será afetado, mesmo que não tenha participado da reunião.

## 4. Exemplo de checklist de prontidão — proposta

Use como **acordo flexível de refinamento**, não como barreira burocrática:

- [ ] Problema, objetivo e valor de negócio identificados.
- [ ] Fluxo e resultado esperado compreendidos.
- [ ] Regras de negócio descritas.
- [ ] Cenários principais e exceções relevantes considerados.
- [ ] Critérios de aceitação compreensíveis e testáveis.
- [ ] Dependências e integrações conhecidas ou explicitamente sinalizadas.
- [ ] Dúvidas críticas registradas com encaminhamento.
- [ ] Entendimento compartilhado com desenvolvimento e QA.
- [ ] Tamanho e capacidade para execução discutidos com a equipe.
- [ ] Item priorizado de acordo com objetivos do produto.

A existência de uma checklist não substitui a conversa entre as pessoas nem garante ausência de mudanças futuras.

## 5. Iniciativas originais de capacitação e suporte

O estudo destaca três frentes, aqui preservadas:

| Frente | Finalidade no caso | Como se conecta ao objetivo |
| --- | --- | --- |
| **Onboarding** | Introduzir novos integrantes à cultura de resultados e base de conhecimento | Reduzir lacunas de contexto |
| **Treinamentos** | Reforçar conceitos e atualizar o uso de práticas e ferramentas; o texto menciona **pelo menos duas vezes ao ano** | Promover linguagem comum |
| **Facilitações** | Apoio prático, sob demanda, durante ciclos de planejamento | Melhorar alinhamento e decisões |

Essas frentes são **iniciativas** que podem apoiar um OKR, mas não constituem por si só resultados-chave.

## 6. Métricas e contramedidas preservadas do estudo

| Métrica observada ou proposta na origem | Contramedida associada |
| --- | --- |
| Cobertura de cenários de usuário | Detalhar regras e especificações |
| Completude do fluxograma | Revisões periódicas do fluxo |
| Eficiência da homologação / preparação dos testes | Orientar QA e preparar cenários e massa de testes |
| Qualidade das mensagens de erro de API | Coletar feedback e ajustar conteúdo das mensagens, quando aplicável |

A origem **não** apresenta resultados quantitativos individuais dessas métricas. Os indicadores formalizados como propostas aparecem em [OKR e indicadores](./OKR_E_INDICADORES.md).

## 7. Uso dos conceitos Lean Six Sigma

O caso associa as melhorias a conceitos de Lean Six Sigma: observar desperdícios, identificar causas de retrabalho e diminuir variações que prejudiquem o entendimento.

Para aplicar o raciocínio com consistência, distinguir:

1. **Sintoma:** reuniões repetidas, dúvidas frequentes e retrabalho de explicação.
2. **Hipótese de causa:** histórias insuficientemente detalhadas e entendimento fragmentado entre frentes.
3. **Contramedida:** documentação acessível, cenários claros, revisão de fluxos, alinhamento direcionado.
4. **Medição:** dias de esclarecimento, cobertura das histórias e retorno por falta de entendimento.

Não há no original uma análise estatística ou evidências suficientes para afirmar que o case realizou um ciclo Lean Six Sigma formal ou comprovou causalidade.

## 8. Riscos e perguntas que um PO deveria levar à discussão

- A equipe tem um único backlog de produto visível e prioritário, mesmo com frentes distintas de trabalho?
- Quais participantes precisam estar em cada refinamento?
- Quais pontos realmente exigem novo detalhamento, e quais são decisões ainda abertas de produto?
- Como serão acompanhadas dependências técnicas e integrações?
- Como evitar que o aumento de documentação também gere desperdício?
- Como avaliar o resultado por indicadores sem confundir redução de reuniões com aumento da qualidade?

**Referências internas:** [README principal](../README.md) · [OKR e indicadores](./OKR_E_INDICADORES.md) · [documentação original](../DOCUMENTACAO_ORIGINAL.md).
