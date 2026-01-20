# 🔎 Revisão Conceitual — Análise de Crédito e Risco Financeiro

Este documento consolida os **resultados da etapa de revisão conceitual** do projeto *Mini Guia de Estudo — Análise de Crédito e Risco Financeiro com IA Generativa*.

As respostas apresentadas foram geradas a partir da execução de **prompts estruturados no NotebookLM**, utilizando exclusivamente as fontes selecionadas no projeto. O objetivo é reforçar conceitos-chave, esclarecer dúvidas recorrentes e apoiar revisões futuras.

---

## 🎯 Objetivo da Revisão

- Reforçar os principais conceitos de **risco de crédito e risco financeiro**
- Verificar consistência conceitual entre diferentes fontes
- Identificar limitações e pontos de atenção em análises automatizadas
- Apoiar revisões rápidas antes de avaliações ou novos estudos

---

## 🧠 Metodologia Utilizada

- Execução de prompts previamente definidos no arquivo:
  - `/prompts/prompts_revisao.md`
- Geração de respostas pelo **NotebookLM**
- Registro estruturado no formato **Prompt → Resposta**
- Todas as respostas são fundamentadas nas fontes carregadas no caderno

---

## 📌 Revisões Conceituais

### PROMPT 1:
> Com base nas fontes fornecidas e nos resumos estruturados já elaborados, apresente uma revisão geral dos principais conceitos de análise de crédito e gestão de riscos financeiros.  
> Organize a resposta em tópicos claros e objetivos, destacando os pontos mais relevantes para um estudante iniciante.

### RESPOSTA:
A análise de crédito e a gestão de riscos financeiros são pilares fundamentais para a estabilidade das instituições e do sistema econômico, baseando-se em metodologias que buscam mensurar a incerteza e proteger o capital. Abaixo, os principais conceitos são detalhados de forma estruturada:

### 1. Definições Fundamentais de Risco
*   **Risco de Crédito:** É definido como a **probabilidade de perda** resultante da inadimplência do tomador ou da incapacidade da contraparte em honrar compromissos financeiros assumidos.
*   **Risco de Mercado:** Refere-se à possibilidade de perdas devido a variações nos preços de mercado, taxas de juros ou câmbio.
*   **Risco de Liquidez:** É o risco de não conseguir vender um ativo ou fechar uma posição rapidamente sem incorrer em custos significativos, prejudicando o fluxo de caixa.
*   **Risco Operacional:** Envolve perdas causadas por falhas humanas, processos internos inadequados, sistemas ou eventos externos.

### 2. A Análise Tradicional: Os "5 Cs" do Crédito
A análise qualitativa de um cliente baseia-se em cinco dimensões essenciais que servem como roteiro para o analista:
*   **Caráter:** Avalia a **vontade e determinação do devedor** em cumprir seus compromissos, observando idoneidade e histórico passado.
*   **Capacidade:** Foca na competência gerencial e no potencial da empresa ou indivíduo em gerar recursos para o pagamento.
*   **Capital:** Analisa a saúde financeira, patrimônio líquido e a estrutura de capital da entidade.
*   **Condições:** Observa o cenário macroeconômico e o setor específico em que o tomador está inserido, avaliando influências externas.
*   **Colateral:** Refere-se às **garantias acessórias** (reais ou pessoais) oferecidas para mitigar o risco da operação.

### 3. Modelagem Quantitativa: Credit Scoring
Para agilizar processos e reduzir a subjetividade, utilizam-se modelos estatísticos denominados *Credit Scoring*.
*   **Application Scoring:** Utilizado para novos clientes, baseando-se em dados cadastrais e de mercado, já que não há histórico interno.
*   **Behavioral Scoring:** Aplica-se a clientes que já possuem relacionamento com a instituição, incorporando o **histórico de comportamento de pagamentos** para aumentar o poder preditivo.
*   **Métricas de Validação:** A eficácia desses modelos é medida por indicadores como o índice **Kolmogorov-Smirnov (KS)**, o Coeficiente de Gini e a Curva ROC.

