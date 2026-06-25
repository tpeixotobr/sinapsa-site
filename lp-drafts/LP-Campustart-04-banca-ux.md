# Banca de UX — LP Campustart (etapa 4/5)

> Avaliação das 3 direções (`LP-Campustart-03-A/B/C`) por 4 lentes independentes.
> Notas de 0 a 10 por dimensão.

## Placar consolidado

| Lente | A · Sóbrio | B · Esportivo | C · Editorial |
|---|:--:|:--:|:--:|
| Clareza de mensagem / copy / conversão | **8,0** | 6,5 | 7,5 |
| Hierarquia visual / design / estética | 8,0 | 7,0 | **8,5** |
| Acessibilidade (WCAG AA) / técnico | **8,5** | 5,5 | 7,0 |
| Consistência de marca / adequação ao público | **9,0** | 5,0 | 6,0 |
| **Média** | **8,4** | 6,0 | 7,3 |

**Recomendação da banca:** **A (Sóbrio) como base**, incorporando o sistema de
notas de rodapé / honestidade de dados da **C** e uma dose controlada de energia
da **B** — sem adotar as rupturas de marca de B e C.

---

## A · Sóbrio — *o "no-regrets"* (média 8,4)
**Vence em marca, acessibilidade e conversão.**
- ✅ Única fiel ao brand kit: paleta navy/coral/violet + Archivo/IBM Plex Mono.
- ✅ Estrutura a11y completa (skip-link, `<main>`, landmarks, `aria-labelledby`, foco visível).
- ✅ Única com oferta segmentada por persona (empresa × universidade) e honestidade de prova ("referência da abordagem — não atribuída ao Campustart universitário").
- ⚠️ Hero conceitual e sem número de prova acima da dobra; CTA junta os dois públicos numa frase longa.
- ⚠️ Pode soar "deck institucional" para o público jovem (secundário).

## C · Editorial — *o mais sofisticado* (média 7,3)
**Vence em design/tipografia; melhor tratamento de informação (tabela + footnotes).**
- ✅ Maior refinamento visual e o melhor sistema de honestidade de dados (footnotes que isolam cada ressalva).
- ✅ Credibilidade premium para reitorias/ICTs.
- ⚠️ **Rompe o brand kit**: troca Archivo por Fraunces + Spectral (serifadas) — "não parece Sinapsa".
- ⚠️ Densa, pouco escaneável; CTAs fracos; apaga a energia/léxico esportivo do Campustart.
- ⚠️ Muito texto mono em cinza-claro (`--note`) abaixo de AA.

## B · Esportivo — *mais energia, mais risco* (média 6,0)
**Vence em impacto/personalidade; melhor gancho de atenção.**
- ✅ Hero "scoreboard" com a única prova numérica acima da dobra; abraça o léxico olímpico da marca.
- ⚠️ **Rompe o brand kit**: introduz fonte Anton e cores gold/lime fora da paleta.
- ⚠️ **Risco de credibilidade (apontado por 3 das 4 lentes):** o placar "ao vivo" piscante usa números da *Olimpíada de Energia 2022* (lastro, não Campustart universitário) — beira indução a erro.
- ⚠️ Caixa-alta generalizada + diagonais/clip-paths prejudicam legibilidade e a11y; sem skip-link e sem `<main>`.

---

## Achados transversais (valem para as 3)

1. **Contraste do coral `#E8694F`** falha AA como cor de texto e como fundo de botão
   (~3,0–3,5:1) nas três versões. **Corrigir na paleta-mãe** (ex.: escurecer texto/CTA
   para ~`#C9502F`) beneficia todas.
2. **`prefers-reduced-motion`**: só B trata (parcialmente). Adicionar bloco de redução.
3. **Nav some no mobile** sem menu alternativo em A e C.
4. **Números de lastro** (Olimpíada de Energia / Boticto) precisam de rótulo inequívoco
   de "referência da metodologia" em qualquer versão que os use — não atribuir ao
   Campustart universitário (liga-se à **lacuna 3**).

## Recomendação final
Seguir para a etapa 5 com a **A como base**, aplicando:
- importar o **sistema de footnotes/ressalvas da C**;
- importar **um número-âncora de prova** no topo (rotulado como lastro), inspirado na B;
- corrigir os achados transversais de contraste/motion/nav.
