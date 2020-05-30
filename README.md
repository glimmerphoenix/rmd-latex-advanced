# R Markdown and LaTeX typesetting
This is a guide for advanced typesetting with [R Markdown](https://github.com/rstudio/rmarkdown),
[LaTeX](https://www.latex-project.org/) and [Pandoc].

This is a work in progress. It mainly grows from my own searches and experiments,
trying to find examples, tools and best practices to create PDF documents that look really
good. This is an important step to communicate results from data science projects
effectively.

I assume that you have some working knowledge about RMarkdown and LaTeX. If that is
not the case, you should read some references first to get acquainted with these
technologies. See the **References** section below to get some reliable
pointers.

## References

**R Markdown**

* The book ["R Markdown: The Definitive Guide"] is a broad and accessible introduction
to R Markdown, co-authored by the leading developer of the project, 
[Yiui Xie](https://yihui.org/en/about/).

* There is also another good book that is currently under preparation:
["R Markdown Cookbook"](https://bookdown.org/yihui/rmarkdown-cookbook/). The book
is also co-authored by two lead developers of R Markdown packages.

**LaTeX**

* One of my favourite references to learn LaTeX is ["The Not So Short Introduction
to LaTeX 2e"](https://tobi.oetiker.ch/lshort/lshort.pdf). It may take
you a bit more than the 139 minutes shown on its front page, but I always find
it an excellent resource to get a solid understanding of LaTeX principles, tools,
work flow and important packages. It also includes relevant information about
[`pdflatex`](https://www.overleaf.com/learn/latex/Articles%2FThe_TeX_family_tree:_LaTeX,_pdfTeX,_XeTeX,_LuaTeX_and_ConTeXt#pdfTeX)
and [`xelatex`](https://www.overleaf.com/learn/latex/XeLaTeX), two 
[LaTeX compilers](https://www.overleaf.com/learn/latex/Choosing%20a%20LaTeX%20Compiler) 
that produce PDF output.

* Another wonderful source is the [Overleaf LaTeX documentation](https://www.overleaf.com/learn/latex/Main_Page).
It has an extensive collection of articles explaining many aspects of LaTeX programming,
tools, work flow, etc. 

* Finally, more advanced users may also like the venerable [LaTeX Companion, 2ed](https://www.informit.com/store/latex-companion-9780201362992), written by some contributors of the LaTeX project.