### 4. Gestão de Risco de Carteira (Portfólio)
A gestão moderna não avalia apenas o risco individual, mas o comportamento do conjunto de ativos.
*   **Diversificação:** Princípio que busca combinar ativos com baixa correlação para reduzir o risco não sistemático e maximizar o retorno.
*   **Risco de Concentração:** Ocorre quando uma parcela significativa do capital está exposta a poucos clientes ou a um único setor da economia.
*   **Migração de Risco:** Monitoramento das variações no nível de risco (*rating*) de um empréstimo ao longo do tempo, permitindo estratégias preventivas de cobrança.

### 5. Padrões Regulatórios e o Acordo de Basiléia
As normas internacionais estabelecem parâmetros para que os bancos mantenham capital suficiente para suportar riscos.
*   **Pilar I de Basiléia II:** Define os requisitos mínimos de capital para riscos de crédito, mercado e operacional.
*   **Perda Esperada (EL):** Estimativa do valor que a instituição espera perder em média, calculada pela multiplicação da Probabilidade de Default (PD), Exposição no Default (EAD) e Perda dado o Default (LGD).
*   **Patrimônio de Referência:** Capital que a instituição deve manter regulamentarmente para absorver perdas inesperadas.

### 6. O Papel do Julgamento Humano (*Override*)
Embora a tecnologia traga eficiência, as fontes destacam que os modelos estatísticos possuem limitações, como a dependência de dados passados e a rigidez. O **julgamento humano** é essencial para identificar mudanças de cenário e realizar o *override*, que é a decisão de contrariar o modelo automático baseando-se em informações qualitativas não captadas pelo sistema.

---

### PROMPT 2:
> Elabore um conjunto de perguntas e respostas com base nas fontes e nos resumos gerados, visando à autoavaliação do aprendizado.  
> Priorize perguntas conceituais e explicativas, evitando cálculos ou modelagens avançadas.  
> Organize o resultado em formato de lista numerada.

### RESPOSTA:
Com base nos documentos consultados, aqui está um conjunto de perguntas e respostas para autoavaliação sobre **análise de crédito e gestão de riscos**:

### **1. Fundamentos e Definições de Risco**

1.  **Como se define o risco de crédito em termos financeiros?**
    *   **Resposta:** O risco de crédito é a **probabilidade de perda** resultante da inadimplência do tomador ou da incapacidade da contraparte em honrar os compromissos financeiros assumidos com o credor. Ele também pode envolver a degradação da qualidade do crédito, quando o nível de risco de um devedor piora (ex: de nota A para C).

2.  **Qual a diferença entre risco sistemático e não sistemático?**
    *   **Resposta:** O risco **não sistemático** (ou diversificável) é aquele ligado a um devedor ou setor específico, podendo ser reduzido através da diversificação da carteira. Já o **risco sistemático** está associado a fatores macroeconômicos que afetam todo o mercado e não pode ser eliminado apenas pela adição de mais ativos ao portfólio.

3.  **O que compõe a estrutura das "Três Linhas" na gestão de riscos?**
    *   **Resposta:** A **1ª linha** é formada pelos gestores de processos que administram os riscos no dia a dia; a **2ª linha** provê metodologias, suporte técnico e monitora a conformidade; e a **3ª linha** é a Auditoria Interna, que realiza avaliações independentes sobre a eficácia dos controles e da governança.

---

### **2. Análise e Modelagem de Crédito**

4.  **Quais são os tradicionais "5 Cs" do crédito e o que cada um avalia?**
    *   **Resposta:** São eles: **Caráter** (vontade do devedor em pagar/idoneidade); **Capacidade** (competência gerencial e potencial de geração de caixa); **Capital** (saúde financeira e patrimônio); **Condições** (cenário econômico e situação do setor); e **Colateral** (garantias oferecidas para mitigar a perda).

5.  **Qual a diferença conceitual entre os modelos de *Application Scoring* e *Behavioral Scoring*?**
    *   **Resposta:** O ***Application Scoring*** é utilizado para avaliar **novos clientes** com base em dados cadastrais e de mercado. O ***Behavioral Scoring*** é aplicado a **clientes antigos**, incorporando o histórico de comportamento de pagamento e relacionamento com a instituição, o que geralmente confere maior poder preditivo ao modelo.

6.  **Por que o julgamento humano (*override*) ainda é essencial diante de modelos automáticos?**
    *   **Resposta:** Os modelos estatísticos dependem de dados do passado e podem tornar-se obsoletos diante de **mudanças bruscas no cenário econômico**. Além disso, máquinas têm dificuldade em avaliar fatores qualitativos subjetivos, como o "Caráter", e o julgamento humano serve para corrigir distorções em variáveis que penalizam injustamente um bom cliente.

