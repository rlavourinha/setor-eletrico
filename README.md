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
| **Oferta & demanda** | Crescimento histórico, a curva do pato, os leilões (LRCAP, BESS), custo por fonte (LCOE), formação de preço pela geração marginal (merit order, canibalização, missing money) e o arco dos incentivos renováveis |
| **Mercado & preço** | ACR vs ACL, abertura do mercado livre, formação do PLD, risco hidrológico (MRE/GSF), bandeiras |
| **Regulação econômica** | Como cada segmento ganha dinheiro: RAP (transmissão), Parcela A/B + ativos regulatórios (distribuição), risco da geração |
| **Benchmark global** | Cost-based vs bid-based, Nord Pool, RIIO, PJM/ERCOT, Ibéria; preços internacionais; síntese crítica |

## Fontes primárias

ONS · ANEEL · EPE (BEN 2026) · CCEE · MME · Eletronuclear · Planalto/Congresso · IEA · EIA · Eurostat · Ofgem · FERC.

## Notas técnicas

- Gráficos em **SVG inline** renderizados por JavaScript puro — sem CDN, sem bibliotecas. Funciona atrás de firewall corporativo.
- Fontes via Google Fonts com fallback de sistema (degrada sem quebrar).
- Dados de 2024–2026. Números-âncora são de fonte primária; alguns pontos iniciais de séries de tendência (curtailment 2022–23, ACL anos anteriores) são aproximados/ilustrativos e estão sinalizados.

---

*v1.2 · 27 jun 2026 — Próxima fase: empresas da cadeia (geração, transmissão, distribuição).*
