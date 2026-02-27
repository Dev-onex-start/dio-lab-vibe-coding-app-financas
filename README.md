# App de Finanças Pessoais com Vibe Coding — Lucas Adriano
Este projeto foi desenvolvido como um desafio da DIO de Vibe Coding, utilizando Lovable e GPT web. A proposta é criar um aplicativo de controle financeiro pessoal baseado em interações por linguagem natural

## PRD refinado com ChatGPT (Web)

```markdown
Crie um app de finanças pessoais com base no seguinte PRD (Product Requirement Document):

PRD — Aplicativo de Finanças Conversacional

Nome do Projeto

O sistema deve permitir alteração fácil do nome via configuração.

Sugestões:
- Grana.ai
- Controlinho
- DinDin

Visão do Produto

Criar um aplicativo de organização financeira pessoal que funcione principalmente por meio de conversas em linguagem natural, permitindo registrar gastos, receitas e metas de forma simples, acessível e inclusiva.

O produto deve ser amigável para iniciantes, pessoas com baixa familiaridade tecnológica e usuários com limitações motoras, oferecendo entrada por voz e interface simplificada.

Problema

Muitas pessoas desistem de controlar suas finanças porque aplicativos existentes exigem preenchimento manual excessivo, interfaces complexas ou conhecimento financeiro prévio.

O objetivo é reduzir fricção usando conversa natural e automação inteligente.

Público-Alvo

- Iniciantes em finanças pessoais  
- Pessoas que abandonaram apps financeiros  
- Usuários com pouca experiência digital  
- Idosos  
- Pessoas com limitações motoras  
- Usuários que preferem praticidade  

Proposta de Valor

Organizar a vida financeira conversando, de forma simples, rápida e sem julgamento.

Personalidade da Marca

- Simples  
- Confiável  
- Amigável  
- Motivadora  
- Educativa  
- Acolhedora  

O usuário não deve sentir culpa ao registrar gastos.

Tom emocional:
"Estou aqui para ajudar, não para cobrar."

Funcionalidades Principais (MVP)

Registro de Transações por Conversa

Usuário pode digitar ou falar frases como:
"Gastei 30 reais com almoço"  
"Recebi 1200 de salário"  
"Paguei 50 de internet ontem"

O sistema deve:
- Identificar valor  
- Identificar tipo (receita ou despesa)  
- Sugerir categoria  
- Confirmar com o usuário  

Entrada por Voz

Deve existir:
- Botão de microfone grande  
- Conversão voz para texto  
- Feedback visual de gravação  

Objetivo: acessibilidade e facilidade de uso.

Classificação Automática

Categorias iniciais:
- Alimentação  
- Transporte  
- Moradia  
- Lazer  
- Saúde  
- Contas  
- Outros  

Usuário pode editar categorias.

Metas Financeiras

Exemplos:
"Quero economizar 500 reais"  
"Meta de emergência 1000"  
"Quero juntar para um celular"

O sistema acompanha o progresso.

Relatórios Simples

Exibir:
- Total gasto  
- Total recebido  
- Saldo atual  
- Principais categorias  

Com gráficos simples e claros.

Agente Financeiro Inteligente

Fornecer:
- Alertas de gasto  
- Sugestões de economia  
- Progresso de metas  
- Insights periódicos  

Tom amigável e motivador.

Telas do MVP

Tela Boas-Vindas
- Nome do aplicativo  
- Slogan  
- Botão "Começar"  

Tela Chat Principal
Componentes:
- Histórico de mensagens  
- Campo de texto grande  
- Botão de microfone  
- Botão enviar  
- Sugestões rápidas  

Tela Resumo Financeiro
- Saldo atual  
- Receitas  
- Gastos  
- Gráfico  

Tela Metas
- Lista de metas  
- Progresso visual  
- Criar nova meta  

Tela Perfil / Configurações
- Nome  
- Preferências  
- Configurações de acessibilidade  
- Opções de voz  

Design Universal e Acessibilidade

Visual:
- Fonte grande  
- Alto contraste  
- Botões grandes  
- Ícones claros  

Cognitivo:
- Linguagem simples  
- Feedback imediato  
- Pouco texto  

Motor:
- Poucos cliques  
- Botões grandes  
- Entrada por voz  

Baixa escolaridade:
- Exemplos de frases  
- Sugestões prontas  
- Ícones com texto  

Recursos Técnicos Sugeridos

Frontend:
- React ou Next.js  

Backend:
- Node.js ou Supabase  

Banco:
- PostgreSQL ou Firebase  

IA:
- API de linguagem natural  

Voz:
- Web Speech API inicialmente  

Estrutura de Dados

Usuários:
- id  
- nome  
- email  

Transações:
- id  
- user_id  
- tipo  
- valor  
- categoria  
- data  
- descricao  

Metas:
- id  
- user_id  
- nome  
- valor_objetivo  
- valor_atual  

Evolução Futura

Portfólio:
- PWA  
- Tema escuro  
- Exportar relatórios  
- Dashboard avançado  

Diferencial Estratégico

Inclusão financeira com interface conversacional e acessível.

Requisitos de Código

- Código modular  
- Componentização clara  
- Comentários explicativos  
- Estrutura escalável  

Paleta de Cores Profissional

Primária:
#4CAF50

Secundária:
#2D9CDB

Neutros:
#FFFFFF  
#F5F7FA  
#E0E0E0  
#333333  

Feedback:
Sucesso: #27AE60  
Alerta: #F2C94C  
Erro: #EB5757  

Conceito de Logo

Ideia 1: Cofrinho minimalista com balão de conversa  
Ideia 2: Símbolo de moeda formando um chat bubble  
Ideia 3: Robô financeiro simples com sorriso  

Estilo: Flat Design moderno e amigável
```

