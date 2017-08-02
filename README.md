This is a template and style file for LaTeX files for SPE publications. Adjustments to the article document class are made to make it compatible with the SPE publication format.

## After the documentclass is loaded, this file should be input
\documentclass[10pt,fleqn,twoside]{article}
\input{spej.tex}

## Title page should look like something like
\title{\TitleFont My Title \vspace*{-8pt}}  
\date{}   
\author{\AuthorFont \textbf{Author 1}, Affil 1; \textbf{Author 2} and \textbf{Author 3}, Affil 2}   
\maketitle  
\vspace*{-10pt}   
\thispagestyle{fancy}   
\let\thefootnote\relax\footnotetext{\CopyRightFont Copyright \textcopyright \ 2017 Society of Petroleum Engineers}   
\let\thefootnote\relax\footnotetext{\CopyRightFont Original SPE manuscript received for review XX YY 20ZZ. Revised manuscript received for review XX YY 20ZZ. Paper (SPE XX) peer approved XX YY 20ZZ.}

## The corresponding bibliography style should be called too.
\bibliographystyle{spej}
