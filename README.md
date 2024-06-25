# Criando um Podcast

Repositório para agregar o projeto de podcast do Bootcamp Santander DIO AI para Devs

## Objetivo do projeto

1. Objetivo principal: produzir um Podcast.
2. Objetivos secundários: criar uma autoridade no mundo tech, não precisa expor a imagem; apreciado por quem não gosta de consumir conteúdos em forma de artigo, uma estratégia de destaque no mercado.

## Conceitos necessários para o projeto

### Prompt Engineering

:closed_book: Referência: [Podcast Studio](https://helpful-jum17b.notion.site/PAS-Podcast-AI-Studio-210489e15d7a4a73b743bb159e45d06f)

 >Arte e ciência de criar mensagens claras para comupatadores que estranham a melhor reposta efetiva.

### Como escrever prompts mais profissionais?

- **Regra de ouro**: Quanto mais específico melhor!

>Essa regra funciona para qualquer IA que gera conteúdos a partir de prompts.

- Criar o cenário do problema: Contextualizar o cenário e apresentar as preocupações existente.

- Solicitar resolução de um problemad inserido em um contexto prático: Aplicabilidade do problema.

- Comunicação clara e natural: Usar uma comunicação mais natural, como você trata um ser humano.

- **Prompts negativos**

Consiste em descrever de forma clara o que você não quer como resposta para a questão.

- **Passagem variáveis (prompt pattern)**

Padrões: área de substinuição "NOME?" substituir por Felipe
>Essa estratégia é muito utilizada para criar bancos de dados fake. Bloco de variáveis que depois será susbituido.

``` Prompt original: "Olá, [NOME]! Como posso te ajudar hoje? ```

[!Note]
Como o nome não está indicado, haver troca da variável a cada resposta gerada.

### Gerando prompt de imagem

[O que voce quer] + palavras de configurações da imagem e filtro

### Definição de um grupo

Para melhor alcance do podcas é importante adotar um nicho de atuação. Considere que um tema amplo, precisa de um refinamento da abrangência do tema.

## Criando o Podcast

### Título do podcast

**Prompt do nome do podcast** -Você é um roteirista de podcast e vamos criar um podcast de saude pública focado em orientações sobre núcleo de prevenção a violência; e eu gostaria de uma ajuda sua para criar 5 sugestões de nomes criativos para um podcast de saúde pública feito por uma enfermeira especializada em educação, que passe uma vertende educacional.
O podcast vai falar sobre a abordagem e escuta qualificada de pessoas vítimas de violência
REGRAS:
>nome deve ser enxuto;
>nome e subtítulo
>nome com referência a educação
>referencia a proteção
>referencia ao atendimento multiprofissional

REGRAS NEGATIVAS:
>não quero que use palavras em inglês
>não utilize a palavra enfermagem

Resultado selecionado: *Cuidado em Foco: Proteção e Apoio Integral às Vítimas de violência*

[!NOTE]
O nome pode remeter já o conteúdo que será mais trabalhado.

### Criando personagem apresentador

Prompt:
Black womam, with blackpower hair, use colorful clothes. photografic realistc, 8mm lents, backstage beautiful library

### Criando o Prompt do conteúdo

Voce é um roteirita de podcast, vamos criar o roteiro de podcast cujo o nome é Cuidado em Foco
Subtítulo: Proteção e Apoio Integral às Vítimas de violência, vamos focar no atendimento multiprofissional do acolhimento de pessoas vítimas de violência, escuta qualificada.

- Formato do roteiro:
[INTRODUÇÃO]
[SITUAÇÃO1]
[SITUAÇÃO2]
[FINALIZAÇÃO]

{REGRAS}

- no bloco [INTRODUÇÃO] substitua por uma introdução como no podcast do Mamilos, como a Cris Bastos costuma apresentar.
- no bloco de [SITUAÇÃO1] sempre substitua por um tipo de violência comum
- no bloco de [SITUAÇÃO2] substitua por uma forma apropriada de acolhimento
- no bloco de [FINALIZAÇÃO] subistitua por fortalecimento da equipe multiprofissional e acolhimento e termine com um agradecimento
- use termos sensíveis e respeitosos
- o podcast vai ser apresentado somente por uma pessoa, chamada Maria
- o podcast deve ser curto

{REGRAS NEGATIVAS}

- não explorar com detalhes as violências
- não ultrapassar 5 minutos de duração
