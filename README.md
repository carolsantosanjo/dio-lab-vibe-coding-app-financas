# 💸 App de Organização de Finanças Pessoais com Vibe Coding

PRD refinado com Copilot Web:

```markdown
# PRD v2.0 - Copiloto Financeiro Pessoal Conversacional

## 1. Visão do Produto

Criar uma aplicação de finanças pessoais baseada em conversas por linguagem natural que funcione como um Copiloto Financeiro Pessoal.

O sistema deve ajudar usuários a registrar movimentações financeiras, compreender hábitos de consumo, acompanhar metas, planejar o futuro e receber orientações personalizadas de forma simples e acessível.

A interação principal deve ocorrer através de um chat conversacional, minimizando a necessidade de formulários manuais.

O produto deve seguir princípios de Design Universal, garantindo uma experiência intuitiva, acessível e agradável para o maior número possível de usuários.

---

## 2. Problema

Muitas pessoas desejam controlar melhor suas finanças, mas desistem devido a:

- Complexidade dos aplicativos existentes.
- Necessidade excessiva de preenchimento manual.
- Falta de orientação personalizada.
- Dificuldade para interpretar dados financeiros.
- Baixa visibilidade sobre cartão de crédito, parcelamentos e compromissos futuros.

Como consequência:

- Não sabem para onde o dinheiro está indo.
- Não conseguem planejar gastos futuros.
- Possuem dificuldade para atingir objetivos financeiros.

---

## 3. Objetivos do Produto

Permitir que qualquer pessoa organize sua vida financeira simplesmente conversando com a aplicação.

### Objetivos do MVP

- Registrar movimentações em menos de 10 segundos.
- Categorizar automaticamente mais de 80% das transações.
- Identificar automaticamente formas de pagamento.
- Apresentar informações financeiras de maneira compreensível.
- Ajudar usuários a tomar melhores decisões financeiras.
- Criar hábito de acompanhamento financeiro.

---

## 4. Público-Alvo

### Público Principal

Pessoas entre 18 e 45 anos que desejam organizar melhor suas finanças.

### Perfil

- Iniciantes em educação financeira.
- Usuários que abandonaram aplicativos financeiros anteriormente.
- Pessoas que utilizam aplicativos de mensagens diariamente.
- Usuários que desejam praticidade e orientação.

---

## 5. Proposta de Valor

### Promessa Central

"Organize sua vida financeira simplesmente conversando."

### Diferenciais

- Registro por linguagem natural.
- Assistente financeiro inteligente.
- Recomendações personalizadas.
- Planejamento financeiro simplificado.
- Experiência acessível para iniciantes.
- Memória contextual dos hábitos financeiros.

---

## 6. Funcionalidades do MVP

### 6.1 Registro Conversacional de Movimentações

O usuário poderá registrar receitas e despesas através de mensagens.

#### Exemplos

- "Gastei R$ 42 no almoço via Pix"
- "Recebi R$ 3.500 de salário"
- "Paguei R$ 130 de academia no débito"

#### Informações extraídas automaticamente

- Valor
- Tipo da movimentação
- Categoria
- Data
- Forma de pagamento
- Conta ou carteira utilizada

---

### 6.2 Classificação Automática

#### Categorias iniciais

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Investimentos
- Salário
- Outros

O sistema poderá aprender preferências e corrigir classificações futuras.

---

### 6.3 Contas e Carteiras

O sistema deverá representar onde o dinheiro está armazenado.

#### Contas

- Conta Corrente
- Conta Digital
- Conta Poupança

#### Cartões

- Cartão de Crédito
- Cartão de Débito

#### Carteiras

- Dinheiro em espécie
- Carteiras digitais

#### Benefícios

Permitir responder perguntas como:

- Quanto dinheiro tenho disponível hoje?
- Em quais contas meu dinheiro está distribuído?
- Qual cartão estou utilizando com maior frequência?

---

### 6.4 Formas de Pagamento

Controle de:

- PIX
- Cartão de Crédito
- Cartão de Débito
- Dinheiro
- Transferência Bancária
- Boleto
- Outros

#### Relatórios

- Gastos por forma de pagamento.
- Distribuição percentual de utilização.
- Evolução do uso por período.

---

### 6.5 Metas Financeiras

Permitir criação e acompanhamento de objetivos financeiros.

#### Exemplos

- Reserva de emergência.
- Viagem.
- Troca de veículo.
- Compra de imóvel.

#### Funcionalidades

- Criação de metas.
- Acompanhamento de progresso.
- Previsão de conclusão.
- Recomendações relacionadas às metas.

---

### 6.6 Despesas Recorrentes

#### Exemplos

- Aluguel
- Internet
- Academia
- Streaming
- Plano de saúde

#### Funcionalidades

- Repetição automática.
- Lembretes de pagamento.
- Histórico de recorrência.
- Sugestão automática de recorrência ao detectar padrões.

---

### 6.7 Cartão de Crédito Inteligente

#### Funcionalidades

- Limite total.
- Limite disponível.
- Valor da fatura atual.
- Data de fechamento.
- Data de vencimento.

#### Consultas

- Quanto já gastei no cartão?
- Quanto tenho disponível?
- Quanto será minha próxima fatura?

---

### 6.8 Controle de Parcelamentos

#### Exemplo

"Comprei um notebook de R$ 4.800 em 12 vezes."

#### Funcionalidades

- Criação automática das parcelas.
- Projeção de impacto futuro.
- Consulta de parcelas pendentes.
- Visualização do comprometimento futuro da renda.

---

### 6.9 Relatórios e Dashboard

#### Indicadores

- Receitas
- Despesas
- Saldo
- Metas
- Faturas
- Parcelamentos

#### Visualizações

- Gastos por categoria.
- Gastos por forma de pagamento.
- Gastos por período.
- Evolução financeira.
- Distribuição por contas e carteiras.

---

### 6.10 Agente Financeiro

Assistente responsável por gerar recomendações úteis.

#### Exemplos

- Você gastou 20% mais com delivery este mês.
- Faltam R$ 150 para atingir sua meta.
- Seu gasto com transporte caiu 15%.

---

## 7. Funcionalidades Inteligentes Diferenciadoras

### 7.1 Memória Financeira Conversacional

O sistema deverá lembrar padrões e hábitos.

#### Exemplos

- Como da última vez, registrei a academia na categoria Saúde.
- Esse gasto parece ter sido feito no mesmo cartão utilizado anteriormente.

#### Benefícios

- Menos correções.
- Menos esforço do usuário.
- Experiência personalizada.

---

### 7.2 Conversar com as Finanças

O usuário pode fazer perguntas livremente.

#### Exemplos

- Onde estou gastando mais?
- Quanto gastei com lazer este ano?
- Se eu economizar R$ 15 por dia, quanto consigo em um ano?
- Estou gastando acima da minha média?

---

### 7.3 Insights Proativos

O sistema deve identificar oportunidades automaticamente.

#### Exemplos

- Seus gastos em delivery aumentaram 30%.
- Você possui R$ 280 em assinaturas mensais.
- Está próximo de atingir sua meta financeira.

---

### 7.4 Detecção de Assinaturas

Identificação automática de pagamentos recorrentes.

#### Exemplos

- Netflix
- Spotify
- YouTube Premium
- Microsoft 365
- ChatGPT

#### Benefício

Mostrar ao usuário o impacto mensal das assinaturas.

---

### 7.5 Score de Saúde Financeira

Indicador interno de acompanhamento financeiro.

#### Componentes

- Evolução das metas.
- Controle de gastos.
- Comprometimento de renda.
- Parcelamentos.
- Reserva financeira.

#### Resultado

Pontuação simples e compreensível que incentive evolução contínua.

---

### 7.6 Planejamento de Fluxo de Caixa

Análise financeira futura.

#### Consultas

- Vou fechar o mês no positivo?
- Quanto terei disponível no final do mês?
- Quanto da minha renda futura já está comprometida?

#### Considerações

- Receitas previstas.
- Parcelamentos.
- Despesas recorrentes.
- Faturas abertas.

---

### 7.7 Desafios de Economia

Gamificação leve para incentivar hábitos saudáveis.

#### Exemplos

- Economizar R$ 100 nesta semana.
- Ficar 7 dias sem pedir delivery.
- Registrar movimentações por 15 dias consecutivos.

#### Benefícios

- Maior engajamento.
- Formação de hábitos.
- Aumento da retenção.

---

## 8. Telas do MVP

### Tela Inicial

- Saldo consolidado.
- Resumo financeiro.
- Metas.
- Alertas.
- Saúde Financeira.

---

### Tela de Conversa

Principal interface do sistema.

#### Funcionalidades

- Histórico.
- Campo de mensagem.
- Sugestões rápidas.
- Ações frequentes.

---

### Dashboard

- Indicadores financeiros.
- Gráficos.
- Insights.
- Evolução de gastos.

---

### Contas e Carteiras

- Saldos por conta.
- Cartões cadastrados.
- Limites.
- Faturas.

---

### Metas

- Lista de objetivos.
- Evolução.
- Previsões.
- Recomendações.

---

## 9. Design Universal e Acessibilidade

O produto deverá seguir princípios de Design Universal.

### Diretrizes

- Mobile-first.
- Linguagem simples.
- Alto contraste.
- Tipografia legível.
- Compatibilidade com leitores de tela.
- Navegação intuitiva.
- Áreas de toque adequadas.
- Não depender apenas de cores.
- Fluxos simples para usuários iniciantes.
- Boa experiência para diferentes idades e níveis de alfabetização financeira.

---

## 10. Métricas de Sucesso

### Produto

- 70% registram uma movimentação no primeiro dia.
- 50% retornam após 7 dias.
- 80% das classificações corretas.
- 80% das formas de pagamento identificadas corretamente.

### Negócio

- NPS ≥ 40.
- Retenção de 30 dias ≥ 30%.
- Média de 5 registros por usuário por semana.

---

## 11. Hipóteses de Validação

### Hipótese 1

Usuários preferem registrar gastos por conversa.

### Hipótese 2

Insights automáticos aumentam retenção.

### Hipótese 3

A memória financeira reduz correções manuais.

### Hipótese 4

Visualizar contas, cartões e parcelamentos gera mais valor do que visualizar apenas gastos.

### Hipótese 5

O acompanhamento de fluxo de caixa ajuda o usuário a tomar decisões financeiras melhores.

---

## 12. Regras para Geração no Lovable

Criar um aplicativo mobile-first de finanças pessoais baseado em IA conversacional.

A aplicação deve seguir princípios de Design Universal e acessibilidade.

O chat é o centro da experiência.

O sistema deve funcionar como um Copiloto Financeiro Pessoal.

Priorizar:

- Simplicidade.
- Clareza.
- Acessibilidade.
- Educação financeira.
- Personalização.

Funcionalidades obrigatórias:

- Registro por linguagem natural.
- Classificação automática.
- Formas de pagamento.
- Contas e carteiras.
- Metas financeiras.
- Cartões de crédito.
- Parcelamentos.
- Despesas recorrentes.
- Dashboard financeiro.
- Insights proativos.
- Memória financeira conversacional.
- Saúde financeira.
- Planejamento de fluxo de caixa.
- Detecção de assinaturas.

Todas as respostas devem estar em português brasileiro.

Evitar formulários sempre que possível.

A experiência deve parecer uma conversa com um consultor financeiro amigável, inteligente e não julgador.
```

