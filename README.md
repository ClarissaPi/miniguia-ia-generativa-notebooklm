# Miniguia de Inteligência Artificial Generativa com NotebookLM

> Projeto desenvolvido para o **Desafio de Projeto da DIO**, utilizando o NotebookLM como ferramenta de aprendizagem ativa, pesquisa, organização do conhecimento e experimentação com Inteligência Artificial.

---

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO**, com o objetivo de explorar a Inteligência Artificial como ferramenta de aprendizagem ativa.

O tema escolhido foi:

> **Inteligência Artificial Generativa: fundamentos, aplicações, riscos e engenharia de prompts.**

A proposta foi utilizar o **NotebookLM** para organizar fontes confiáveis, formular perguntas, comparar respostas, identificar limitações e transformar o conteúdo pesquisado em um miniguia de estudos.

Mais do que obter respostas de uma IA, o objetivo foi desenvolver um processo de aprendizagem baseado em:

- curadoria de fontes;
- elaboração de perguntas;
- engenharia de prompts;
- verificação das informações;
- organização do conhecimento;
- identificação de limitações;
- reflexão crítica sobre o uso da IA.

---

# 1. Contexto e objetivos

## Contexto

A Inteligência Artificial Generativa ganhou grande relevância por sua capacidade de produzir diferentes tipos de conteúdo, como textos, códigos, imagens, áudio e outros materiais.

Ao mesmo tempo em que essas tecnologias ampliam possibilidades de produtividade e aprendizagem, também apresentam desafios relacionados à confiabilidade, segurança, vieses, privacidade, propriedade intelectual e uso responsável.

Neste projeto, o NotebookLM foi utilizado como ambiente de pesquisa e aprendizagem baseado em fontes previamente selecionadas.

Além dos materiais técnicos e acadêmicos, foi incluída uma fonte brasileira sobre o uso responsável da IA Generativa no serviço público, ampliando a análise para questões práticas de segurança, privacidade, responsabilidade e contexto institucional.

## Objetivo geral

Construir uma visão introdutória e estruturada sobre Inteligência Artificial Generativa, compreendendo seus fundamentos, aplicações, limitações, riscos e técnicas básicas de engenharia de prompts.

## Objetivos específicos

- Compreender o conceito de Inteligência Artificial Generativa.
- Diferenciar IA, Machine Learning, Deep Learning e IA Generativa.
- Entender, em nível introdutório, a importância da arquitetura Transformer.
- Compreender o conceito de Large Language Model (LLM).
- Estudar os principais usos da IA Generativa.
- Identificar limitações como alucinações e vieses.
- Conhecer princípios de IA responsável.
- Aprender fundamentos de engenharia de prompts.
- Utilizar o NotebookLM para consultar fontes selecionadas.
- Comparar diferentes estratégias de prompting.
- Identificar riscos relacionados à privacidade e segurança.
- Criar um conjunto de prompts reutilizáveis para estudos futuros.

---

# 2. Curadoria das fontes

Foram selecionadas fontes públicas e de instituições reconhecidas, priorizando materiais técnicos, acadêmicos, institucionais e educacionais.

## Fonte 1 — NIST

### Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile

**Instituição:** National Institute of Standards and Technology (NIST)

**Tipo:** documento técnico / PDF

**Link:**

https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence

### Justificativa

A fonte foi selecionada para estudar os riscos associados à Inteligência Artificial Generativa e compreender práticas relacionadas ao gerenciamento responsável desses riscos.

O material contribui principalmente para os tópicos de segurança, confiabilidade, avaliação e gerenciamento de riscos.

---

## Fonte 2 — Stanford HAI

### AI Index Report

**Instituição:** Stanford Institute for Human-Centered Artificial Intelligence

**Tipo:** relatório / PDF

**Link:**

https://hai.stanford.edu/ai-index

### Justificativa

O relatório foi selecionado para analisar a evolução da Inteligência Artificial sob uma perspectiva mais ampla.

O AI Index apresenta informações relacionadas à evolução técnica da IA, investimentos, adoção empresarial, segurança, educação, políticas públicas e impacto social.

---

## Fonte 3 — Google Cloud

### Prompt Engineering: Overview and Guide

**Instituição:** Google Cloud

**Tipo:** material educacional

