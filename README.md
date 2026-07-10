# Setor Elétrico Brasileiro — Mapa do Sistema

Estudo de referência do setor elétrico brasileiro (Fases 1–3), construído **antes** do estudo das empresas da cadeia. Dashboard HTML autocontido, sem dependências externas de dados.

🔗 **Publicado em:** https://rlavourinha.github.io/setor-eletrico/

## O que cobre

| Aba | Conteúdo |
|-----|----------|
| **Visão geral** | As três camadas (física, comercial, regulatória), os números-chave do SIN, as **10 teses do estudo** ("Se você tem 15 minutos") e o **mapa da cadeia** — pools de receita por elo (RAP R$ 55 bi; Parcela B R$ 81 bi; geração ~R$ 150 bi), players da B3, réguas de valuation e o checklist da Fase 4 |
| **Contexto histórico** | O arco de 1879 a 2026: como cada instituição nasceu de uma crise, e por que o Brasil "desagrega" o que o mundo "agrega" (comparação institucional internacional) |
| **Instituições** | Quem planeja (EPE), opera (ONS), regula (ANEEL) e liquida (CCEE) |
| **Sistema físico** | Matriz, reservatórios como "bateria", os 4 submercados, despacho por custo (NEWAVE→DECOMP→DESSEM), curtailment |
| **Oferta & demanda** | Crescimento histórico, a curva do pato, os leilões (LRCAP, BESS), o aprofundamento **capacidade × potência** (os dois lastros — energia vs. potência —, a fórmula da disponibilidade, o crédito de capacidade/ELCC, a evolução do LRCAP de 2021 a 2026 + baterias, as trajetórias do déficit de potência até 2034, e **se o LRCAP resolve** — cronograma de entrega, o resíduo de 2032–34 e a necessidade de novos leilões), custo por fonte (LCOE), formação de preço pela geração marginal (merit order, canibalização, missing money), a teoria curto × longo prazo (SRMC/LRMC, curva de triagem, a reconciliação) e o arco dos incentivos renováveis |
| **Geração** | Quanto custa e quanto demora construir (CAPEX/prazo/fator de capacidade por fonte), o ciclo de caixa (curva J), o financiamento (project finance, BNDES, debêntures incentivadas), por que o Brasil parou de construir grandes hidrelétricas (+ UHR reversíveis) e o **aprofundamento de armazenamento**: o desenho do leilão de baterias de dez/2026, o *revenue stacking* (por que o Brasil entra pela capacidade e não pela arbitragem — PLD no piso, saturação no ERCOT/GB), o colapso do custo do BESS, e a UHR como armazenamento de longa duração (Roadmap EPE 2025, BESS × UHR) |
| **Mercado & preço** | ACR vs ACL, abertura do mercado livre, formação do PLD, risco hidrológico (MRE/GSF), bandeiras e a **comercialização — o elo órfão** (506 agentes, as ondas de quebras, a abertura de 2027–28 e o SUI) |
| **Regulação econômica** | Como cada segmento ganha dinheiro: RAP (transmissão), Parcela A/B + ativos regulatórios (distribuição), risco da geração; e **WACC × múltiplo justo** — o WACC regulatório (nacional, série histórica, defasagem do ciclo) e a ponte com o valuation (EV/RAB ancorado em 1,0×, por que crescimento é alavanca e não fonte, comportamento *bond-like*); os **três tipos de contrato de transmissão** (degrau do 16º ano, reforços & melhorias, IGP-M×IPCA, pipeline) e a **anatomia da CDE** (trajetória 2013–26, rubricas, o teto de 2027/ECR) |
| **Internacional** | Seis eixos regulatórios (cost-based vs bid-based, nodal/zonal, energy-only vs capacidade, RIIO, abertura de varejo, camada supranacional); preços (varejo/atacado/tributos); preço negativo vs curtailment; armazenamento; casos de estresse (Uri, Ibéria, NEM); e as lições para o Brasil (copiar/evitar/preservar) |
| **Acompanhamento** | Monitoramento de curto prazo: cadeia causal do PLD, painel de indicadores diários com fontes primárias ao vivo (ONS/CCEE/ANEEL/INMET), playbook e armadilhas; + histórico e **sazonalidade** (ciclo úmido/seco, EAR mês a mês, consumo) e **eventos climáticos** (El Niño/La Niña, a fase ENSO de cada crise, rios voadores, mudança climática) |
| **Agenda regulatória** | O que está na mesa em 2026: a **antecipação do reconhecimento do CapEx** (lag regulatório, distribuição × transmissão, impactos) e o mapa das discussões — ressarcimento de curtailment, recalibração do PLD/CVaR, WACC, Fator X/TOTEX, CDE, RBSE, abertura do ACL, LRCAP de baterias |

## Fontes primárias

ONS · ANEEL · EPE (BEN 2026) · CCEE · MME · Eletronuclear · Planalto/Congresso · IEA · EIA · Eurostat · Ofgem · FERC.

## Navegação (v3.0)

- **Deep-link por hash**: `#aba` ou `#aba/seção` (ex.: `…/#regulacao/regulacao-wacc`) — favoritável e compartilhável; F5 preserva o lugar.
- **"Nesta aba"**: sumário automático no topo de cada aba longa; botão ↑ flutuante.
- **Glossário**: 33 siglas com tooltip na primeira ocorrência por aba + lista completa no rodapé.
- **"Se você tem 15 minutos"**: as 10 teses do estudo, na Visão geral, com links.
- **Chips 📌**: valores conjunturais carregam a data de referência (âmbar quando envelhecidos); a ausência do chip significa dado estrutural.

## Notas técnicas

- Gráficos em **SVG inline** renderizados por JavaScript puro — sem CDN, sem bibliotecas. Funciona atrás de firewall corporativo.
- Fontes via Google Fonts com fallback de sistema (degrada sem quebrar).
- Dados de 2024–2026. Números-âncora são de fonte primária; alguns pontos iniciais de séries de tendência (curtailment 2022–23, ACL anos anteriores) são aproximados/ilustrativos e estão sinalizados.

---

*v3.3 · 08 jul 2026 — Próxima fase: empresas da cadeia (geração, transmissão, distribuição).*
