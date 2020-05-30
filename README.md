# R Markdown and LaTeX typesetting
This is a guide for advanced typesetting with [R Markdown](https://github.com/rstudio/rmarkdown),
[LaTeX](https://www.latex-project.org/) and [Pandoc](https://pandoc.org/).

This is a work in progress. It mainly grows from my own searches and experiments,
finding examples, tools and best practices to create PDF documents that look really
good. This is an important step to communicate results from data science projects
effectively (as well as producing web content, of course).

I assume that you have some working knowledge about R Markdown and LaTeX. If that is
not the case, you should read some references first to get acquainted with these
technologies. See the **References** section below to get some reliable
pointers.

Hopefully, when this book is completed it will comprise templates, practical
advice, tips and best practices that you can readily incorporate in your documents.
In particular, I plan to focus on three well-known LaTeX document classes to
create handouts, articles and books:

* [Tufte-LaTeX](https://github.com/Tufte-LaTeX/tufte-latex): This project is
a collection of "LaTeX classes for producing handouts and books according to 
the style of Edward R. Tufte and Richard Feynman". They are already neatley
integrated in R Markdown, thanks to the [`tufte`](https://github.com/rstudio/tufte) R package.
The first part of this book will cover how to tweak and expand these classes
to change the aspect of your documents and add additional elements.
* [`memoir`](https://www.ctan.org/pkg/memoir): A LaTeX class that is easily
customizable and includes a ton of features from other packages, providing
a standard interface. It is one of the common options to create books
in LaTeX using advanced typesetting features.
* [`koma-script`](https://www.ctan.org/pkg/koma-script): KOMA-Script
is a bundle of classes and packages for advanced typesetting of articles, letters,
reports and books. It is also highly customizable, with a long list of
options to tweak almos every aspect of your documents.

In the end, I also plan to provide several templates based on the examples and
mini-projects included in the book, so you can readily experiment with them and
adapt the code to your own purposes.

## References

**Q&A sites**

* The [TeX - LaTeX site at SE](https://tex.stackexchange.com) is an invaluable resource
to find answers to many questions on your daily work with LaTeX (and even R Markdown too).
You can also find good advice from expert LaTeX users. I will refer to this
site as `TeX-SE`.

* Stack Overflow is another good source of useful answers and good advice on R Markdown.
You can start searching through [questions tagged as `r-markdown`](https://stackoverflow.com/questions/tagged/r-markdown).
I will refeer to this site as `SO-SE`.

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
you a bit more than the 139 minutes it says on its front page, but I always find
it an excellent resource to get a solid understanding of LaTeX principles, tools,
work flow and important packages. It also includes relevant information about
[`pdflatex`](https://www.overleaf.com/learn/latex/Articles%2FThe_TeX_family_tree:_LaTeX,_pdfTeX,_XeTeX,_LuaTeX_and_ConTeXt#pdfTeX)
and [`xelatex`](https://www.overleaf.com/learn/latex/XeLaTeX), two 
[LaTeX compilers](https://www.overleaf.com/learn/latex/Choosing%20a%20LaTeX%20Compiler) 
that produce PDF output.

* Another wonderful source is the [Overleaf LaTeX documentation](https://www.overleaf.com/learn/latex/Main_Page).
It has an extensive collection of articles explaining many aspects of LaTeX programming,
tools, work flow, etc. 

* Finally, more advanced users may also like the venerable [LaTeX Companion, 2ed](https://www.informit.com/store/latex-companion-9780201362992), written by some contributors to the LaTeX project.

* In [this TeX-SE question](https://tex.stackexchange.com/questions/262901/about-the-latex-companion-second-edition)
you can find some additional suggestions.