**Link:**

https://cloud.google.com/discover/what-is-prompt-engineering

### Justificativa

A fonte foi utilizada para fundamentar a parte prática relacionada à engenharia de prompts.

Ela contribui para compreender como instruções podem ser estruturadas, testadas e refinadas para melhorar os resultados obtidos com modelos generativos.

---

## Fonte 4 — Google for Developers

### Machine Learning Glossary — Generative AI

**Instituição:** Google for Developers

**Tipo:** documentação técnica

**Link:**

https://developers.google.com/machine-learning/glossary/generative

### Justificativa

Foi utilizada como fonte complementar para conceitos técnicos relacionados à IA Generativa, modelos de linguagem e engenharia de prompts.

---

## Fonte 5 — Attention Is All You Need

**Autores:** Ashish Vaswani et al.

**Tipo:** artigo acadêmico

**Link:**

https://arxiv.org/abs/1706.03762

### Justificativa

O artigo foi selecionado por apresentar a arquitetura Transformer, uma referência fundamental para compreender a evolução dos modernos modelos de linguagem.

A publicação apresenta uma arquitetura baseada em mecanismos de atenção.

---

## Fonte 6 — Guia Prático para o Uso Responsável da Inteligência Artificial Generativa no Dia a Dia do Serviço Público

**Arquivo utilizado:** `infograficos_defeso.pdf`

**Tipo:** guia prático / infográfico

**Contexto:** uso responsável de IA Generativa no serviço público brasileiro

**Link:** https://www.gov.br/governodigital/pt-br/infraestrutura-nacional-de-dados/inteligencia-artificial-1/publicacoes/guia-ia-generativa

### Justificativa

Esta fonte foi adicionada para trazer ao projeto uma perspectiva prática e contextualizada sobre o uso responsável da IA no Brasil.

O material apresenta recomendações sobre formulação de solicitações, utilização das respostas, proteção de dados, informações sigilosas, soluções institucionais, rastreabilidade, revisão humana, alucinações, vieses, transparência e responsabilidade.

Também aborda riscos relacionados a vazamento de dados, uso malicioso da IA, informações desatualizadas e geração de informações incorretas.

A fonte foi especialmente importante para ampliar a discussão sobre o uso de IA para além da qualidade da resposta, considerando também a segurança das informações utilizadas no prompt e a responsabilidade de quem utiliza o resultado.

---

# 3. Uso do NotebookLM

As fontes foram organizadas em um notebook temático no NotebookLM.

A estratégia de estudo foi dividida em quatro etapas:

```text
Fontes
   ↓
Perguntas iniciais
   ↓
Aprofundamento
   ↓
Comparação e verificação
   ↓
Síntese do conhecimento
```

O NotebookLM foi utilizado principalmente para:

- resumir documentos;
- localizar conceitos;
- comparar informações;
- formular perguntas de revisão;
- identificar relações entre os conteúdos;
- apoiar a construção do glossário;
- testar diferentes formas de questionamento;
- analisar riscos e boas práticas.

A IA foi tratada como **ferramenta de apoio ao estudo**, e não como substituta da análise das fontes.

---

# 4. Engenharia de prompts

Uma das principais etapas do projeto foi experimentar diferentes formas de formular perguntas.

O objetivo foi observar como mudanças no contexto, na estrutura e na finalidade do prompt poderiam alterar a qualidade e a utilidade das respostas.

---

## Teste 1 — Prompt genérico

### Prompt

> O que é Inteligência Artificial Generativa?

### Objetivo

Obter uma definição inicial do conceito.

### Problema identificado

A pergunta é muito ampla e não define:

- nível de conhecimento;
- profundidade;
- estrutura;
- exemplos desejados.

### Aprendizado

Um prompt muito aberto pode produzir uma resposta correta, porém genérica.

---

# Teste 2 — Definição com contexto

### Prompt

> Com base nas fontes disponíveis neste notebook, explique o que é Inteligência Artificial Generativa para uma pessoa que possui conhecimentos básicos de tecnologia. Apresente a definição, explique como ela se diferencia da IA tradicional e dê três exemplos de aplicação.

### Melhorias adicionadas

- contexto;
- público-alvo;
- escopo;
- estrutura esperada;
- quantidade de exemplos.

### Aprendizado