---

### **3. Gestão de Carteira e Padrões Regulatórios**

7.  **Quais são os três pilares estabelecidos pelo Acordo de Basiléia II?**
    *   **Resposta:** O **Pilar I** trata dos requisitos mínimos de capital para riscos de crédito, mercado e operacional; o **Pilar II** reforça a supervisão bancária e a análise da gestão interna; e o **Pilar III** foca na transparência e divulgação de informações para que o mercado exerça disciplina sobre as instituições.

8.  **O que é a Perda Esperada (EL) e quais parâmetros a compõem?**
    *   **Resposta:** É a estimativa do valor que se espera perder, em média, em uma operação. Ela é calculada pela multiplicação de três componentes: a **Probabilidade de Default (PD)**, a **Exposição no Default (EAD)** e a **Perda dado o Default (LGD)**.

9.  **Como a matriz de riscos auxilia na tomada de decisão?**
    *   **Resposta:** A matriz cruza a **probabilidade** de ocorrência de um evento com o seu **impacto** esperado. Isso gera um nível de criticidade (baixo, médio, alto ou extremo) que permite à administração priorizar quais riscos devem ser mitigados, evitados, transferidos ou simplesmente aceitos.

---

### **4. Gestão de Continuidade e Liquidez**

10. **O que é o risco de liquidez e como ele impacta uma instituição?**
    *   **Resposta:** É o risco de uma instituição não conseguir vender um ativo rapidamente ou fechar uma posição sem incorrer em custos elevados, o que pode prejudicar sua capacidade de honrar compromissos de caixa imediatos.

11. **Qual o objetivo de um Plano de Continuidade de Negócios (PCN)?**
    *   **Resposta:** O PCN estabelece estratégias e procedimentos para permitir que processos críticos de uma organização sejam **retomados rapidamente** após uma interrupção (como falhas de sistema ou desastres), minimizando danos à operação e à imagem da instituição.

---

### PROMPT 3:
> Produza uma síntese final do mini guia de estudos sobre análise de crédito e risco financeiro, integrando os principais conceitos, definições e aprendizados.  
> Utilize linguagem clara e objetiva, adequada a um nível introdutório.

### RESPOSTA:
Esta síntese consolida os fundamentos da análise de crédito e da gestão de riscos financeiros, integrando as metodologias tradicionais, os modelos estatísticos modernos e os padrões regulatórios essenciais para o setor.

### 1. Definições e Tipos de Risco
O **risco** é definido como o efeito das incertezas sobre os objetivos de uma organização, podendo resultar em ameaças ou oportunidades. No contexto financeiro, os principais riscos são:
*   **Risco de Crédito:** A probabilidade de perda resultante da inadimplência do tomador ou da incapacidade da contraparte em honrar compromissos financeiros.
*   **Risco de Mercado:** Possibilidade de perdas devido a variações nos preços, taxas de juros ou câmbio.
*   **Risco de Liquidez:** O risco de não conseguir vender um ativo ou fechar uma posição rapidamente sem custos significativos, prejudicando o fluxo de caixa.
*   **Risco Operacional:** Perdas causadas por falhas humanas, processos internos inadequados, sistemas ou eventos externos.

### 2. A Análise Qualitativa: Os "5 Cs" do Crédito
A base primária para a decisão de concessão de crédito envolve a avaliação de cinco dimensões críticas do devedor:
1.  **Caráter:** A vontade e determinação do devedor em cumprir seus compromissos, avaliada por sua idoneidade e histórico passado.
2.  **Capacidade:** A competência gerencial e o potencial da empresa ou indivíduo em gerar recursos para o pagamento.
3.  **Capital:** A saúde financeira e o patrimônio líquido, analisados por meio de demonstrativos contábeis.
4.  **Condições:** O cenário macroeconômico e a situação específica do setor em que o tomador atua.
5.  **Colateral:** As garantias acessórias oferecidas para mitigar as perdas em caso de inadimplência.

