# 📊 Otimização de OEE em Linha Produtiva — Projeto Lean Six Sigma (DMAIC)

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Metodologia](https://img.shields.io/badge/Lean%20Six%20Sigma-DMAIC-0A66C2?style=flat-square)
![KPI](https://img.shields.io/badge/OEE-54%25%20%E2%86%92%2077%25-2EA44F?style=flat-square)
![Hard Savings](https://img.shields.io/badge/Hard%20Savings-R%24%20384k%2Fano-F59E0B?style=flat-square)

Projeto completo de melhoria contínua e análise de dados industriais voltado para a atuação de **Analista de Operações**. O estudo aplica o roteiro **DMAIC** para elevar a Eficiência Global de Equipamentos (**OEE**) de uma linha produtiva gargalo sem necessidade de investimento em novas máquinas (CAPEX).

---

## 🎯 Resumo 

- **Problema:** A Linha de Produção 01 operou por 6 meses com **OEE médio de 54%** (meta: ≥ 75%), derrubando o **OTIF para 82%** e exigindo turnos extras recorrentes aos finais de semana.
- **Abordagem:** Diagnóstico baseado em dados (VSM, MSA, Pareto, Boxplot, ANOVA e Regressão), seguido de contramedidas Lean (SMED e Manutenção Autônoma) validadas por testes de hipótese e controladas via CEP.
- **Impacto Estimado (*Hard Savings*):** **R\$ 384.000,00/ano** (eliminação de horas extras, redução de refugo de 5,5% para ≤ 2% e liberação de capacidade) com OPEX limitado a R\$ 15.000,00.

---

## 📈 Evolução dos Indicadores (Baseline vs. Meta)

| Indicador | Baseline (6 meses) | Meta do Projeto | Frequência |
| :--- | :---: | :---: | :---: |
| **OEE Global (Y Principal)** | 54,0% | **≥ 75,0%** | Diária (por turno) |
| **Disponibilidade** | 68,0% | **≥ 85,0%** | Diária (por turno) |
| **Performance** | 84,0% | **≥ 90,0%** | Diária (por turno) |
| **Qualidade** | 94,5% | **≥ 98,0%** | Diária (por turno) |
| **OTIF (Negócio)** | 82,0% | **≥ 95,0%** | Semanal |

---



## O que é OEE?

O **OEE** (*Overall Equipment Effectiveness*, ou Eficiência Global dos Equipamentos) é o principal indicador utilizado na gestão industrial para medir o quanto um equipamento ou linha de produção está realmente produzindo em relação ao seu potencial máximo.

Em vez de olhar apenas para o volume produzido, o OEE responde a uma pergunta mais estratégica: **quanto do tempo planejado de operação foi convertido em produto bom, na velocidade ideal e sem paradas?**

### Os 3 Pilares do OEE

O cálculo do OEE combina três fatores que capturam as principais perdas do chão de fábrica:

$$\text{OEE} = \text{Disponibilidade} \times \text{Performance} \times \text{Qualidade}$$

| Pilar | O que mede | Fórmula | Exemplos de perdas na laminação |
| :--- | :--- | :--- | :--- |
| **Disponibilidade** | Percentual do tempo planejado em que a linha ficou realmente operando. | $\frac{\text{Tempo Operando}}{\text{Tempo Disponível}}$ | Trocas de bitola (setup), manutenções corretivas, falta de tarugo, embuchamentos (*cobbles*). |
| **Performance** | Ritmo real de produção comparado à capacidade nominal do equipamento. | $\frac{\text{Produtividade Real (t/h)}}{\text{Capacidade Nominal (t/h)}}$ | Microparadas, redução de velocidade da linha, ajustes de guias em operação. |
| **Qualidade** | Percentual da produção total que atende às especificações sem defeitos. | $\frac{\text{Produção Boa (t)}}{\text{Produção Total (t)}}$ | Refugo, sucata de ponta/cauda, barras fora de tolerância dimensional. |

### Por que o OEE é importante na gestão operacional?

* **Exposição de gargalos:** Mostra com precisão se a perda está em paradas (Disponibilidade), ritmo abaixo do nominal (Performance) ou geração de refugo (Qualidade).
* **Priorização de ações:** Direciona planos de ação (5W2H), melhorias de setup (SMED) e manutenção preventiva para os equipamentos e turnos com maior impacto.
* **Base para a rotina diária:** Facilita o acompanhamento de metas por turno, bitola e equipamento em reuniões de gestão à vista.