Quanto mais claro o objetivo da pergunta, maior a possibilidade de obter uma resposta adequada à finalidade do estudo.

---

# Teste 3 — Comparação estruturada

### Prompt

> Com base nas fontes carregadas, compare Inteligência Artificial, Machine Learning, Deep Learning e Inteligência Artificial Generativa. Organize a resposta em uma tabela contendo: definição, objetivo, exemplos de aplicação e relação entre os conceitos. Ao final, explique de forma simples como esses conceitos se relacionam.

### Objetivo

Comparar conceitos relacionados sem misturá-los.

### Aprendizado

Definir explicitamente o formato da resposta ajuda a organizar informações e facilita a revisão.

---

# Teste 4 — Aprofundamento técnico

### Prompt

> Explique a importância da arquitetura Transformer para o desenvolvimento dos modernos modelos de linguagem. Comece com uma explicação para iniciantes e depois apresente uma explicação de nível intermediário. Utilize as fontes disponíveis e indique quais fontes sustentam cada parte da explicação.

### Objetivo

Observar como o nível de profundidade pode ser controlado pelo próprio prompt.

---

# Teste 5 — Uso responsável

### Prompt

> Com base nas fontes disponíveis no notebook, analise a seguinte situação: um servidor público deseja utilizar uma ferramenta de IA Generativa para elaborar um documento institucional. Identifique quais informações poderiam ser utilizadas no prompt, quais informações deveriam ser removidas ou anonimizadas e quais etapas de revisão humana seriam necessárias antes da utilização do conteúdo. Considere aspectos de proteção de dados, segurança, confiabilidade e responsabilidade.

### Objetivo

Aplicar conceitos teóricos a uma situação prática.

### Aprendizado

O prompt pode ser utilizado não apenas para solicitar conteúdo, mas também para analisar riscos e definir boas práticas de utilização da própria IA.

---

# 5. As “cicatrizes” do processo

A documentação das dificuldades encontradas é uma parte importante deste projeto.

A intenção foi demonstrar que o resultado não surgiu simplesmente de uma única pergunta feita à IA.

---

## Cicatriz 1 — Pergunta ampla demais

### Problema

Perguntas muito abertas produziram respostas extensas e pouco direcionadas.

### Solução

Adicionar:

- objetivo;
- público;
- formato;
- limite de escopo;
- fontes permitidas.

---

## Cicatriz 2 — Excesso de informação

### Problema

Algumas respostas apresentavam mais conceitos do que o necessário para uma revisão introdutória.

### Solução

Solicitar explicitamente:

> Responda de forma objetiva e priorize somente os conceitos fundamentais necessários para compreender o tema.

---

## Cicatriz 3 — Necessidade de verificar afirmações

### Problema

Uma resposta produzida por IA não deve ser automaticamente considerada verdadeira apenas porque está bem escrita.

### Solução

Solicitar respostas fundamentadas nas fontes carregadas e verificar informações relevantes nos documentos originais.

---

## Cicatriz 4 — Diferentes níveis de conhecimento

### Problema

Uma explicação muito técnica pode dificultar o aprendizado de quem está começando.

### Solução

Utilizar prompts que definam explicitamente o nível:

> Explique primeiro como se eu fosse iniciante e depois apresente uma versão de nível intermediário.

---

## Cicatriz 5 — O risco não está apenas na resposta

### Problema

Inicialmente, a análise estava concentrada na qualidade da resposta produzida pela IA.

A fonte sobre uso responsável mostrou que existe outro aspecto fundamental: **as informações inseridas no próprio prompt também precisam ser avaliadas.**

O material recomenda não inserir dados pessoais, sensíveis, sigilosos ou informações internas do órgão.

### Solução

Antes de formular um prompt, passou-se a considerar:

```text
Qual é o objetivo?
      ↓
A IA é adequada para essa tarefa?
      ↓
Quais informações serão utilizadas?
      ↓
Existe dado pessoal ou sigiloso?
      ↓
É necessário anonimizar?
      ↓
Como a resposta será validada?
```

### Aprendizado

Engenharia de Prompts não significa apenas aprender a escrever melhores instruções.

Também significa aprender **quais informações podem ser fornecidas à IA e como o resultado deve ser utilizado**.

---