Interações com o Lovable:
> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document):{PRD}

> Me explique como funciona o quadro "Saúde financeira" que está na página /inicio

> parece que esse quadro não está funcionando corretamente de acordo com as informações que foram inseridas referentes às entradas e saídas. Você consegue verificar?

> se uma informaçao não tiver registros, como por exemplo as metas, como essa informação deveria aparecer no quadro de saúde financeira?

> Vamos fazer as alterações da lógica conforme você sugeriu anteriormente para poder corrigir o quadro de saúde financeira, de modo que consiga funcionar corretamente. Caso não haja registros específicos para uma informação faça como sugerido na Opção 1: Estado "Não avaliado" com nota proporcional (Recomendada)

> Na página /painel, verifique se o quadro "Fluxo de caixa até o fim do mês" está funcionando corretamente. Ele não deveria ao menos informar o valor disponível hoje, com base nas minhas entradas e saídas?

> faça as alterações necessárias.


Resultado Final no Lovable: https://fio-financas-em-dia.lovable.app

<img width="1352" height="626" alt="image" src="https://github.com/user-attachments/assets/af80d87e-a45d-4380-b7a5-f85d60681bd4" />

<img width="1355" height="623" alt="image" src="https://github.com/user-attachments/assets/fb7c9eee-f0d5-421c-a968-c9fc8af3103c" />

