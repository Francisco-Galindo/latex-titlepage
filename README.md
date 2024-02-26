# Title pages for my LaTex documents

Include this file via `input`

```tex
\documentclass{book}

% ...

\newcommand{\thedescription}{Description for my work} % Required!!
\newcommand{\theinstitution}{My institution} % Required!!
\title{My Title}
\author{Francisco Galindo}
\date{Some time}


\begin{document}
    \frontmatter

    \input{titlepage.tex}

    \tableofcontents

    \mainmatter

    % ...
\end{document}
```
