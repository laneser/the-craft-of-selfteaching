# the-craft-of-selfteaching

> One has no future if one couldn't teach themself<a href='#fn1' name='fn1b'><sup>[1]</sup></a>.

# 自學是門手藝

> 沒有自學能力的人沒有未來

**作者：李笑來**

特別感謝**霍炬**（[@virushuo](https://github.com/virushuo)）、**洪強寧**（[@hongqn](https://github.com/hongqn))兩位良師諍友在此書寫作過程中給予我的巨大幫助！

```python
# pseudo-code of selfteaching in Python

def teach_yourself(anything):
    while not create():
        learn()
        practice()
    return teach_yourself(another)

teach_yourself(coding)
```

本書可以搭配 google research colab 直接線上執行, 舉例
[Part.1.E.1.entrance（**入口**）](Part.1.E.1.entrance.ipynb)
的 study branch 可以直接使用 <https://colab.research.google.com/github/laneser/the-craft-of-selfteaching/blob/study/Part.1.E.1.entrance.ipynb>
而且 colab 上面改完還可以存回 gitlab ! 唯一缺點是使用的檔案都需要透過網路而不是原本的 local storage.

有興趣幫忙的朋友，請先行閱讀 [如何使用 Pull Request 為這本書校對](02.proof-of-work.ipynb)。

2019 年 3 月 23 日，新增 Markdown 版本：

> https://github.com/selfteaching/the-craft-of-selfteaching/tree/master/markdown

### 目錄

> - [01.preface（**前言**）](01.preface.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/laneser/the-craft-of-selfteaching/blob/study/01.preface.ipynb)
> - [02.proof-of-work（**如何證明你真的讀過這本書？**）](02.proof-of-work.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/laneser/the-craft-of-selfteaching/blob/study/02.proof-of-work.ipynb)
> - [Part.1.A.better.teachyourself（**為什麼一定要掌握自學能力？**）](Part.1.A.better.teachyourself.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/laneser/the-craft-of-selfteaching/blob/study/Part.1.A.better.teachyourself.ipynb)
> - [Part.1.B.why.start.from.learning.coding（**為什麼把編程當作自學的入口？**）](Part.1.B.why.start.from.learning.coding.ipynb)
> - [Part.1.C.must.learn.sth.only.by.reading（**只靠閱讀習得新技能**）](Part.1.C.must.learn.sth.only.by.reading.ipynb)
> - [Part.1.D.preparation.for.reading（**開始閱讀前的一些準備**）](Part.1.D.preparation.for.reading.ipynb)
> - [Part.1.E.1.entrance（**入口**）](Part.1.E.1.entrance.ipynb)
> - [Part.1.E.2.values-and-their-operators（**值及其相應的運算**）](Part.1.E.2.values-and-their-operators.ipynb)
> - [Part.1.E.3.controlflow（**流程控制**）](Part.1.E.3.controlflow.ipynb)
> - [Part.1.E.4.functions（**函數**）](Part.1.E.4.functions.ipynb)
> - [Part.1.E.5.strings（**字符串**）](Part.1.E.5.strings.ipynb)
> - [Part.1.E.6.containers（**數據容器**）](Part.1.E.6.containers.ipynb)
> - [Part.1.E.7.files（**文件**）](Part.1.E.7.files.ipynb)
> - [Part.1.F.deal-with-forward-references（**如何從容應對含有過多“過早引用” 的知識？**）](Part.1.F.deal-with-forward-references.ipynb)
> - [Part.1.G.The-Python-Tutorial-local（**官方教程：The Python Tutorial**）](Part.1.G.The-Python-Tutorial-local.ipynb)
> - [Part.2.A.clumsy-and-patience（**笨拙與耐心**）](Part.2.A.clumsy-and-patience.ipynb)
> - [Part.2.B.deliberate-practicing（**刻意練習**）](Part.2.B.deliberate-practicing.ipynb)
> - [Part.2.C.why-start-from-writing-functions（**為什麼從函數開始？**）](Part.2.C.why-start-from-writing-functions.ipynb)
> - [Part.2.D.1-args（**關於參數（上）**）](Part.2.D.1-args.ipynb)
> - [Part.2.D.2-aargs（**關於參數（下）**）](Part.2.D.2-aargs.ipynb)
> - [Part.2.D.3-lambda（**化名與匿名**）](Part.2.D.3-lambda.ipynb)
> - [Part.2.D.4-recursion（**遞歸函數**）](Part.2.D.4-recursion.ipynb)
> - [Part.2.D.5-docstrings（**函數的文檔**）](Part.2.D.5-docstrings.ipynb)
> - [Part.2.D.6-modules（**保存到文件的函數**）](Part.2.D.6-modules.ipynb)
> - [Part.2.D.7-tdd（**測試驅動的開發**）](Part.2.D.7-tdd.ipynb)
> - [Part.2.D.8-main（**可執行的 Python 文件**）](Part.2.D.8-main.ipynb)
> - [Part.2.E.deliberate-thinking（**刻意思考**）](Part.2.E.deliberate-thinking.ipynb)
> - [Part.3.A.conquering-difficulties（**戰勝難點**）](Part.3.A.conquering-difficulties.ipynb)
> - [Part.3.B.1.classes-1（**類 —— 面向對象編程**）](Part.3.B.1.classes-1.ipynb)
> - [Part.3.B.2.classes-2（**類 —— Python 的實現**）](Part.3.B.2.classes-2.ipynb)
> - [Part.3.B.3.decorator-iterator-generator（**函數工具**）](Part.3.B.3.decorator-iterator-generator.ipynb)
> - [Part.3.B.4.regex（**正則表達式**）](Part.3.B.4.regex.ipynb)
> - [Part.3.B.5.bnf-ebnf-pebnf（**BNF 以及 EBNF**）](Part.3.B.5.bnf-ebnf-pebnf.ipynb)
> - [Part.3.C.breaking-good-and-bad（**拆解**）](Part.3.C.breaking-good-and-bad.ipynb)
> - [Part.3.D.indispensable-illusion（**剛需幻覺**）](Part.3.D.indispensable-illusion.ipynb)
> - [Part.3.E.to-be-thorough（**全面 —— 自學的境界**）](Part.3.E.to-be-thorough.ipynb)
> - [Part.3.F.social-selfteaching（**自學者的社交**）](Part.3.F.social-selfteaching.ipynb)
> - [Part.3.G.the-golden-age-and-google（**這是自學者的黃金時代**）](Part.3.G.the-golden-age-and-google.ipynb )
> - [Part.3.H.prevent-focus-drifting（**避免注意力漂移**）](Part.3.H.prevent-focus-drifting.ipynb)
> - [Q.good-communiation（**如何成為優秀溝通者**）](Q.good-communiation.ipynb)
> - [R.finale（**自學者的終點**）](R.finale.ipynb)
> - [S.whats-next（**下一步幹什麼？**）](S.whats-next.ipynb)
> - [T-appendix.editor.vscode（**Visual Studio Code 的安裝與配置**）](T-appendix.editor.vscode.ipynb)
> - [T-appendix.git-introduction（**Git 簡介**）](T-appendix.git-introduction.ipynb)
> - [T-appendix.jupyter-installation-and-setup（**Jupyterlab 的安裝與配置**）](T-appendix.jupyter-installation-and-setup.ipynb)
> - [T-appendix.symbols（**這些符號都代表什麼？**）](T-appendix.symbols.ipynb)


本書的版權協議為 [CC-BY-NC-ND license](https://creativecommons.org/licenses/by-nc-nd/3.0/deed.zh)。

![CC-BY-NC-ND](images/CC-BY-NC-ND.png?raw=true)

-----
**註解**

<a name='fn1'>[1]</a>：['Themselves' or 'themself'? -- Oxford Dictionary](https://en.oxforddictionaries.com/usage/themselves-or-themself)

<a href='#fn1b'><small>↑Back to Content↑</small></a>