# 6. Uso responsável de IA

A fonte brasileira adicionada ao projeto apresenta três perguntas fundamentais:

### Como devo formular minha solicitação?

Utilizar comandos objetivos e evitar a inclusão de dados pessoais, sensíveis, sigilosos ou informações internas.

### Como devo usar a resposta gerada?

A resposta deve servir como apoio, sendo necessário verificar as informações, adaptar o conteúdo ao contexto e evitar sua reprodução automática.

### Como decidir se a IA é adequada?

A IA deve servir como apoio e não substituir o julgamento humano, especialmente em decisões estratégicas e atos administrativos.

---

# 7. Proteção de dados

Um dos principais aprendizados foi compreender que a segurança começa antes mesmo da geração da resposta.

A fonte recomenda evitar dados pessoais, sensíveis ou identificáveis e utilizar, quando possível, exemplos fictícios, informações públicas ou dados anonimizados.

Também recomenda não utilizar IA para tratar informações estratégicas, sigilosas ou protegidas por lei.

### Regra prática

Antes de enviar qualquer informação para uma IA:

> **Pergunte se aquela informação realmente precisa estar no prompt.**

Se não precisar, não inclua.

---

# 8. Revisão humana

A resposta da IA deve ser considerada um apoio.

O material estudado recomenda verificar as informações, ajustar o resultado ao contexto institucional e não reproduzir automaticamente o conteúdo gerado.

Também reforça que a responsabilidade pelo conteúdo continua sendo humana. A IA não substitui análise técnica, jurídica ou administrativa.

Isso leva a um princípio central deste projeto:

> **A IA pode auxiliar na produção de conteúdo, mas não elimina a necessidade de julgamento humano.**

---

# 9. Principais riscos identificados

## Vazamento de dados

Informações inseridas em prompts podem representar risco de exposição ou reprodução indevida.

## Uso malicioso

A IA pode ser utilizada para apoiar golpes digitais, phishing, deepfakes e outras formas de engenharia social.

## Obsolescência

O conhecimento disponível para determinado sistema pode não contemplar fatos recentes, mudanças legislativas ou mudanças de contexto posteriores aos dados utilizados em seu treinamento.

## Alucinações

A IA pode gerar informações incorretas, referências inexistentes ou interpretações inadequadas quando não possui dados confiáveis suficientes.

## Responsabilidade jurídica

A ferramenta não assume responsabilidade pelos erros produzidos. A responsabilidade legal e administrativa permanece com quem utiliza o sistema e com a instituição.

## Vieses

Respostas que parecem neutras e objetivas podem reproduzir vieses existentes nos dados e escolhas humanas envolvidos no desenvolvimento dos sistemas.

## Falta de transparência

Sistemas pouco explicáveis podem dificultar auditoria, rastreabilidade e prestação de contas.

## Contexto brasileiro

Sistemas de IA podem interpretar incorretamente elementos do contexto brasileiro, incluindo gírias, regionalismos e referências culturais.

---

# 10. Miniguia de estudo

## 10.1 O que é Inteligência Artificial?

Inteligência Artificial é um campo da computação dedicado ao desenvolvimento de sistemas capazes de realizar tarefas que normalmente exigem capacidades associadas à inteligência humana.

Entre essas tarefas estão:

- reconhecimento de padrões;
- classificação;
- previsão;
- compreensão de linguagem;
- tomada de decisão.

---

## 10.2 O que é Machine Learning?

Machine Learning, ou Aprendizado de Máquina, é uma abordagem na qual modelos aprendem padrões a partir de dados para realizar determinadas tarefas.

Exemplos:

- classificação;
- recomendação;
- previsão;
- reconhecimento de padrões.

---

## 10.3 O que é Deep Learning?

Deep Learning é uma abordagem de Machine Learning baseada principalmente em redes neurais com múltiplas camadas.

É utilizada em problemas que envolvem padrões complexos, como:

- visão computacional;
- reconhecimento de fala;
- processamento de linguagem natural;
- geração de conteúdo.

---

## 10.4 O que é IA Generativa?

IA Generativa é uma classe de sistemas capazes de gerar novos conteúdos a partir de padrões aprendidos durante seu treinamento.

Dependendo do sistema, esses conteúdos podem incluir:

