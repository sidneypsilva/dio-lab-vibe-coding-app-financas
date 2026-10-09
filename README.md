# 🏮 Farol — App de Finanças Pessoais com Vibe Coding & Design Universal

> **"Pequenos passos. Mais tranquilidade."**  
> Aplicação web de finanças pessoais orientada a conversas em linguagem natural, construída nativamente com foco em **Design Universal** e diretrizes **WCAG 2.1 AA**.

Projeto desenvolvido por **Sidney Pereira da Silva** como entrega do **Desafio de Projeto da DIO (Digital Innovation One)** sobre **Vibe Coding** utilizando o **Lovable**.

---


## 📝 PRD Sintetizado (Design Universal como Pilar)

```markdown
# PRD — Farol: Finanças Pessoais Inclusivas

---

## 1. Visão Geral & Proposta de Valor

O **Farol** é uma solução de finanças pessoais orientada a conversação em linguagem natural desenvolvida sob a filosofia do **Design Universal**. 

O produto elimina a fricção dos aplicativos financeiros convencionais — que exigem o preenchimento manual de dezenas de campos, categorizações engessadas e leitura de relatórios densos — substituindo-os por uma conversa acolhedora com um agente inteligente. Qualquer pessoa, independentemente de idade, letramento digital, destreza motora ou limitações visuais e cognitivas, tem autonomia plena para planejar sua vida financeira.

---

## 2. O Problema & Oportunidade de Mercado

### 2.1. Dores do Usuário
- **Abandono precoce:** A maioria das pessoas desiste do controle financeiro nas primeiras duas semanas devido ao esforço cognitivo e operacional de anotar gastos manualmente.
- **Exclusão digital e capacitismo de design:** Interfaces convencionais utilizam fontes diminutas, baixo contraste, navegação estritamente baseada em mouse e dependência exclusiva de cores (como vermelho para despesas e verde para receitas), excluindo pessoas com baixa visão, daltônicos e idosos.
- **Ansiedade financeira:** Linguagem ríspida, jargões de mercado bancário e gráficos complexos aumentam o estresse do usuário iniciante.

### 2.2. A Oportunidade
- Uma experiência conversacional sem atritos onde o usuário registra receitas e gastos como se enviasse uma mensagem no WhatsApp.
- Aplicação nativa de **WCAG 2.1 AA** como diferencial competitivo e compromisso ético de inclusão.

---

## 3. Personas & Design Universal

### 3.1. Princípios do Design Universal no Farol
1. **Uso Equitativo:** A mesma experiência acolhedora para quem enxerga perfeitamente e para quem usa leitor de tela.
2. **Flexibilidade no Uso:** Controle via digitação livre, chips de atalho rápido ou navegação 100% por teclado.
3. **Uso Simples e Intuitivo:** Microcópia em português claro (nível fundamental), sem jargões contábeis.
4. **Informação Perceptível:** Apresentação redundante de dados (valores, ícones descritivos e sinais `+` e `-`).
5. **Tolerância ao Erro:** Ações destrutivas com confirmação segura e foco inicial em cancelamento; botão de "Desfazer" imediato.
6. **Baixo Esforço Físico:** Alvos de clique/toque de no mínimo 44×44px e campo de digitação sempre acessível.
7. **Dimensão e Espaço para Acesso:** Interface responsiva que suporta zoom de 200% sem quebra de layout.

---

## 4. Requisitos de Produto (Visão Global)

### 4.1. Requisitos Funcionais (RF)
- **RF01 — Interpretação Conversacional:** Processamento em linguagem natural para identificar receitas, despesas, valores, categorias e datas.
- **RF02 — Confirmação e Tolerância:** Apresentação de cards interativos para confirmação imediata ou cancelamento/desfazer da transação.
- **RF03 — Gestão de Metas Financeiras:** Criação, acompanhamento e aportes direcionados para metas específicas com barras de progresso informativas.
- **RF04 — Extrato sob Demanda no Chat:** Consulta de histórico consolidado diretamente no fluxo da conversa, sem necessidade de trocar de aba.
- **RF05 — Painel de Controle (Dashboard):** Visão sintética de receitas, despesas, saldo acumulado e gráficos com legendas acessíveis.
- **RF06 — Histórico Estruturado:** Listagem cronológica com suporte a múltiplos períodos (mês atual, 30 dias e acumulado) e filtros por categoria.
- **RF07 — Educação & Cotações de Apoio:** Exibição não intrusiva de dicas financeiras diárias e indicadores de mercado (câmbio e ativos).

### 4.2. Requisitos Não-Funcionais (RNF)
- **RNF01 — Acessibilidade WCAG 2.1 AA:** Contraste mínimo de 4.5:1 para texto normal e 3:1 para componentes de interface.
- **RNF02 — Precisão Financeira:** Armazenamento monetário rigoroso em inteiros (centavos) para evitar erros de ponto flutuante.
- **RNF03 — Segurança e Privacidade:** Isolamento estrito de dados multi-inquilino através de políticas de banco (Row Level Security - RLS).
- **RNF04 — Responsividade:** Adaptação fluida para dispositivos móveis, tablets e desktops.

---

## 5. Métricas de Sucesso

- **Taxa de Retenção D30:** Usuários mantendo registros após 30 dias de uso.
- **Tempo Médio de Registro:** Conclusão de inserção de gasto em menos de 10 segundos.
- **Aderência de Acessibilidade:** 0 violações críticas em auditorias automatizadas (axe DevTools / WAVE).
- **Engajamento com Metas:** Porcentagem de usuários com pelo menos uma meta ativa com aportes recorrentes.

---

## 6. Roadmap Estratégico (Pós-MVP)

1. **Entrada por Voz (Speech-to-Text):** Envio de áudios curtos para transcrição e registro automático.
2. **Exportação de Relatórios Acessíveis:** Relatórios em CSV e PDF estruturados para leitores de tela.
3. **Alertas Proativos de Metas:** Notificações amigáveis no chat quando uma meta estiver perto de ser concluída.
4. **Open Finance:** Leitura automática de extratos bancários com consentimento do usuário.

```

