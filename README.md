# test

Question : Create a LaTeX document on the topic "Importance of Mathematics in Science and Technology" using the following instructions:
Document formatting: Use the article document class and set the title, author and date.
Sections: Create a main section and at least two subsections.
Text formatting: Include bold, italic and underlined text.
Lists: Create both a numbered list and a bulleted list.
Mathematical equations: Insert at least three equations, including a fraction, square root and summation.
Tables: Create a table with 4 rows and 3 columns, including headings and borders.
Figures: Insert an image with a caption and label.
Equation numbering: Include a numbered equation and refer to it in the text.
Page formatting: Add a page break and page numbering.

Solution : 
\documentclass{article}

% Required package
\usepackage{graphicx}
\usepackage{amsmath}

% Title, author and date
\title{Importance of Mathematics in Science and Technology}
\author{Your Name}
\date{\today}

% Page numbering
\pagestyle{plain}

\begin{document}

% Display title
\maketitle

% Main section
\section{Introduction}

Mathematics plays an important role in science
and technology. It helps us understand natural
phenomena and solve complex problems.

\subsection{Importance in Science}

Mathematics is used in physics, chemistry and
other scientific fields. It helps scientists
perform calculations and analyze results.

\subsection{Importance in Technology}

Mathematics is essential in computer science,
engineering and artificial intelligence.

\textbf{Mathematics is the foundation of science.}

\textit{It helps us understand the universe.}

\underline{It is essential for technological progress.}

% Numbered list
\section{Applications of Mathematics}

\begin{enumerate}
    \item Mathematics is used in physics.
    \item Mathematics is used in chemistry.
    \item Mathematics is used in engineering.
\end{enumerate}

% Bulleted list
\subsection{Branches of Mathematics}

\begin{itemize}
    \item Algebra
    \item Geometry
    \item Calculus
    \item Statistics
\end{itemize}

% Mathematical equations
\section{Mathematical Equations}

Fraction:

\[
\frac{a}{b}=c
\]

Square root:

\[
\sqrt{x^2+y^2}
\]

Summation:

\[
\sum_{i=1}^{n}i=\frac{n(n+1)}{2}
\]

% Numbered equation
Einstein's energy equation is given below:

\begin{equation}
E=mc^2
\label{eq:energy}
\end{equation}

As shown in Equation~\ref{eq:energy},
energy is equal to mass multiplied by
the square of the speed of light.

% Table
\section{Applications Table}

\begin{center}
\begin{tabular}{|c|c|c|}
\hline
Subject & Application & Importance \\
\hline
Physics & Motion & High \\
\hline
Chemistry & Calculations & High \\
\hline
Engineering & Design & High \\
\hline
\end{tabular}
\end{center}

% Figure
\section{Mathematics and Technology}

\begin{figure}[h]
\centering
\includegraphics[width=0.5\textwidth]{math.jpg}
\caption{Mathematics in Science and Technology}
\label{fig:math}
\end{figure}

Figure~\ref{fig:math} illustrates the
importance of mathematics.

% Page break
\newpage

\section{Conclusion}

Mathematics is an essential part of science
and technology. It helps in research,
innovation, engineering and problem-solving.

Therefore, mathematics plays a major role
in the development of modern society.

\end{document}