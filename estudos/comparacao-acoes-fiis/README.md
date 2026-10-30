# Comparação entre ações e FIIs

Documento principal: `main.tex`.

## Compilação no Overleaf
- Compilador: pdfLaTeX
- Bibliografia: Biber

Sequência local:
```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

## Arquivos
- `main.tex`: manuscrito principal.
- `referencias.bib`: referências.
- `dados/ativos.csv`: universo candidato e campos para consolidação.
- `graficos/`: gráficos e documentação de figuras.

## Estado científico
A versão atual é um projeto de pesquisa em desenvolvimento. Os campos numéricos estão deliberadamente vazios: nenhum retorno ou DY deve ser inserido sem validação da fonte, da janela de cálculo e dos eventos corporativos. A lista de FIIs é candidata e precisa de auditoria individual de histórico e continuidade. Não é recomendação de investimento.