- texto;
- código;
- imagens;
- áudio;
- vídeo.

---

## 10.5 O que são LLMs?

LLM significa **Large Language Model**, ou Grande Modelo de Linguagem.

São modelos desenvolvidos para trabalhar com linguagem e podem executar tarefas como:

- responder perguntas;
- resumir textos;
- traduzir;
- gerar conteúdo;
- auxiliar em programação;
- transformar informações de acordo com instruções.

---

## 10.6 O que é Transformer?

Transformer é uma arquitetura apresentada no artigo **Attention Is All You Need**, publicado em 2017.

A arquitetura utiliza mecanismos de atenção para trabalhar com relações entre diferentes partes de uma sequência.

O Transformer tornou-se uma referência importante para o desenvolvimento de modelos modernos de linguagem.

---

## 10.7 O que é Prompt?

Um prompt é uma instrução ou entrada fornecida a um modelo de IA para orientar sua resposta.

Pode conter:

- pergunta;
- instrução;
- contexto;
- exemplos;
- restrições;
- formato esperado.

---

## 10.8 O que é Engenharia de Prompts?

Engenharia de Prompts é o processo de criar, testar e aperfeiçoar instruções para obter resultados mais úteis e adequados ao objetivo.

Um prompt pode especificar:

1. o que deve ser feito;
2. qual contexto deve ser considerado;
3. para quem a resposta será destinada;
4. como a resposta deve ser estruturada;
5. quais restrições devem ser respeitadas.

---

## 10.9 Zero-shot, One-shot e Few-shot

### Zero-shot

A tarefa é apresentada sem exemplos.

### One-shot

A tarefa é apresentada com um exemplo.

### Few-shot

A tarefa é apresentada com vários exemplos.

Essas estratégias podem ser utilizadas para orientar o modelo quanto à tarefa e ao formato esperado.

---

## 10.10 Alucinações

Uma alucinação ocorre quando a IA produz uma informação incorreta ou sem suporte adequado, mas apresenta essa informação de maneira plausível.

Por isso:

> **Uma resposta bem escrita não é necessariamente uma resposta verdadeira.**

A fonte estudada também destaca que a IA pode inventar informações, referências legais ou interpretações incorretas.

---

## 10.11 Vieses

Respostas de IA podem refletir vieses existentes nos dados e nas escolhas humanas envolvidas no desenvolvimento dos modelos.

A fonte analisada chama atenção para o risco de falsa neutralidade e reprodução de desigualdades.

---

## 10.12 IA responsável

O uso responsável de IA envolve aspectos como:

- segurança;
- privacidade;
- transparência;
- confiabilidade;
- revisão humana;
- proteção de dados;
- responsabilidade;
- avaliação de riscos.

---

# 11. Glossário

| Conceito | Definição |
|---|---|
| **IA** | Campo da computação relacionado à criação de sistemas capazes de executar tarefas associadas à inteligência. |
| **Machine Learning** | Abordagem na qual modelos aprendem padrões a partir de dados. |
| **Deep Learning** | Abordagem baseada principalmente em redes neurais profundas. |
| **IA Generativa** | IA capaz de gerar novos conteúdos. |
| **LLM** | Large Language Model, modelo de linguagem de grande escala. |
| **Transformer** | Arquitetura baseada em mecanismos de atenção. |
| **Prompt** | Instrução ou entrada fornecida ao modelo. |
| **Prompt Engineering** | Processo de criação e refinamento de prompts. |
| **Zero-shot** | Execução de tarefa sem exemplos no prompt. |
| **One-shot** | Execução de tarefa com um exemplo. |
| **Few-shot** | Execução de tarefa com vários exemplos. |
| **Alucinação** | Geração de informação incorreta ou sem suporte adequado. |
| **Viés** | Tendência sistemática que pode afetar resultados. |
| **Anonimização** | Remoção ou transformação de informações que permitam identificar uma pessoa. |
| **Rastreabilidade** | Capacidade de acompanhar registros e etapas de determinado processo. |
| **Transparência** | Clareza sobre a utilização e origem de determinado conteúdo. |
| **Responsabilidade humana** | Princípio de que o uso de IA não elimina a responsabilidade de quem utiliza e valida seus resultados. |
| **Risco jurídico** | Possibilidade de consequências legais ou administrativas decorrentes do uso inadequado de IA. |
| **Contexto institucional** | Regras, objetivos, responsabilidades e características específicas de uma organização. |

