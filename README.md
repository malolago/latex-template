# README

## To use
Copy and paste the following cmd in the directory:
```powershell
git clone https://github.com/malolago/latex-template.git .
```

## To include in your project

### With header
Just use 
```latex
\input{Template}
```
at the beggining of your file, then 
```latex
\begin{document}
...
\end{document}
```

### Without header
Use
```latex
\usepackage{Style}
```
(for boxes)
and
```latex
\usepackage{Commands}
```
(for custom commands)