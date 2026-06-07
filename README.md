# CloudSales AI

CloudSales AI é um Copiloto de Vendas com IA criado para apoiar freelancers, agências e pequenos negócios no atendimento comercial.

O projeto foi desenvolvido como parte de um desafio prático de IA aplicada a vendas.

## Problema

Muitos freelancers sabem criar bons serviços digitais, mas têm dificuldade para vender, qualificar clientes e responder objeções.

Esse copiloto ajuda o vendedor a:

* Entender o interesse do cliente
* Fazer perguntas de qualificação
* Sugerir ofertas adequadas
* Identificar oportunidades de upsell
* Responder objeções
* Criar mensagens prontas para WhatsApp

## Abordagem

A solução usa uma estrutura de copiloto multiagente com três papéis principais:

### Agente Qualificador

Analisa o interesse do cliente e identifica o potencial da venda.

### Agente Vendedor

Sugere a melhor oferta com base na necessidade do cliente.

### Agente Fechador

Ajuda a responder objeções e orientar o próximo passo.

## Serviços considerados

* Landing page
* Site institucional
* Página com agendamento
* Sistema web simples
* Automação com IA
* Consultoria cloud
* Manutenção mensal

## Estrutura do projeto

```txt
cloudsales-ai/
  README.md
  AGENTS.md
  prompts/
    prompt-principal.md
    agente-qualificador.md
    agente-vendedor.md
    agente-fechador.md
  knowledge/
    servicos.md
    objecoes.md
    perguntas-frequentes.md
    exemplos.md
```

## Exemplo de uso

Entrada:

```txt
Cliente quer uma página para divulgar serviços de massagem e receber agendamentos pelo WhatsApp.
```

Saída esperada:

* Diagnóstico do lead
* Perguntas para qualificação
* Oferta recomendada
* Complementos possíveis
* Objeções prováveis
* Mensagem pronta para WhatsApp

## Melhorias futuras

* Criar interface web com Next.js
* Conectar com API de IA
* Salvar histórico de leads
* Gerar propostas comerciais automaticamente
* Integrar com WhatsApp Business
* Criar painel para acompanhar oportunidades