## 🌐 Demonstração Online

Acesse o app publicado e teste a experiência em tempo real:  
👉 **[https://chatfinac.lovable.app](https://chatfinac.lovable.app)**

<img width="1340" height="1311" alt="image" src="https://github.com/user-attachments/assets/4f9f303f-b113-4655-a89f-4ab4934cb967" />

---

## 💬 Jornada de Vibe Coding no Lovable

O processo de desenvolvimento seguiu o ciclo contínuo de **Vibe Coding**: instrução em linguagem natural, observação do resultado gerado, testes de usabilidade e refinamento iterativo.

### Etapas Principais

1. **Estrutura Base & Design Universal (Prompt 1):**  
   Criação da interface inicial com suporte a temas acessíveis, contrastes validados, banco de dados e autenticação via Lovable Cloud (Supabase).

2. **Interpretação Natural & Tolerância a Falhas (Prompt 2):**  
   Implementação do parser de linguagem natural para capturar receitas e despesas cotidianas (*"Almoço R$ 38,50"*, *"Recebi Pix de R$ 300"*), incluindo desambiguação inteligente quando a intenção não for óbvia (*"Pagamento de R$ 100 — você recebeu ou pagou?"*).

3. **Dashboard, Metas & Histórico (Prompts 3 e 4):**  
   Criação dos cards de saldo, receitas e despesas, gráficos com legendas textuais legíveis (sem depender só de cores), tela de Histórico com filtros temporais e edição com confirmação segura.

### Refinamentos e Evoluções de Experiência (Iterações Reais)

- **Aportes em Metas & Desambiguação:** Ao solicitar *"transfira 200 para a meta Viagem"*, o sistema foi ajustado para reconhecer aportes específicos, diferenciar metas homônimas (ex.: *Viagem SP* vs *Viagem Nova Iorque*) e gerar o card dedicado de aporte sem debitar duplamente como despesa avulsa.
- **Exclusão Segura de Metas:** Correção de concorrência na exclusão de metas e inclusão de diálogo de confirmação com foco prioritário em *"Manter meta"* e fechamento por tecla `Esc`.
- **Extrato Integrado ao Chat:** Adição do comando *"meu extrato"* direto na conversa, permitindo que o usuário visualize o resumo do período e a lista de movimentações em um card rolável sem precisar trocar de tela.
- **Cotações de Mercado & Ergonomia:** Criação de faixa horizontal compacta com cotações informativas (Dólar, CMIG4, CPTS11) e fixação permanente do campo de entrada na base, garantindo que o chat nunca fique escondido.
- **Identidade da Marca Farol:** Definição da nova marca, com símbolo minimalista de farol em balão de conversa verde-esmeralda, feixe dourado e o slogan oficial *"Pequenos passos. Mais tranquilidade."*.

---

## 🔍 Funcionalidades do Farol

| Funcionalidade | Descrição | Foco em Acessibilidade |
| :--- | :--- | :--- |
| **Chat Financeiro** | Entrada de gastos/receitas em linguagem natural brasileira | Chips de clique rápido, confirmação em card e botão de desfazer |
| **Extrato no Chat** | Consulta de transações recentes e saldo dentro da conversa | Card rolável com leitura cronológica semântica |
| **Gestão de Metas** | Criação, acompanhamento de progresso e aportes conversacionais | Desambiguação de nomes e exclusão segura com foco em cancelar |
| **Mercado em Foco** | Cotações do Dólar, CMIG4 e CPTS11 atualizadas periodicamente | Faixa compacta rolável, fonte legível e aviso educativo explícito |
| **Histórico & Filtros** | Filtros por Mês Atual, Últimos 30 Dias e Todo o Período | Estados claros de lista vazia, foco visível e edição acessível |
| **Design Universal** | Conformidade com diretrizes WCAG 2.1 nível AA | Contraste ≥ 4.5:1, alvos ≥ 44px, navegação 100% por teclado |

---

## 🛠️ Tecnologias Utilizadas

- **Frontend & Roteamento:** React, TanStack Start / TanStack Router, TypeScript.
- **Estilização & Componentes:** Tailwind CSS, Radix UI / shadcn/ui, Lucide Icons.
- **Backend & Persistência:** Lovable Cloud (PostgreSQL / Supabase com isolamento de dados por usuário via RLS).
- **Inteligência Conversacional:** Lovable AI com instruções semânticas e regras de negócio determinísticas em TypeScript (precisão financeira em centavos inteiros).
- **Dados de Mercado:** API de cotações com atualização periódica e cache otimizado.

---

## 🧠 Reflexão sobre Vibe Coding

### 1. O que funcionou muito bem?
- **O PRD como bússola de desenvolvimento:** Ter os requisitos e os critérios de Design Universal bem documentados desde o início evitou retrabalho e garantiu que cada tela nascesse acessível.
- **Ciclo de iteração rápida:** A capacidade de solicitar uma evolução (como trazer o extrato para dentro do chat ou ajustar o tamanho das cotações) e vê-la implementada e testável em minutos.

### 2. Principais desafios e soluções
- **Diferenciação entre despesa e aporte:** Inicialmente, transferências para metas eram categorizadas como saídas comuns. A solução foi criar um fluxo conversacional próprio com confirmação visual que alimenta a meta sem duplicar débitos.
- **Ergonomia visual em telas menores:** Integrar cotações de mercado e manter o chat legível exigiu transformar os cards em uma faixa horizontal compacta e manter o formulário de envio sempre fixado na parte inferior.

### 3. Aprendizado principal
Vibe Coding não é sobre deixar a IA construir às cegas, mas atuar como **Product Manager e QA rigoroso**: definir restrições claras, testar a interface com empatia para com o usuário final e conduzir a IA com feedbacks objetivos até alcançar excelência de produto.

---
---

*Projeto desenvolvido com dedicação e foco em inclusão digital.*  
**Sidney Pereira da Silva** — 2026
