# BudouX-LaTeX

![](https://raw.githubusercontent.com/s417-lama/budoux-latex/main/concept.png)

## Usage

Put [budoux.sty](./budoux.sty) in your working directory and then,

```latex
\usepackage{budoux}

\begin{document}

\budoux{
  私はその人を常に先生と呼んでいた。
  だからここでもただ先生と書くだけで本名は打ち明けない。
  これは世間を憚かる遠慮というよりも、その方が私にとって自然だからである。
  私はその人の記憶を呼び起すごとに、すぐ「先生」といいたくなる。
  筆を執っても心持は同じ事である。
  よそよそしい頭文字などはとても使う気にならない。
}

\end{document}
```

In order to use BudouX-LaTeX,  you need to install the `budoux` command:
```sh
pip install budoux
```

Note that the `--shell-escape` option is required for LaTeX compilation, because BudouX-LaTeX uses the external shell command `budoux`.

- Sample LaTeX file: [./examples/example.tex](./examples/example.tex)
- Sample output pdf: [./examples/example.pdf](./examples/example.pdf)

## Reference

- BudouX: https://github.com/google/budoux