<img width="1348" height="621" alt="image" src="https://github.com/user-attachments/assets/c6d3b8d9-e9ed-47d0-86de-9cea6cc40c66" />

<img width="1347" height="625" alt="image" src="https://github.com/user-attachments/assets/23f6b0e5-d1df-46d2-b2fc-a6549e81e88f" />

<img width="1360" height="626" alt="image" src="https://github.com/user-attachments/assets/a90f16e6-1333-497a-b010-6686bd3ca354" />

<img width="1339" height="630" alt="image" src="https://github.com/user-attachments/assets/b2750067-a6e8-4343-af06-71cc4fb90fd3" />

<img width="1351" height="624" alt="image" src="https://github.com/user-attachments/assets/2c900ac8-dc4e-4ae3-824d-62ecaef1a6da" />

<img width="1356" height="619" alt="image" src="https://github.com/user-attachments/assets/b9e62d23-3600-41d7-b087-87fb5aab824a" />


# 🧵 Fio — Copiloto Financeiro Pessoal

> **Não perca o fio da meada das suas finanças.**  
> O Fio é um copiloto financeiro conversacional mobile-first feito para quem quer organizar o dinheiro sem o atrito de planilhas complexas ou formulários manuais cansativos.

---

## 🚀 Principais Funcionalidades

