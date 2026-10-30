# Comparação entre ações e FIIs

Artigo principal: [main.tex](./main.tex)  
Base de cálculo: [ativos.csv](./dados/ativos.csv)

## Compilação no Overleaf
- Compilador: pdfLaTeX
- Bibliografia: Biber

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

## Conteúdo consolidado
- Simulação de R$ 10.000 por ativo para 15 ações e 15 FIIs.
- Janela de dez anos: retorno total, patrimônio final e renda anual/mensal estimada pelo DY recente.
- Doze FIIs têm retorno total e DY numéricos nesta versão; HGRE11, HGCR11 e SDIL11 permanecem pendentes de validação.
- Janela de vinte anos discutida formalmente: não há retorno total homogêneo validado para os quinze papéis, nem quinze FIIs com vinte anos completos de histórico individual comparável.

## Ressalvas
Os valores históricos foram transcritos das bases indicadas no artigo e no CSV. O DY atual é uma fotografia retrospectiva, não garantia de renda. O artigo não extrapola o CAGR de dez anos para fabricar um resultado de vinte anos. Não é recomendação de investimento.