---

## Interações com o Lovable

> Crie um app de finanças pessoais com base no seguinte PRD (Product Requirement Document).
> Habilite o Lovable Cloud.
> Integre IA conversacional real ao chat do Grana.ai usando Lovable AI para interpretar mensagens financeiras em linguagem natural.

## Resultado final no Lovable

[https://grana-ai-meu-money.lovable.app](https://grana-ai-meu-money.lovable.app)

<img width="1360" height="723" alt="image" src="https://github.com/user-attachments/assets/d500b746-ea70-44e0-8d62-88a210ee9a26" />
<img width="1360" height="614" alt="image" src="https://github.com/user-attachments/assets/572367df-70dc-4dbf-9a78-b02d8d8feb99" />
<img width="1360" height="617" alt="image" src="https://github.com/user-attachments/assets/b0a1e564-58f1-446b-ac1a-36f3df84f9d2" />


---

# Grana.ai — Aplicativo de Finanças Conversacional

Aplicativo de organização financeira pessoal baseado em conversas em linguagem natural.

O objetivo é permitir que usuários registrem gastos, receitas e metas financeiras de forma simples, rápida e acessível, sem necessidade de planilhas ou formulários complexos.

## Problema

Muitas pessoas desistem de controlar suas finanças devido à complexidade dos aplicativos existentes.

Este projeto busca resolver esse problema por meio de uma experiência conversacional intuitiva.

## Funcionalidades do App

* Registro de gastos por texto ou voz
* Classificação automática de transações
* Metas financeiras
* Relatórios simples
* Agente financeiro com dicas inteligentes
* Interface acessível

## Tecnologias

* Frontend: React / Next.js
* Estilização: Tailwind CSS
* Backend: Supabase
* Banco de dados: PostgreSQL
* IA: API de linguagem natural
* Voz: Web Speech API

## Objetivo Acadêmico

Projeto desenvolvido como parte dos meus estudos em desenvolvimento web e aplicações com IA.

## Diferenciais

* Interface conversacional
* Inclusão digital
* Acessibilidade
* Design universal

## Status

Em desenvolvimento (MVP)

## Autor

Lucas Adriano

## Reflexão

### O que funcionou bem?

O processo de refinamento do PRD com auxílio da IA foi um grande diferencial. A clareza na definição das funcionalidades facilitou a construção do projeto. Mesmo com créditos limitados no Lovable, foi possível validar o conceito principal.

### O que não funcionou como o esperado?

Algumas partes do aplicativo ainda precisam de melhorias, como trechos do painel de configurações que apresentaram inatividade. Além disso, as limitações de créditos no Lovable impactaram o aprofundamento de algumas funcionalidades.

### O que aprendi sobre conversar com IAs?

Aprendi que a qualidade do resultado está diretamente ligada à clareza do prompt. Refinar o PRD antes da execução acelerou o desenvolvimento e trouxe mais organização ao projeto. A engenharia de prompt se mostrou uma habilidade estratégica dentro do conceito de Vibe Coding.