### 3. Modelagem e Automação (*Credit Scoring*)
Para ganhar agilidade e reduzir a subjetividade, utilizam-se modelos estatísticos chamados ***Credit Scoring***, que visam prever a probabilidade de inadimplência.
*   ***Application Scoring:*** Avalia novos clientes sem histórico na instituição, baseando-se em dados cadastrais.
*   ***Behavioral Scoring:*** Aplicado a clientes antigos, incorporando o histórico de relacionamento e comportamento de pagamento.
*   **Limitações e o *Override*:** Modelos automatizados dependem de dados passados e podem falhar diante de mudanças bruscas no cenário econômico ou fatores qualitativos como o "Caráter". Por isso, o **julgamento humano** é essencial para realizar o ***override*** (interferência humana na decisão do sistema) quando necessário.

### 4. Gestão de Carteira e Diversificação
A gestão moderna foca no risco agregado da carteira, e não apenas em contratos individuais. O objetivo é utilizar a **diversificação** (combinar ativos com baixa correlação) para minimizar o risco e maximizar o retorno. O monitoramento constante evita o **risco de concentração**, que ocorre quando uma parcela excessiva do capital está exposta a poucos clientes ou setores específicos.

### 5. Padrões Regulatórios e Perda Esperada
O **Acordo de Basiléia** estabelece padrões globais de supervisão e requisitos mínimos de capital para garantir que os bancos suportem os riscos assumidos. Um conceito central é a **Perda Esperada (EL)**, calculada pela fórmula:
> **EL = PD x EAD x LGD**
*   **PD (*Probability of Default*):** Probabilidade de o cliente não pagar.
*   **EAD (*Exposure at Default*):** Valor total exposto no momento da inadimplência.
*   **LGD (*Loss Given Default*):** Percentual da perda efetiva caso o default ocorra.

Essas métricas auxiliam as instituições a definir o nível de capital necessário para sua proteção e a garantir a continuidade dos negócios diante de crises.

---

### PROMPT 4:
> Com base nas fontes e nos conteúdos gerados, identifique possíveis dúvidas, ambiguidades ou pontos que merecem maior atenção em estudos futuros.  
> Liste esses pontos de forma organizada, justificando brevemente cada um.

### RESPOSTA:
Com base na análise das fontes e no conteúdo discutido, identificam-se pontos que apresentam ambiguidades técnicas ou que demandam um aprofundamento maior devido à sua complexidade e impacto na estabilidade financeira.

Abaixo, os temas são apresentados de forma organizada para orientar estudos futuros:

### 1. Mensuração Quantitativa de Fatores Qualitativos (O "C" de Caráter)
*   **Dúvida/Ponto de Atenção:** Como transformar variáveis subjetivas, como a idoneidade e a vontade de pagar do devedor (**Caráter**), em dados estatísticos precisos?
*   **Justificativa:** As fontes admitem que os modelos de *credit scoring* focam majoritariamente na dimensão "Capital" (dados contábeis), negligenciando riscos "fora do balanço" e fatores humanos que são vitais para prever a inadimplência, mas difíceis de quantificar.

### 2. Governança e Eficácia do Julgamento Humano (*Override*)
*   **Dúvida/Ponto de Atenção:** Quais são os limites técnicos e éticos para que um analista contrarie a decisão de um modelo automatizado?
*   **Justificativa:** Embora o *override* seja necessário para corrigir distorções, o uso excessivo ou mal documentado pode invalidar o significado probabilístico do modelo original e reintroduzir a subjetividade que a automação visava eliminar.

### 3. Gestão Integrada do Risco de Concentração
*   **Dúvida/Ponto de Atenção:** Como integrar o risco de concentração de portfólio diretamente no cálculo de capital regulamentar de forma padronizada?
*   **Justificativa:** As fontes apontam que as normas (como a Resolução 2.682) focam no risco individual da operação, criando uma "brecha" onde uma carteira pode parecer sólida individualmente, mas estar perigosamente exposta a um único setor ou grupo de devedores.

### 4. Vulnerabilidade dos Modelos à Integridade dos Dados
*   **Dúvida/Ponto de Atenção:** De que forma as instituições e reguladores podem garantir a veracidade dos dados de entrada para evitar o efeito "lixo entra, lixo sai"?
*   **Justificativa:** Casos históricos citados mostram que fraudes e "maquiagens" contábeis podem forjar uma saúde financeira irreal que os sistemas especialistas são incapazes de detectar se a base de dados estiver corrompida na origem.

