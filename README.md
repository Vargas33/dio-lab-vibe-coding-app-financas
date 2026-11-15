# 💸 App de Organização de Finanças Pessoais com Vibe Coding para ampliar estudos de Marcelo Barreto

PRD refinado no Copilot Web

```markdown
## Visão Geral

### Nome do Produto
Finanças Pessoais

### Proposta de Valor

Finanças Pessoais é um aplicativo de gestão financeira pessoal baseado em inteligência artificial conversacional.

O objetivo é permitir que qualquer pessoa organize sua vida financeira de forma simples e intuitiva, sem depender de planilhas, formulários complexos ou conhecimentos avançados de finanças.

O usuário interage com um assistente financeiro através de linguagem natural para registrar movimentações, acompanhar metas, controlar cartões, monitorar dívidas e receber recomendações personalizadas.

---

## Problema

Muitas pessoas abandonam o controle financeiro porque os aplicativos atuais:

- Exigem muito preenchimento manual
- Possuem interfaces complexas
- São difíceis para iniciantes
- Não oferecem orientação personalizada
- Exigem conhecimento financeiro básico

Como consequência, usuários perdem controle dos gastos, acumulam dívidas e não conseguem atingir metas financeiras.

---

## Solução

Criar uma experiência conversacional onde o usuário apenas descreve o que aconteceu e o sistema interpreta automaticamente.

Exemplos:

- Gastei R$ 50 no mercado
- Recebi R$ 4.500 de salário
- Comprei um celular de R$ 2.000 em 10 parcelas
- Tenho uma dívida de R$ 5.000
- Quanto gastei este mês?

O sistema deve compreender a intenção, registrar as informações e atualizar automaticamente os relatórios financeiros.

---

## Público-Alvo

### Perfil Principal

Pessoas que:

- Estão começando a organizar suas finanças
- Nunca utilizaram planilhas financeiras
- Possuem pouco conhecimento financeiro
- Buscam praticidade
- Querem economizar dinheiro
- Possuem cartões de crédito, parcelas e dívidas
- Utilizam aplicativos de mensagens diariamente

### Faixa Etária

18 a 55 anos

### Nível de Conhecimento Financeiro

Iniciante a intermediário

---

## Objetivos do Produto

### Objetivos do Usuário

- Controlar gastos sem esforço
- Entender para onde o dinheiro está indo
- Acompanhar cartões e faturas
- Organizar dívidas e parcelamentos
- Criar metas financeiras
- Receber sugestões para economizar

### Objetivos do Negócio

- Aumentar frequência de uso através do chat
- Reduzir a complexidade da gestão financeira
- Melhorar a retenção de usuários iniciantes
- Criar uma experiência altamente personalizada

---

# Funcionalidades do MVP

## 1. Chat Financeiro Inteligente

Funcionalidade principal do aplicativo.

Exemplos:

- Gastei R$ 75 no mercado
- Recebi R$ 1.000 de um freelance
- Quanto gastei em alimentação este mês?
- Tenho uma dívida de R$ 2.000
- Minha fatura está alta?

Responsabilidades da IA:

- Entender a intenção da mensagem
- Extrair valores monetários
- Identificar categorias
- Detectar datas
- Registrar movimentações
- Responder consultas financeiras

---

## 2. Registro de Receitas

Exemplos:

- Recebi meu salário de R$ 4.500
- Entrou R$ 300 via PIX
- Recebi R$ 800 de um trabalho extra

Dados:

- Valor
- Descrição
- Data
- Categoria

---

## 3. Registro de Despesas

Exemplos:

- Gastei R$ 50 no restaurante
- Uber R$ 25
- Mercado R$ 300

Dados:

- Valor
- Categoria
- Descrição
- Data

---

## 4. Classificação Automática

Categorias:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Assinaturas
- Investimentos
- Cartão de Crédito
- Dívidas
- Outros

Regra:
Quando houver dúvida, solicitar confirmação ao usuário.

---

## 5. Metas Financeiras

Permitir:

- Criar metas
- Editar metas
- Excluir metas
- Acompanhar evolução

Dados:

- Nome
- Valor objetivo
- Valor atual
- Prazo

Visualização:

- Percentual concluído
- Valor acumulado
- Valor restante

---

## 6. Agente Financeiro

Assistente virtual responsável por:

- Analisar hábitos financeiros
- Detectar gastos excessivos
- Identificar padrões
- Gerar recomendações
- Alertar vencimentos

Exemplos:

- Você gastou 20% mais em alimentação este mês
- Seu cartão está utilizando 80% do limite
- Existem parcelas vencendo nos próximos dias
- É possível economizar R$ 100 reduzindo gastos com delivery

---

## 7. Relatórios Inteligentes

Consultas:

- Quanto gastei este mês?
- Onde gasto mais?
- Quanto recebi?
- Quanto ainda devo?
- Quanto falta para minha meta?

Exibir:

- Texto
- Cards
- Gráficos simples

---

## 8. Cartões de Crédito

Permitir cadastro de múltiplos cartões.

Dados:

- Nome do cartão
- Banco
- Bandeira
- Limite total
- Limite disponível
- Dia de fechamento
- Dia de vencimento

Visualizações:

- Limite utilizado
- Limite restante
- Percentual utilizado

---

## 9. Faturas

Controlar automaticamente as faturas dos cartões.

Status:

- Aberta
- Fechada
- Paga
- Atrasada

Visualizações:

- Valor total
- Vencimento
- Histórico
- Compras da fatura

Consultas:

- Quanto está minha fatura?
- Quando vence?
- O que compõe minha fatura?

---

## 10. Parcelas

Registrar compras parceladas.

Exemplos:

- Celular de R$ 2.000 em 10x
- Notebook de R$ 5.000 em 12x

Visualizações:

- Parcela atual
- Parcelas restantes
- Valor restante
- Próximos vencimentos

---

## 11. Dívidas

Controlar:

- Empréstimos
- Financiamentos
- Dívidas pessoais
- Dívidas de cartão

Visualizações:

- Valor total
- Valor pago
- Valor restante
- Percentual quitado

---

# Autenticação e Segurança

## Funcionalidades

- Cadastro por e-mail e senha
- Login por e-mail e senha
- Recuperação de senha
- Verificação obrigatória de e-mail
- Logout seguro

## Login Social

- Google
- Microsoft
- Apple

## Segurança

- HTTPS
- JWT
- Sessões persistentes
- Proteção de rotas
- Row Level Security (RLS)

Regra:

Cada usuário pode acessar apenas os próprios dados.

---

# Fluxo de Onboarding

## Etapa 1

Nome do usuário

## Etapa 2

Objetivo financeiro principal

Opções:

- Economizar dinheiro
- Sair das dívidas
- Fazer uma viagem
- Comprar um imóvel
- Criar reserva de emergência
- Investir

## Etapa 3

Faixa de renda mensal (opcional)

## Etapa 4

Criar primeira meta financeira

---

# Telas do Sistema

1. Splash Screen
2. Boas-vindas
3. Login
4. Cadastro
5. Recuperação de Senha
6. Onboarding
7. Dashboard
8. Chat Financeiro
9. Cartões
10. Faturas
11. Parcelas
12. Dívidas
13. Metas
14. Insights
15. Perfil
16. Configurações

---

# Dashboard

Resumo financeiro contendo:

- Saldo atual
- Receitas do mês
- Despesas do mês
- Dívidas totais
- Faturas abertas
- Metas financeiras

Gráficos:

- Gastos por categoria
- Evolução mensal
- Receitas x despesas
- Comprometimento financeiro

---

# Banco de Dados

## profiles

- id
- nome
- email
- objetivo_financeiro
- faixa_renda
- onboarding_concluido
- created_at

## transactions

- id
- user_id
- tipo
- valor
- categoria
- descricao
- data

## cards

- id
- user_id
- nome
- banco
- bandeira
- limite_total
- limite_disponivel
- dia_fechamento
- dia_vencimento

## invoices

- id
- card_id
- valor_total
- data_fechamento
- data_vencimento
- status

## installments

- id
- user_id
- descricao
- valor_total
- valor_parcela
- total_parcelas
- parcela_atual
- status

## debts

- id
- user_id
- origem
- valor_total
- valor_pago
- valor_restante
- status

## goals

- id
- user_id
- nome
- valor_meta
- valor_atual
- prazo
- status

## insights

- id
- user_id
- titulo
- descricao
- tipo
- created_at

---

# Stack Tecnológica

Frontend:

- React
- TypeScript
- Tailwind CSS
- Shadcn UI

Backend:

- Supabase

Banco de Dados:

- PostgreSQL (Supabase)

Autenticação:

- Supabase Auth

IA:

- OpenAI API

---

# Diretrizes de Design

- Mobile First
- Interface moderna e minimalista
- Fácil para iniciantes
- Inspirada em aplicativos financeiros modernos
- Navegação simples
- Componentes acessíveis
- Uso de cards para informações financeiras
- Experiência semelhante a aplicativos de mensagens

---

# Critérios de Sucesso do MVP

- 70% dos usuários registram uma movimentação na primeira sessão
- 40% retornam após 7 dias
- 85% das transações são categorizadas corretamente
- 50% dos usuários criam ao menos uma meta financeira
- Usuário consegue registrar uma movimentação em menos de 10 segundos

---

# Requisitos para o Lovable

Gerar uma aplicação completa utilizando:

- React
- TypeScript
- Supabase
- Tailwind CSS
- Shadcn UI

Implementar:

- Banco de dados
- Autenticação
- Navegação
- Componentes
- Chat Financeiro
- Dashboard
- Metas
- Cartões
- Faturas
- Parcelas
- Dívidas
- Insights
- Integração com OpenAI
- Segurança com RLS

A arquitetura deve ser escalável e preparada para futuras integrações com Open Finance e sincronização bancária.

```

 Interações com Lovable:
 
> Crie App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> O Finanças Pessoais está pronto. Testei o caminho principal no celular: fiz o onboarding, mandei "Gastei R$ 50 no mercado" no chat e o assistente registrou em Alimentação. Depois respondi "Quanto gastei este mês?" com o valor certo, e o painel mostrou o gasto.
> Favor alterar o logo e cor para um roxo vivo e moderno (claro, vou substituir o logo e a cor para um roxo.

Resultado final no Lovable:  https://papo-de-gastos-diarios.lovable.app

- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