---

# 12. Prompts reutilizáveis

## Prompt 1 — Resumo

> Com base nas fontes disponíveis, faça um resumo estruturado sobre **[TEMA]**. Organize em definição, conceitos fundamentais, aplicações, benefícios, limitações e pontos que merecem atenção. Utilize linguagem adequada para um estudante iniciante.

---

## Prompt 2 — Explicação progressiva

> Explique **[CONCEITO]** em dois níveis. Primeiro, explique como se eu estivesse começando a estudar o assunto. Depois, apresente uma explicação de nível intermediário. Utilize exemplos práticos e destaque as diferenças entre os dois níveis.

---

## Prompt 3 — Comparação

> Compare **[CONCEITO A]**, **[CONCEITO B]** e **[CONCEITO C]**. Crie uma tabela contendo definição, objetivo, aplicações, vantagens, limitações e relação entre eles. Utilize somente as fontes disponíveis.

---

## Prompt 4 — Revisão para prova

> Crie 10 perguntas de revisão sobre **[TEMA]**, começando pelas mais fáceis e aumentando gradualmente a dificuldade. Não apresente as respostas imediatamente. Depois que eu responder, avalie minhas respostas utilizando as fontes disponíveis.

---

## Prompt 5 — Identificação de lacunas

> Analise minha explicação sobre **[TEMA]** e identifique quais conceitos importantes estão ausentes, quais afirmações precisam ser corrigidas e quais pontos deveriam ser aprofundados. Baseie sua análise nas fontes disponíveis.

---

## Prompt 6 — Aprendizagem ativa

> Não me dê a resposta imediatamente. Faça uma pergunta sobre **[TEMA]**, aguarde minha tentativa de resposta e depois forneça feedback. Explique o que acertei, o que errei e qual conceito devo revisar.

---

## Prompt 7 — Verificação de confiabilidade

> Analise a afirmação abaixo: **[AFIRMAÇÃO]**. Verifique se ela é sustentada pelas fontes disponíveis. Classifique-a como “sustentada”, “parcialmente sustentada”, “não sustentada” ou “inconclusiva”. Explique o motivo e indique a fonte utilizada.

---

## Prompt 8 — Revisão final

> Faça uma revisão completa do meu conhecimento sobre **[TEMA]**. Primeiro, apresente os 10 conceitos que eu obrigatoriamente deveria dominar. Depois, faça cinco perguntas para testar minha compreensão. Ao final, indique quais assuntos devo revisar novamente com base nos meus erros.

---

## Prompt 9 — Avaliação de segurança

> Antes de responder à minha solicitação, analise se as informações fornecidas podem conter dados pessoais, sensíveis, sigilosos ou informações internas. Caso exista algum risco, identifique o tipo de informação que deveria ser removida, anonimizada ou substituída por um exemplo fictício. Não reproduza os dados potencialmente sensíveis na resposta.

---

## Prompt 10 — Revisão humana

> Analise o conteúdo abaixo e identifique quais informações precisam ser verificadas por um profissional antes de serem utilizadas. Classifique os pontos em: factual, técnico, jurídico, administrativo ou opinativo. Não considere a resposta da IA como fonte definitiva.

---

## Prompt 11 — Análise de risco

> Analise esta tarefa de acordo com quatro dimensões: proteção de dados, confiabilidade das informações, riscos jurídicos e necessidade de julgamento humano. Para cada dimensão, indique possíveis riscos e medidas de prevenção. Ao final, diga se a IA deve ser utilizada apenas como apoio ou se a tarefa deveria ser realizada sem IA.

---

# 13. Principais aprendizados

## 1. A qualidade da pergunta influencia o resultado

Uma pergunta vaga pode gerar uma resposta genérica.

Adicionar contexto, objetivo e formato esperado torna a solicitação mais direcionada.

## 2. IA não substitui a fonte

A IA pode facilitar a compreensão de um documento, mas a fonte original continua sendo importante para verificar informações.

## 3. Prompt Engineering é iterativo

O processo pode ser representado por:

```text
Criar prompt
     ↓
Observar resposta
     ↓
Identificar problema
     ↓
Modificar prompt
     ↓
Testar novamente
     ↓
Avaliar resultado
```

## 4. Contexto faz diferença

Informar objetivo, público, restrições e formato esperado ajuda a produzir respostas mais úteis.

## 5. Segurança começa no prompt

Não basta verificar a resposta.

Também é necessário avaliar quais informações estão sendo enviadas à ferramenta.

## 6. Pensamento crítico continua sendo essencial

Mesmo com ferramentas avançadas, é necessário questionar:

- A informação possui fonte?
- A fonte é confiável?
- A resposta está dentro do contexto?
- Existem evidências?
- Existe possibilidade de erro?
- A conclusão realmente decorre das fontes?
- As informações utilizadas no prompt poderiam ser sensíveis?

---

# 14. Conclusão

O uso do NotebookLM neste projeto mostrou que ferramentas de Inteligência Artificial podem ser utilizadas não apenas para obter respostas, mas também para estruturar um processo de aprendizagem.

A principal mudança de perspectiva foi compreender que uma interação produtiva com IA depende de uma combinação entre:

**boa curadoria + boas perguntas + experimentação + verificação + segurança + pensamento crítico.**

A inclusão do material brasileiro sobre uso responsável da IA ampliou ainda mais essa visão.

Inicialmente, o foco estava em compreender:

> **Como obter uma resposta melhor da IA?**

Ao longo do projeto, surgiu uma pergunta igualmente importante:

> **Devo utilizar IA para esta tarefa e, caso utilize, como fazer isso de maneira segura e responsável?**

Portanto, o uso consciente de IA envolve três níveis:

### 1. Saber perguntar

Criar prompts claros, objetivos e contextualizados.

### 2. Saber avaliar

Verificar respostas, fontes, limitações, possíveis vieses e atualidade.

### 3. Saber decidir

Determinar quando a IA é apropriada, quais informações podem ser compartilhadas e quando a decisão deve permanecer sob responsabilidade humana.

A IA pode acelerar processos de aprendizagem e produção, mas seu uso exige participação ativa do usuário.

> **Aprender com IA não significa aceitar respostas prontas. Significa saber perguntar, investigar, comparar, validar e transformar informação em conhecimento.**

---

# 15. Próximos passos

Como continuidade deste projeto, os próximos estudos planejados são:

- aprofundar o funcionamento dos Transformers;
- estudar embeddings;
- compreender representação vetorial;
- estudar RAG (Retrieval-Augmented Generation);
- estudar avaliação de LLMs;
- explorar agentes de IA;
- aprofundar conceitos de IA responsável;
- aplicar Engenharia de Prompts em projetos práticos;
- construir pequenos projetos utilizando APIs de modelos de IA.

---

# 🔗 16. Referências

1. **NIST** — Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile  
   https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence

2. **Stanford HAI** — AI Index Report  
   https://hai.stanford.edu/ai-index

3. **Google Cloud** — Prompt Engineering: Overview and Guide  
   https://cloud.google.com/discover/what-is-prompt-engineering

4. **Google for Developers** — Machine Learning Glossary: Generative AI  
   https://developers.google.com/machine-learning/glossary/generative

5. **Vaswani et al.** — Attention Is All You Need  
   https://arxiv.org/abs/1706.03762

6. **Guia Prático para o Uso Responsável da Inteligência Artificial (IA) Generativa no Dia a Dia do Serviço Público**  
   Arquivo utilizado no projeto: `infograficos_defeso.pdf`  
   https://www.gov.br/governodigital/pt-br/infraestrutura-nacional-de-dados/inteligencia-artificial-1/publicacoes/guia-ia-generativa

---

# Resultado

Este repositório documenta não apenas o conteúdo estudado, mas também o **processo de aprendizagem com Inteligência Artificial**, incluindo:

- curadoria de fontes;
- utilização do NotebookLM;
- experimentação de prompts;
- identificação de problemas;
- refinamento das perguntas;
- análise de riscos;
- proteção de dados;
- revisão humana;
- consolidação do conhecimento;
- criação de prompts reutilizáveis.

O projeto demonstra que a IA pode ser utilizada como uma ferramenta de aprendizagem ativa quando combinada com **curadoria, pensamento crítico, validação e responsabilidade**.