### 5. Desafios de Basiléia II para Instituições de Menor Porte
*   **Dúvida/Ponto de Atenção:** Qual o impacto da disparidade competitiva entre grandes bancos (que usam modelos internos IRB) e bancos menores (que usam a abordagem padronizada)?
*   **Justificativa:** A implementação de modelos avançados exige altos investimentos em tecnologia e pessoal especializado; bancos menores podem acabar retendo proporcionalmente mais capital por não terem recursos para validar seus próprios modelos de risco.

### 6. Convergência entre Riscos Operacionais e Cibernéticos
*   **Dúvida/Ponto de Atenção:** Como consolidar a gestão de riscos cibernéticos dentro da taxonomia tradicional de risco operacional de forma harmônica?
*   **Justificativa:** O manual do Banco Central trata o risco cibernético com uma governança específica, mas a interdependência entre falhas de sistema, ataques externos e continuidade de negócios exige uma visão cada vez mais integrada e menos segmentada.

### 7. Comportamento de Modelos em Crises Extraeconômicas
*   **Dúvida/Ponto de Atenção:** Como ajustar modelos que dependem do passado para prever comportamentos em cenários de ruptura total, como pandemias ou crises climáticas extremas?
*   **Justificativa:** A premissa básica de que o futuro repete o passado torna os modelos estatísticos obsoletos diante de mudanças bruscas nas condições socioeconômicas, exigindo novas abordagens de **Testes de Estresse** e modelos de simulação mais dinâmicos.

---

### PROMPT 5:
> A partir do conteúdo estudado, destaque os conceitos que seriam mais relevantes em uma prova introdutória ou entrevista básica sobre análise de crédito e risco financeiro.  
> Explique brevemente por que cada conceito é importante.

### RESPOSTA: 
Com base nos documentos consultados, os conceitos listados abaixo representam o núcleo fundamental da **análise de crédito e gestão de riscos**, sendo os temas mais prováveis em avaliações ou entrevistas para iniciantes no setor financeiro:

### 1. Definição e Tipos de Risco Financeiro
*   **O que é:** O risco é o efeito das incertezas sobre os objetivos, podendo ser uma ameaça ou oportunidade. Os principais tipos são: **Risco de Crédito** (inadimplência), **Risco de Mercado** (flutuação de preços e taxas), **Risco de Liquidez** (dificuldade em converter ativos em caixa) e **Risco Operacional** (falhas em processos, sistemas ou pessoas).
*   **Por que é importante:** Compreender essas distinções permite que o analista identifique a origem exata da incerteza e utilize a ferramenta de mitigação correta para cada caso.

### 2. Os "5 Cs" do Crédito
*   **O que é:** Um roteiro de análise qualitativa composto por **Caráter** (idoneidade e vontade de pagar), **Capacidade** (competência gerencial e geração de caixa), **Capital** (patrimônio líquido), **Condições** (cenário econômico e setorial) e **Colateral** (garantias oferecidas).
*   **Por que é importante:** Garante que nenhum aspecto relevante da saúde do tomador seja esquecido, equilibrando dados frios do balanço com fatores comportamentais e externos.

### 3. Credit Scoring (Application vs. Behavioral)
*   **O que é:** O ***Application Scoring*** avalia novos clientes com base em dados cadastrais; o ***Behavioral Scoring*** avalia clientes antigos usando o histórico de comportamento de pagamento na instituição.
*   **Por que é importante:** Permite a **decisão em massa**, reduz o custo operacional e elimina a subjetividade do julgamento humano em operações de varejo.

### 4. Perda Esperada (Expected Loss - EL)
*   **O que é:** Uma estimativa financeira calculada pela fórmula: **EL = PD x LGD x EAD**.
    *   **PD (*Probability of Default*):** Probabilidade de o devedor não pagar.
    *   **LGD (*Loss Given Default*):** Percentual da perda efetiva após a tentativa de recuperação.
    *   **EAD (*Exposure at Default*):** Valor total exposto no momento da inadimplência.
*   **Por que é importante:** É a base para o cálculo de provisões e para determinar quanto capital a instituição deve reservar para cobrir perdas estatisticamente prováveis.

