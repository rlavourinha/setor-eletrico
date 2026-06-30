# Setor Elétrico Brasileiro — Mapa do Sistema

Estudo de referência do setor elétrico brasileiro (Fases 1–3), construído **antes** do estudo das empresas da cadeia. Dashboard HTML autocontido, sem dependências externas de dados.

🔗 **Publicado em:** https://rlavourinha.github.io/setor-eletrico/

## O que cobre

| Aba | Conteúdo |
|-----|----------|
| **Visão geral** | As três camadas (física, comercial, regulatória) e os números-chave do SIN |
| **Contexto histórico** | O arco de 1879 a 2026: como cada instituição nasceu de uma crise, e por que o Brasil "desagrega" o que o mundo "agrega" (comparação institucional internacional) |
| **Instituições** | Quem planeja (EPE), opera (ONS), regula (ANEEL) e liquida (CCEE) |
| **Sistema físico** | Matriz, reservatórios como "bateria", os 4 submercados, despacho por custo (NEWAVE→DECOMP→DESSEM), curtailment |
| **Oferta & demanda** | Crescimento histórico, a curva do pato, os leilões (LRCAP, BESS), o aprofundamento **capacidade × potência** (os dois lastros — energia vs. potência —, a fórmula da disponibilidade, o crédito de capacidade/ELCC, a evolução do LRCAP de 2021 a 2026 + baterias, e as trajetórias do déficit de potência até 2034), custo por fonte (LCOE), formação de preço pela geração marginal (merit order, canibalização, missing money), a teoria curto × longo prazo (SRMC/LRMC, curva de triagem, a reconciliação) e o arco dos incentivos renováveis |
| **Geração** | Quanto custa e quanto demora construir (CAPEX/prazo/fator de capacidade por fonte), o ciclo de caixa (curva J), o financiamento (project finance, BNDES, debêntures incentivadas), por que o Brasil parou de construir grandes hidrelétricas (+ UHR reversíveis) e o que muda com o avanço das baterias (capacidade vs arbitragem, complementaridade com a hidro, tensão com o gás) |
| **Mercado & preço** | ACR vs ACL, abertura do mercado livre, formação do PLD, risco hidrológico (MRE/GSF), bandeiras |
| **Regulação econômica** | Como cada segmento ganha dinheiro: RAP (transmissão), Parcela A/B + ativos regulatórios (distribuição), risco da geração; e **WACC × múltiplo justo** — o WACC regulatório (nacional, série histórica, defasagem do ciclo) e a ponte com o valuation (EV/RAB ancorado em 1,0×, por que crescimento é alavanca e não fonte, comportamento *bond-like*) |
| **Internacional** | Seis eixos regulatórios (cost-based vs bid-based, nodal/zonal, energy-only vs capacidade, RIIO, abertura de varejo, camada supranacional); preços (varejo/atacado/tributos); preço negativo vs curtailment; armazenamento; casos de estresse (Uri, Ibéria, NEM); e as lições para o Brasil (copiar/evitar/preservar) |
| **Acompanhamento** | Monitoramento de curto prazo: cadeia causal do PLD, painel de indicadores diários com fontes primárias ao vivo (ONS/CCEE/ANEEL/INMET), playbook e armadilhas; + histórico e **sazonalidade** (ciclo úmido/seco, EAR mês a mês, consumo) e **eventos climáticos** (El Niño/La Niña, a fase ENSO de cada crise, rios voadores, mudança climática) |
| **Agenda regulatória** | O que está na mesa em 2026: a **antecipação do reconhecimento do CapEx** (lag regulatório, distribuição × transmissão, impactos) e o mapa das discussões — ressarcimento de curtailment, recalibração do PLD/CVaR, WACC, Fator X/TOTEX, CDE, RBSE, abertura do ACL, LRCAP de baterias |

## Fontes primárias

ONS · ANEEL · EPE (BEN 2026) · CCEE · MME · Eletronuclear · Planalto/Congresso · IEA · EIA · Eurostat · Ofgem · FERC.

## Notas técnicas

- Gráficos em **SVG inline** renderizados por JavaScript puro — sem CDN, sem bibliotecas. Funciona atrás de firewall corporativo.
- Fontes via Google Fonts com fallback de sistema (degrada sem quebrar).
- Dados de 2024–2026. Números-âncora são de fonte primária; alguns pontos iniciais de séries de tendência (curtailment 2022–23, ACL anos anteriores) são aproximados/ilustrativos e estão sinalizados.

---

*v2.2 · 30 jun 2026 — Próxima fase: empresas da cadeia (geração, transmissão, distribuição).*
