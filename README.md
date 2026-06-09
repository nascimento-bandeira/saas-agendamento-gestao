# 📅 Agendamente - SaaS de Agendamento e Gestão para Negócios Locais

[![Vercel Deployment](https://img.shields.io/badge/Deploy-Vercel-black?style=flat-square&logo=vercel)](https://seu-link-aqui.vercel.app)
[![Supabase Backend](https://img.shields.io/badge/Backend-Supabase-emerald?style=flat-square&logo=supabase)](https://supabase.com)
[![Next.js Framework](https://img.shields.io/badge/Framework-Next.js%2014-white?style=flat-square&logo=nextdotjs)](https://nextjs.org)

O **Agendamente** é uma plataforma SaaS (Software as a Service) white-label desenvolvida para otimizar o fluxo de marcação de horários e gestão de clientes em estabelecimentos de serviços locais, como salões de beleza, clínicas de estética, estúdios e consultórios. 

O sistema resolve o problema de agendamentos manuais via mensagens, oferecendo uma interface de agendamento autônomo para o cliente final e um painel de controle administrativo completo para o empreendedor.

---

## 🚀 Demonstração em Tempo Real

Acesse a aplicação e teste com os dados de demonstração:
*   **🔗 Link da Aplicação:** [https://seu-link-aqui.vercel.app](https://seu-link-aqui.vercel.app)
*   **🔑 Credenciais de Teste (Painel ADM):**
    *   **E-mail:** `demo@agendamente.com`
    *   **Senha:** `demo1234`

---

## ✨ Funcionalidades Principais

### 📱 Portal Público do Cliente (Mobile-First)
*   **Agendamento Fluido:** Fluxo intuitivo em 3 passos (Escolha do Serviço/Profissional ➔ Escolha da Data/Hora ➔ Confirmação).
*   **Sem Barreiras de Entrada:** O cliente final realiza o agendamento fornecendo apenas Nome e WhatsApp, sem a necessidade de criar senhas complexas.
*   **Validação de Horários:** Bloqueio automático de horários retroativos ou já ocupados em tempo real.

### 💼 Painel Administrativo do Estabelecimento (Dashboard)
*   **Calendário Interativo:** Visualização diária/semanal dos horários agendados com suporte a bloqueio manual de horários (folgas/almoço).
*   **Gestão de Serviços e Equipe:** CRUD completo para cadastro de profissionais, horários de trabalho individuais, serviços prestados, preços e durações.
*   **Métricas de Negócio:** Gráficos de faturamento mensal, ticket médio e taxa de ocupação dos profissionais.
*   **Multi-tenant (Isolamento de Dados):** Segurança em nível de banco de dados (RLS), garantindo que um estabelecimento nunca acesse os dados de outro.

---

## 🛠️ Stack Tecnológica

O projeto foi construído utilizando as tecnologias mais modernas do ecossistema Web para garantir máxima performance, SEO otimizado e escalabilidade:

*   **Framework:** [Next.js (App Router)](https://nextjs.org/) com TypeScript.
*   **Estilização & UI:** [Tailwind CSS](https://tailwindcss.com/) + [Shadcn/ui](https://ui.shadcn.com/) (Componentes acessíveis e customizáveis).
*   **Gerenciamento de Estado:** [Zustand](https://zustand-demo.pmnd.rs/) (Estado global leve para o carrinho/fluxo de agendamento).
*   **Banco de Dados & Auth:** [Supabase](https://supabase.com/) (PostgreSQL com Row Level Security).
*   **Deployment:** [Vercel](https://vercel.com/) (Hospedagem de alta performance com Edge Caching).

---

## 📐 Arquitetura e Boas Práticas

*   **Clean Code:** Separação clara entre componentes de UI, lógica de negócios (hooks customizados) e chamadas de API.
*   **Segurança (RLS):** Uso extensivo de políticas de Row Level Security no Supabase para garantir que as rotas autenticadas do painel administrativo estejam 100% protegidas.
*   **Responsividade Total:** Interface desenhada sob a filosofia *mobile-first*, considerando que mais de 80% dos agendamentos de serviços locais ocorrem via smartphones.

---

## 🔧 Como Executar o Projeto Localmente
