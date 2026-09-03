# Miniguia de Estudos: Vendas com apoio do NotebookLM

> Caderno Temático produzido com o NotebookLM (Google) para o desafio de projeto da DIO em parceria com o Santander.

## 🎯 Contexto e Objetivos

**Assunto escolhido:** Vendas — técnicas, processo comercial e prospecção.

**Por que esse tema:** Trabalho como analista comercial cobrindo o estado de São Paulo e também atuo com tráfego pago (Meta Ads), então dominar melhor o processo de vendas — da prospecção ao fechamento — tem aplicação direta no meu dia a dia e é um diferencial pra minha carreira em Data & IA.

**Objetivos de estudo:**
- [x] Entender as etapas clássicas do processo de vendas (prospecção, qualificação, abordagem, negociação, fechamento, pós-venda)
- [x] Aprender técnicas práticas de negociação e contorno de objeções
- [x] Conectar vendas B2B com dados e automação (já que é minha área de interesse)
- [x] Construir um glossário de termos comerciais pra referência rápida

---

## 📚 Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM:

1. **[Técnicas de venda: preço, gatilhos e promoções — Sebrae](https://sebrae.com.br/sites/PortalSebrae/ufs/ms/sebraeaz/conheca-tecnicas-de-venda-preco-gatilhos-e-promocoes,db551706005ee710VgnVCM100000d701210aRCRD)** — artigo do Sebrae sobre técnicas de venda aplicadas ao pequeno negócio.
2. **[27 Livros de Vendas Grátis em PDF — Infolivros](https://infolivros.org/livros-pdf-gratis/negocios/vendas/)** — curadoria de apostilas e e-books gratuitos sobre vendas B2B, prospecção e gestão comercial.
3. **[eBook: Tudo sobre Funil de Vendas — RD Station](https://www.rdstation.com/resources/ebooks/ebook-funil-de-vendas/)** — material sobre como estruturar e otimizar um funil de vendas.
4. **[eBook: CRM — como gerar mais vendas a partir da análise de dados — RD Station](https://www.rdstation.com/resources/ebooks/ebook-crm-vendas-analise-de-dados/)** — conecta vendas com dados, boa ponte com o interesse em Data/IA.

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

### Prompt 1
**Pergunta:** "Resuma as principais etapas do processo de vendas descritas nas fontes, em formato de lista"
**Resposta obtida:** A IA identificou que as fontes abordam vendas sob 4 perspectivas complementares — o processo comercial do vendedor (prospecção → pré-abordagem → abordagem → apresentação → objeções → fechamento → pós-venda), o processo de gestão/planejamento da empresa (10 etapas em 3 fases: planejamento, implementação, controle), o funil de marketing (topo/meio/fundo de funil) e a jornada de compra do cliente (aprendizado → reconhecimento → consideração → decisão).
**Fontes citadas pela IA:** Não especificou individualmente quais fontes embasaram cada bloco — resposta consolidada.
**Funcionou bem? Precisou ajustar?** Funcionou bem — a IA organizou sozinha 4 visões distintas do mesmo tema em vez de misturar tudo numa lista genérica. Ponto de atenção: pedir explicitamente "cite a fonte de cada bloco" na próxima rodada, já que ela não deixou claro qual documento embasou cada seção.

### Prompt 2
**Pergunta:** "Quais técnicas de negociação aparecem em mais de uma fonte? Compare as abordagens"
**Resposta obtida:** A IA identificou 4 técnicas recorrentes nas fontes — venda consultiva (resolver a dor do cliente), cross-selling/upselling, negociação de preços e descontos, e tratamento de objeções — e mostrou como cada uma aparece de forma diferente na literatura clássica de vendas (foco humano, cara a cara) versus nas fontes digitais/RD Station (foco em dados, automação e UX). Fechou com uma tabela comparativa: foco principal, tempo de execução e mecanismo de controle em cada abordagem.
**Fontes citadas pela IA:** Sim, dessa vez foi explícita — citou por nome "Administração de Vendas (Fava Neves)", "Sebrae", "Webinar (FGV)" e "Data-Driven Marketing (RD Station)" em cada técnica.
**Funcionou bem? Precisou ajustar?** Funcionou muito melhor que o Prompt 1 — pedir "compare" e "aparecem em mais de uma fonte" forçou a IA a atribuir cada afirmação à fonte de origem, o que não tinha acontecido antes. Prompt mais específico = rastreabilidade melhor.

### Prompt 3
**Pergunta:** "Crie um glossário com os 10 termos mais importantes sobre vendas mencionados nas fontes"
**Resposta obtida:** A IA gerou 10 termos com definições completas: Vendas Consultivas, Prospecção, Funil de Vendas, Jornada de Compra, Data-Driven, SLA, LTV, CAC, Churn e Omnichannel — misturando conceitos clássicos de vendas com métricas modernas de marketing digital.
**Fontes citadas pela IA:** Não citou fonte por termo individualmente, mas o conteúdo é claramente rastreável às fontes RD Station (SLA, LTV, CAC, Churn, Data-Driven) e Administração de Vendas/Sebrae (Prospecção, Vendas Consultivas, Funil, Jornada).
**Funcionou bem? Precisou ajustar?** Funcionou bem de primeira — pedir um número exato (10) e "os mais importantes" trouxe uma lista objetiva e bem distribuída entre os temas das fontes, sem precisar reformular.

### Dificuldades encontradas (troubleshooting)
- Prompt genérico ("resuma o processo de vendas") trouxe uma resposta boa, mas sem atribuição clara de qual fonte embasava cada bloco.
- Pedir explicitamente "compare" e "aparecem em mais de uma fonte" (Prompt 2) forçou a IA a citar a fonte de origem de cada afirmação — resultado bem mais rastreável.
- Pedir um número exato de itens ("os 10 termos mais importantes") ajudou a IA a entregar uma lista objetiva de primeira, sem precisar de ajustes.

> Dica: quanto mais específico o prompt (pedindo comparação, citação de fonte, ou formato de saída), melhor a resposta do NotebookLM.

---

## 📖 Miniguia de Estudo (Entrega Final)

### Resumo estruturado

O processo de vendas pode ser entendido sob quatro perspectivas complementares, que se conectam entre si:

**1. Processo comercial do vendedor (execução direta)**
Sequência clássica de 7 etapas: prospecção (identificar clientes com desejo, necessidade, capacidade financeira e autoridade) → pré-abordagem (levantar informações antes do contato) → abordagem (primeira impressão) → apresentação de vendas (mostrar como o produto resolve a dor do cliente) → tratamento de objeções (rebater resistências de preço, prazo ou produto) → fechamento (conduzir à decisão) → pós-venda (garantir satisfação e abrir espaço pra novas oportunidades).

**2. Gestão e planejamento comercial da empresa**
Em paralelo à venda individual, a empresa organiza a operação em 3 fases: planejamento (análise de mercado, definição de metas e território), implementação (recrutamento, treinamento da equipe) e controle (auditoria de resultados e gestão de conflitos entre canais).

**3. Funil de marketing e vendas (visão digital/inbound)**
Topo do funil (atrair visitantes) → meio do funil (converter em Lead e qualificar) → fundo do funil (oportunidade comercial pronta pra abordagem do vendedor). A passagem entre marketing e vendas é formalizada por um **SLA**, que define quando um Lead está pronto pra ser abordado.

**4. Jornada de compra do cliente**
Aprendizado e descoberta → reconhecimento do problema → consideração da solução → decisão de compra. Serve de base pra alinhar as etapas 1 e 3 ao momento real do cliente.

**Vendas tradicionais vs. vendas digitais**
As fontes clássicas (Administração de Vendas) tratam negociação, cross-selling e objeções como habilidades humanas, exercidas cara a cara. Já as fontes digitais (Sebrae, RD Station) traduzem essas mesmas técnicas em dados e automação: intenção de busca no lugar de intuição, sugestões automáticas de produto no checkout no lugar da oferta verbal do vendedor, e registro estruturado de motivos de perda no CRM no lugar do "feeling" pós-venda.

**Métricas que sustentam a operação**
CAC (quanto custa converter um cliente), LTV (quanto esse cliente gera ao longo do relacionamento), Churn (taxa de perda de clientes) e SLA (acordo entre marketing e vendas) são os indicadores que conectam o processo comercial à saúde financeira do negócio.

### Glossário

| Termo | Definição |
|---|---|
| Vendas Consultivas | Abordagem focada em resolver o problema real do cliente e construir relação de confiança, em vez de empurrar produto |
| Prospecção | Identificação de clientes em potencial com desejo, necessidade, capacidade financeira e autoridade para comprar |
| Funil de Vendas | Etapas do processo comercial desde o recebimento da oportunidade até o fechamento do pedido |
| Jornada de Compra | Caminho do cliente: aprendizado e descoberta → reconhecimento do problema → consideração da solução → decisão de compra |
| Data-Driven | Cultura de basear decisões em dados e métricas reais, em vez de intuição |
| SLA (Service Level Agreement) | Acordo entre marketing e vendas sobre quando um Lead está pronto pra ser abordado e o prazo de resposta do vendedor |
| LTV (Lifetime Value) | Valor total que um cliente gera pra empresa ao longo de todo o relacionamento |
| CAC (Custo de Aquisição de Clientes) | Soma de todos os investimentos necessários pra converter um novo cliente |
| Churn | Taxa de perda/cancelamento de clientes |
| Omnichannel | Integração de todos os canais de venda e atendimento numa experiência única pro cliente |

### Prompts reutilizáveis para revisão futura

```
1. "Com base nos documentos carregados, monte um quiz de 5 perguntas sobre [etapa do processo de vendas]."
2. "Compare as técnicas de negociação apresentadas nas fontes X e Y, destacando semelhanças e diferenças."
3. "Explique [termo do glossário] como se eu estivesse aprendendo pela primeira vez, usando um exemplo prático de vendas B2B."
4. "Liste os pontos em que as fontes discordam entre si, se houver."
```

---

## 🔗 Sobre este projeto

Projeto desenvolvido para o desafio de projeto da [DIO](https://www.dio.me/) em parceria com o Santander, trilha de Data & Artificial Intelligence.
