# A CSUST Bachelor Thesis Template

Original repo: [csust-latex-sig/CSUSTBachelorThesis](https://github.com/csust-latex-sig/CSUSTBachelorThesis)

相比原仓库有一些改动没有上游化，相关 Issue 已提，但是没有下文，所以另起一个仓库。

本项目参考长沙理工大学官方提供的毕业论文 Word 模板设计了一份 LaTeX 模板，包括以下四份模板：
- 论文（[thesis.tex](thesis.tex)）
- 开题报告（[research_proposal.tex](research_proposal.tex)）
- 任务书（[task_book.tex](task_book.tex)）
- 外文译文及原文（[translation.tex](translation.tex)）

本项目为今后想使用 LaTeX 撰写毕业论文的学弟学妹们提供了一份参考，但模板本身还存在许多不足之处，
长理的论文撰写规范以后也可能会发生变化，因此本项目需要一届又一届长理学子接力维护和发展。

希望长理的 LaTeX 交流氛围越来越好，也欢迎加入[我们](https://github.com/csust-latex-sig)！

## 使用

- 编译论文：
  ```bash
  make thesis
  ```
- 编译开题报告：
  ```bash
  make research_proposal
  ```
- 编译任务书：
  ```bash
  make task_book
  ```
- 编译外文译文及原文：
  ```bash
  make translation
  ```
- 一次全部编译：
  ```bash
  make all
  ```
- 删除所有生成的文件（注意！也会删除生成的 PDF）：
  ```bash
  make clean
  ```
