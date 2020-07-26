---
title: "1 Generative Models for Discrete Data"
output: html_notebook
---

In molecular biology, many situations involve counting events: how many codons use a certain spelling, how many reads of DNA match a reference, how many CG digrams are observed in a DNA sequence. These counts give us *discrete* variables, as opposed to quantities such as mass and intensity that are measured on *continuous* scales.

分子生物学では、多くの状況でカウントイベントが発生します: 特定のスペルを使用するコドンの数、リファレンスと一致するDNAのリード数、DNAシーケンスで観察されるCG2文字組の数。 *連続*スケールで測定される質量や強度などの量とは対照的に、これらのカウントは*離散*変数を提供します。

If we know the rules that the mechanisms under study follow, even if the outcomes are random, we can generate the probabilities of any events we are interested in by computations and standard probability laws. This is a *top-down* approach based on deduction and our knowledge of how to manipulate probabilities. In Chapter 2, you will see how to combine this with data-driven (*bottom-up*) statistical modeling.

調査中のメカニズムが従う規則がわかっている場合、結果がランダムであっても、計算と標準確率法則によって、関心のあるイベントの確率を生成できます。 これは、推論と確率の操作方法に関する知識に基づく*トップダウン*アプローチです。第2章では、これをデータ駆動型（ボトムアップ）統計モデリングと組み合わせる方法について説明します。