### 5. Gestão de Carteira: Diversificação vs. Concentração
*   **O que é:** A **diversificação** busca combinar ativos com baixa correlação para reduzir o risco; a **concentração** ocorre quando uma grande parte do capital está exposta a poucos clientes ou setores.
*   **Por que é importante:** Uma carteira pode ter clientes individualmente bons, mas se todos forem do mesmo setor, um evento sistêmico (como uma crise agrícola) pode quebrar a instituição.

### 6. Padrões Regulatórios (Resolução 2.682/99 e Basiléia)
*   **O que é:** Normas que obrigam os bancos a classificar operações em faixas de risco (de **AA a H**) e a constituir provisões proporcionais a esse risco.
*   **Por que é importante:** Traz **transparência** ao mercado, impede "maquiagens" contábeis e garante que o sistema financeiro tenha capital suficiente para suportar crises.

### 7. O Conceito de *Override* e Julgamento Humano
*   **O que é:** A decisão do analista de **contrariar o modelo estatístico** com base em informações qualitativas que o sistema não captou.
*   **Por que é importante:** Modelos automáticos são rígidos e dependem do passado; o julgamento humano é essencial para identificar mudanças bruscas de cenário ou fraudes que os dados históricos ainda não refletem.

### 8. Estrutura de "Três Linhas de Defesa"
*   **O que é:** Modelo de governança onde a **1ª linha** é a gestão operacional, a **2ª linha** é a área de riscos e conformidade, e a **3ª linha** é a auditoria interna.
*   **Por que é importante:** Garante a segregação de funções e assegura que os riscos sejam monitorados de forma independente dos tomadores de decisão comerciais.

---

## 🧩 Síntese da Revisão

### Principais conceitos reforçados:
- Definição e classificação dos **principais tipos de risco financeiro** (crédito, mercado, liquidez e operacional), com ênfase no risco de crédito como probabilidade de perda por inadimplência.
- Estrutura clássica dos **5 Cs do Crédito** (Caráter, Capacidade, Capital, Condições e Colateral) como base da análise qualitativa.
- Uso de **modelos de Credit Scoring** (Application e Behavioral) para apoiar decisões em escala, reduzindo subjetividade e custo operacional.
- Importância da **gestão de risco de carteira**, destacando diversificação, risco de concentração e migração de risco ao longo do tempo.
- Conceito de **Perda Esperada (EL)** e seus componentes (PD, LGD e EAD) como fundamento para provisões e gestão de capital.
- Papel dos **acordos regulatórios (Basiléia e normas locais)** na exigência de capital mínimo e na estabilidade do sistema financeiro.
- Relevância do **julgamento humano (override)** como complemento aos modelos automatizados.
- Estrutura de governança baseada nas **Três Linhas de Defesa** para gestão e controle de riscos.

### Pontos que exigem maior atenção:
- A dificuldade prática de **mensurar fatores qualitativos**, especialmente o “Caráter”, de forma robusta em modelos estatísticos.
- A necessidade de **governança clara para o uso de overrides**, evitando distorções e excesso de subjetividade.
- A vulnerabilidade dos modelos à **qualidade e integridade dos dados** utilizados como entrada.
- A gestão do **risco de concentração** como complemento essencial à análise individual das operações.
- O comportamento dos modelos de risco em **cenários de ruptura**, como crises sistêmicas, pandemias ou eventos climáticos extremos.
- A integração entre riscos **operacionais, tecnológicos e cibernéticos**, cada vez mais interdependentes.

### Conceitos que apresentaram ambiguidades entre fontes:
- O grau ideal de **intervenção humana (override)** versus a autonomia dos modelos estatísticos.
- A forma mais adequada de incorporar **riscos qualitativos e comportamentais** em modelos quantitativos.
- A **assimetria regulatória** entre grandes instituições (com modelos internos avançados) e instituições de menor porte.
- A delimitação entre **risco operacional tradicional** e risco cibernético, especialmente em termos de governança e mensuração.

## ⚠️ Observações e Limitações

- As respostas refletem **exclusivamente o conteúdo das fontes fornecidas**
- A IA atua como ferramenta de **organização e síntese**, não substituindo análise humana
- Recomenda-se revisão crítica dos conteúdos antes de aplicação prática

---

## 📚 Relação com o Projeto

Este documento integra a pasta `/resultados` e corresponde diretamente à execução dos prompts definidos em `/prompts/prompts_revisao.md`, atendendo ao resultado esperado do desafio proposto pela DIO.

---