### 💬 1. Copiloto Financeiro Conversacional (Chat com IA)
* **Registro em linguagem natural:** registre entradas e saídas digitando como se falasse com um amigo no WhatsApp (ex: *"Almocei por 35 no débito Itaú"* ou *"Recebi 5.200 de salário"*).
* **Compras parceladas inteligentes:** suporte a parcelamentos (ex: *"Comprei uma geladeira de 12x de 250 no Bradesco"*), com cálculo exato de centavos e distribuição automática nas faturas dos meses futuros.
* **Memória de hábitos:** o copiloto aprende palavras-chave do seu dia a dia (como *"almoço"*, *"uber"*, *"academia"*), preenchendo categoria e forma de pagamento automaticamente nos próximos registros.
* **Ações completas por conversa:** crie contas bancárias, cadastre metas, registre aportes ou despesas fixas diretamente pelo chat.
* **Consultas e dúvidas históricas:** pergunte *"Quanto gastei com delivery em outubro?"* ou *"Quanto ainda posso gastar esse mês?"* e receba respostas imediatas baseadas nos seus dados reais.

---

### 🩺 2. Termômetro de Saúde Financeira
* **Score de 0 a 100:** avaliação da solidez das suas finanças dividida em 5 pilares estratégicos (até 20 pontos cada):
  1. **Controle de gastos:** taxa de economia mensal (receitas vs. despesas).
  2. **Evolução das metas:** progresso das suas reservas e objetivos.
  3. **Comprometimento da renda:** fatia do orçamento presa em contas fixas e parcelas.
  4. **Parcelamentos:** peso das compras a prazo no orçamento.
  5. **Reserva financeira:** meses de cobertura das despesas pelo saldo disponível.
