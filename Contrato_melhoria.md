# 📋 Contrato de Melhoria (Project Charter — Fase Define)

![Metodologia](https://img.shields.io/badge/Metodologia-Lean%20Six%20Sigma%20DMAIC-0A66C2?style=flat-square)
![Fase](https://img.shields.io/badge/Fase-Define-2EA44F?style=flat-square)
![Indicador](https://img.shields.io/badge/KPI%20Principal-OEE%2054%25%20%E2%86%92%2075%25-F59E0B?style=flat-square)
![Status](https://img.shields.io/badge/Status-Aprova%C3%A7%C3%A3o%20Tollgate%201-6E7681?style=flat-square)

**Projeto:** Aumento da Eficiência Global de Equipamentos (OEE) da Linha de Produção 01

---

## 📑 Sumário

- [1. Identificação do Projeto](#1-identificação-do-projeto)
- [2. Business Case e Relevância Estratégica](#2-business-case-e-relevância-estratégica)
- [3. Voz do Cliente (VOC), Árvore CTQ e Metas do Projeto](#3-voz-do-cliente-voc-árvore-ctq-e-metas-do-projeto)
- [4. Escopo, Fronteiras e Restrições](#4-escopo-fronteiras-e-restrições)
- [5. Mapa SIPOC Macro (Linha de Produção 01)](#5-mapa-sipoc-macro-linha-de-produção-01)
- [6. Equipe do Projeto, Governança e Stakeholders](#6-equipe-do-projeto-governança-e-stakeholders)
- [7. Cronograma Macro (DMAIC — 24 Semanas)](#7-cronograma-macro-dmaic--24-semanas)
- [8. Análise Preliminar de Riscos](#8-análise-preliminar-de-riscos)
- [9. Checklist de Validação da Fase Define e Aprovação](#9-checklist-de-validação-da-fase-define-e-aprovação)

---

## 1. Identificação do Projeto

| Campo | Detalhe |
| :--- | :--- |
| **Nome do Projeto** | Aumento da Eficiência Global (OEE) da Linha Gargalo de Produção (Linha 01) |
| **Metodologia** | Lean Six Sigma — Roteiro DMAIC |
| **Líder do Projeto (Belt)** | Anderson Pereira Miranda Soares (Analista de Operações) |
| **Sponsor / Champion** | Gerente Industrial / Diretor de Operações |
| **Área / Processo Alvo** | Manufatura Industrial — Linha de Produção 01 (Turnos A, B e C) |
| **Data de Abertura** | 01/09/2026 |
| **Prazo Previsto** | 6 meses (24 semanas) |
| **Status Atual** | Fase Define (Em aprovação para Tollgate 1) |

---

## 2. Business Case e Relevância Estratégica

### 2.1 Declaração do Problema

Nos últimos 6 meses, a Linha de Produção 01 (processo gargalo da planta) operou com um **OEE médio de 54%**, ficando **21 pontos percentuais abaixo da meta operacional de 75%**. Esse déficit de eficiência comprometeu o cumprimento dos prazos de entrega (**OTIF em 82%**, ante a meta de **95%**) e exigiu a realização recorrente de turnos extras aos finais de semana para atender à carteira de pedidos.

> [!NOTE]
> **Nota metodológica:** A declaração descreve estritamente o sintoma mensurável e seu impacto no negócio, sem presumir causas raízes, culpados ou soluções.

### 2.2 Por que este projeto é importante?

- **Para a Organização:** Libera capacidade produtiva instalada sem necessidade de investimento de capital (CAPEX), reduz o custo unitário de transformação, elimina despesas recorrentes com horas extras de final de semana e aumenta a previsibilidade do planejamento (PCP).
- **Para os Clientes:** Eleva a confiabilidade nas datas de entrega (OTIF), reduz o risco de ruptura na cadeia do cliente e assegura maior estabilidade na qualidade dos lotes fornecidos.

### 2.3 Estimativa de Ganho Financeiro (*Hard Savings*)

| Frente de Ganho | Premissa de Cálculo | Ganho Mensal Estimado | Ganho Anual Estimado |
| :--- | :--- | :---: | :---: |
| **Eliminação de Horas Extras** | Redução de 2 turnos extras/semana em finais de semana (encargos e adicionais inclusos) | R$ 18.000,00 | R$ 216.000,00 |
| **Redução de Refugo e Retrabalho** | Queda da taxa de refugo de 5,5% para até 2,0% (economia de matéria-prima e energia) | R$ 8.500,00 | R$ 102.000,00 |
| **Ganho de Capacidade / Margem** | Absorção de demanda reprimida sem custos fixos adicionais | R$ 5.500,00 | R$ 66.000,00 |
| **Total Estimado (*Hard Savings*)** | **Soma das frentes acima** | **R$ 32.000,00** | **R$ 384.000,00** |

> [!TIP]
> **Orçamento e Retorno:** O investimento previsto é restrito a despesas operacionais (**OPEX**) de até **R$ 15.000,00** (padronização, gestão visual, ferramentas de troca rápida e treinamentos), resultando em *payback* estimado **inferior a 1 mês** após a estabilização na fase *Control*.

---

## 3. Voz do Cliente (VOC), Árvore CTQ e Metas do Projeto

### 3.1 Desdobramento VOC para CTQ

| Parte Interessada | Voz do Cliente (VOC) | Direcionador | Requisito Crítico — CTQ |
| :--- | :--- | :--- | :--- |
| **Cliente Externo / Comercial** | *"Preciso receber os pedidos completos na data combinada."* | Confiabilidade de Entrega | OTIF ≥ 95% |
| **Diretoria / Operações** | *"Precisamos entregar mais volume com o ativo atual e sem horas extras."* | Eficiência Produtiva e Custo | OEE ≥ 75% e redução de horas extras ≥ 80% |
| **Qualidade** | *"Os lotes devem sair conforme especificação já na primeira passagem."* | Conformidade de Produto | Índice de Qualidade (OEE) ≥ 98% (Refugo ≤ 2%) |

### 3.2 Painel de Indicadores (Baseline vs. Meta)

| Tipo | Indicador | Fórmula / Critério | Baseline Atual (6m) | Meta do Projeto | Frequência |
| :--- | :--- | :--- | :---: | :---: | :---: |
| **Y Principal** | OEE Global (Linha 01) | `Disponibilidade × Performance × Qualidade` | 54,0% | **≥ 75,0%** | Diária (por turno) |
| **Y Secundário** | Disponibilidade | `Tempo Operando / Tempo Disponível` | 68,0% | **≥ 85,0%** | Diária (por turno) |
| **Y Secundário** | Performance | `(Produção Total × Ciclo Ideal) / Tempo Operando` | 84,0% | **≥ 90,0%** | Diária (por turno) |
| **Y Secundário** | Qualidade | `(Produção Total − Refugo) / Produção Total` | 94,5% | **≥ 98,0%** | Diária (por turno) |
| **Y de Negócio** | OTIF (Pedidos Linha 01) | `Pedidos entregues no prazo e completos / Total de pedidos` | 82,0% | **≥ 95,0%** | Semanal |
| **Contramedida (*Guardrail*)** | Segurança e Manutenção | Taxa de incidentes/acidentes e custo de manutenção corretiva | Zero acidentes | Manter zero acidentes e não elevar custo corretivo | Mensal |

---

## 4. Escopo, Fronteiras e Restrições

- **Fronteira Inicial:** Recebimento da Ordem de Produção (OP) emitida pelo PCP e abastecimento de matéria-prima na Linha 01.
- **Fronteira Final:** Inspeção final de qualidade, apontamento de produção no sistema e liberação do lote acabado para o estoque/expedição.

| ✅ Dentro do Escopo | ❌ Fora do Escopo |
| :--- | :--- |
| Operação completa da Linha 01 nos Turnos A, B e C (SKUs 01, 02 e 03) | Aquisição de novas máquinas ou grandes reformas de capital (CAPEX) |
| Gestão de paradas não planejadas, microparadas e tempos de setup | Alteração de fornecedores externos de matéria-prima ou contratos de suprimentos |
| Aderência ao tempo de ciclo ideal e redução de refugos gerados na linha | Processos de transporte externo e logística de distribuição ao cliente final |
| Padronização de passagem de turno, apontamento de dados e manutenção autônoma | Outras linhas produtivas da fábrica (possível replicação apenas pós-Control) |

### 4.1 Restrições do Projeto (Triângulo de Ferro)

> [!IMPORTANT]
> - **Prazo:** Conclusão de todas as fases do DMAIC em até **6 meses (24 semanas)**.
> - **Custo:** Investimento máximo limitado a **R$ 15.000,00** em verba OPEX aprovada pelo Sponsor.
> - **Qualidade e Segurança:** Nenhuma mudança testada ou implementada poderá flexibilizar tolerâncias técnicas de qualidade, requisitos de clientes ou normas regulamentadoras de segurança (NRs).

---

## 5. Mapa SIPOC Macro (Linha de Produção 01)

| Suppliers (Fornecedores) | Inputs (Entradas) | Process (Processo Macro) | Outputs (Saídas) | Customers (Clientes) |
| :--- | :--- | :--- | :--- | :--- |
| PCP | Ordem de Produção (OP) e sequenciamento de SKUs | **1.** Receber programação e preparar setup da linha | Linha preparada e parâmetros ajustados | Operação da Linha 01 |
| Almoxarifado / Suprimentos | Matéria-prima, insumos e embalagens | **2.** Abastecer insumos e iniciar processamento contínuo | Produto em processamento | Etapa de Transformação |
| Manutenção e Utilidades | Energia elétrica, ar comprimido, equipamentos disponíveis | **3.** Operar linha, monitorar parâmetros e registrar paradas | Lote produzido e apontamentos de turno | Qualidade / Controle de Produção |
| Controle de Qualidade | Especificações técnicas e padrões de inspeção | **4.** Inspecionar conformidade e segregar refugos | Lote aprovado e registro de refugo | Expedição / Logística Interna |
| Operação da Linha 01 | Produto acabado e registros de produção | **5.** Apontar produção final e liberar lote para estoque | Produto acabado conforme + relatórios de OEE | Expedição, PCP e Cliente Final |

---

## 6. Equipe do Projeto, Governança e Stakeholders

### 6.1 Estrutura da Equipe

| Papel no Projeto | Cargo / Área | Responsabilidade Principal | Dedicação Estimada |
| :--- | :--- | :--- | :---: |
| **Sponsor / Champion** | Gerente Industrial | Patrocinar recursos, remover barreiras organizacionais e aprovar passagens de fase (*Tollgates*) | 2h / mês |
| **Líder do Projeto (Belt)** | Anderson Pereira Miranda Soares (Analista de Operações) | Conduzir o roteiro DMAIC, liderar análises estatísticas, coordenar testes piloto e reportar avanços | 10h / semana |
| **Especialistas de Processo** | Supervisores de Produção (Turnos A, B e C) | Apoiar o mapeamento no Gemba, garantir disciplina de apontamento e conduzir testes em turno | 3h / semana cada |
| **Suporte Técnico** | Técnico de Manutenção Industrial | Analisar histórico de falhas mecânicas/elétricas, MTBF/MTTR e propor melhorias de confiabilidade | 4h / semana |
| **Planejamento** | Analista de PCP | Fornecer sequenciamento de produção, dados de setup e impacto no OTIF | 2h / semana |
| **Qualidade** | Inspetor / Analista de Qualidade | Validar sistema de medição (MSA), estratificar motivos de refugo e assegurar conformidade | 3h / semana |
| **Operadores-Chave** | 1 Operador líder por turno (A, B e C) | Trazer visão prática de chão de fábrica, validar instruções de trabalho e apoiar o piloto | 2h / semana cada |

### 6.2 Governança e Rituais de Comunicação

- **Reunião de Kick-off (Semana 1):** Alinhamento formal do contrato, metas, papéis e regras de convivência com Sponsor, gestores diretos e equipe.
- **Acompanhamento Semanal (30 min):** Reunião objetiva da equipe do projeto para revisar plano de ação, destravar pendências e acompanhar coleta de dados.
- **Revisões de Tollgate (Fim de cada fase DMAIC):** Apresentação executiva ao Sponsor para validação das entregas e liberação para a fase seguinte.
- **Gestão Visual no Gemba:** Quadro físico/digital na Linha 01 exibindo evolução semanal do OEE e principais aprendizados para engajamento dos 3 turnos.

---

## 7. Cronograma Macro (DMAIC — 24 Semanas)

| Fase DMAIC | Período | Principais Entregas | Marco de Aprovação |
| :--- | :---: | :--- | :--- |
| **Define** | Semanas 1 a 3 | Contrato de Melhoria, Business Case, SIPOC, VOC/CTQ e Kick-off | Tollgate 1 (Aprovação do Contrato) |
| **Measure** | Semanas 4 a 8 | VSM / Fluxograma detalhado, Plano de Coleta, validação do Sistema de Medição (MSA), Baseline de OEE e Capabilidade | Tollgate 2 (Dados e Baseline Validados) |
| **Analyze** | Semanas 9 a 13 | Pareto de perdas, estratificação por turno (Boxplot/ANOVA), correlação/regressão e Análise de Causa Raiz (RCA) | Tollgate 3 (Causas Raízes Provadas) |
| **Improve** | Semanas 14 a 19 | Matriz Impacto x Esforço, desenho de contramedidas (ex.: SMED, manutenção autônoma), Testes Piloto (PDSA) e validação estatística Antes x Depois | Tollgate 4 (Ganhos Comprovados) |
| **Control** | Semanas 20 a 24 | Plano 5W2H de implementação definitiva, padronização de POPs, treinamento dos turnos, Carta de Controle (CEP) e fechamento financeiro | Tollgate 5 (Encerramento e Handover) |

---

## 8. Análise Preliminar de Riscos

| Risco Identificado | Impacto | Probabilidade | Plano de Mitigação |
| :--- | :---: | :---: | :--- |
| **Apontamentos manuais inconsistentes ou incompletos de paradas** | 🔴 Alto | 🔴 Alta | Realizar treinamento de apontamento e aplicar estudo de MSA/auditoria no Gemba logo no início do *Measure*. |
| **Sobrecarga de rotina dos membros da equipe impedindo dedicação ao projeto** | 🔴 Alto | 🟡 Média | Negociar formalmente a carga horária com os gestores diretos junto ao Sponsor antes do Kick-off. |
| **Resistência operacional nos turnos às mudanças de procedimento** | 🟡 Médio | 🟡 Média | Envolver operadores-chave desde o mapeamento, comunicar ganhos para o dia a dia e testar mudanças via pilotos controlados. |
| **Variação sazonal da demanda mascarando o ganho de OEE** | 🟡 Médio | 🟢 Baixa | Acompanhar o OEE normalizado por tempo disponível e mix de SKUs, utilizando testes de hipótese na validação Antes x Depois. |

---

## 9. Checklist de Validação da Fase Define e Aprovação

- [ ] O problema está descrito de forma mensurável, sem apontar causas, culpados ou soluções?
- [ ] O projeto está alinhado às metas estratégicas da organização e possui ganho financeiro estimado (*Business Case*)?
- [ ] O Sponsor/Champion e a equipe multidisciplinar estão formalmente definidos, com horas alinhadas junto aos gestores?
- [ ] O processo alvo e suas fronteiras (dentro/fora do escopo) estão claros e mapeados via SIPOC?
- [ ] A Voz do Cliente (VOC) foi traduzida em CTQs e indicadores com *baseline* e metas objetivas?
- [ ] O cronograma cabe na janela recomendada de até 6 meses?

### Aprovação Formal

| Papel | Nome | Assinatura / Data |
| :--- | :--- | :---: |
| **Sponsor / Champion** | *Gerente Industrial* | `____/____/2026` |
| **Líder do Projeto** | Anderson Pereira Miranda Soares | `____/____/2026` |
| **Gestor da Área Operacional** | *Coordenador de Produção* | `____/____/2026` |