* **Diagnóstico proporcional (sem penalidades artificiais):** pilares que ainda não possuem registros aparecem como *"Não avaliado"*, calibrando a nota apenas sobre o que já foi informado.
* **Dicas práticas e acionáveis:** orientações diretas com atalho para o chat para calibrar ou melhorar cada indicador.

---

### 📊 3. Painel Financeiro & Fluxo de Caixa
* **Projeção até o fim do mês:** acompanhe o saldo disponível hoje, receitas e despesas previstas e a estimativa de sobra financeira até o fechamento do mês.
* **Cálculo flexível de saldo:** calcula o disponível com base no saldo real das contas cadastradas ou, enquanto não houver contas bancárias criadas, a partir do acumulado de entradas menos saídas.
* **Distribuição visual de gastos:** gráficos e detalhamento por categorias (Alimentação, Moradia, Transporte, etc.) e formas de pagamento (PIX, Cartão de Crédito, Débito, etc.).
* **Controle de faturas e cartões:** visão de faturas abertas, limite utilizado e parcelas futuras já contratadas para os próximos meses.

---

### 🏦 4. Gestão de Contas e Cartões
* Cadastro e acompanhamento de contas correntes, contas digitais, poupanças e carteiras.
* Controle de cartões de crédito com dias de fechamento e vencimento de fatura.

---

### 🎯 5. Metas Financeiras
* Definição de objetivos com valor-alvo e data limite (ex: Reserva de Emergência, Viagem, Reforma).
* Barra de progresso visual (% atingida) e cálculo de quanto você precisa poupar por mês para alcançar o objetivo no prazo.

---

### 🔒 6. Segurança e Nuvem
* **Autenticação segura:** login via e-mail e senha, Google ou Lovable.
* **Isolamento total de dados:** segurança a nível de linha (Row-Level Security - RLS), garantindo que cada usuário acesse exclusivamente suas próprias movimentações.
* **Sincronização em tempo real:** dados atualizados instantaneamente em qualquer dispositivo.

---

## 🛠️ Stack Tecnológica

* **Framework Full-Stack:** [TanStack Start v1](https://tanstack.com/start) (React 19 + SSR)
* **Linguagem:** TypeScript
* **Estilização & Design:** Tailwind CSS v4, shadcn/ui, tipografia mobile com *Bricolage Grotesque* e *Atkinson Hyperlegible*
* **Inteligência Artificial:** Vercel AI SDK + Lovable AI Gateway (Function Calling / Tool Calling integradas)
* **Backend & Banco de Dados:** Lovable Cloud (PostgreSQL / Supabase com RLS)
* **Motor Financeiro:** Núcleo matemático unificado em TypeScript (`src/lib/finance.ts`), garantindo paridade total entre os números exibidos na interface e os cálculos do copiloto.


## Reflexão
### O que funcionou bem?  
Foi importantíssimo refinar previamente o PRD no Copilot para otimizar a utilização de créditos no Lovable.
### O que não funcionou como o esperado?  
Gostaria de poder interagir mais de forma gratuíta pelo Lovable. Tentei construir um app mais robusto e isso consumiu muitos créditos. Não consegui concluir o projeto em um único dia devido à quantidade de créditos utilizada, mesmo fazendo o refinamento prévio no Copilot Web.
### O que aprendeu sobre conversar com IAs?

Aprendi que conversar com uma IA é como explicar uma tarefa para um estagiário. Quanto mais detalhes dermos, melhores são os resultados. E sempre é necessário monitorar e revisar o trabalho, corrigindo falhas e alucinações das IAs.
