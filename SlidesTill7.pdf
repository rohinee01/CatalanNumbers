\documentclass[handout, dvipsnames]{beamer}
\mode<presentation>{}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amssymb, amsfonts, amsthm, mathtools, mathrsfs}
\setbeamertemplate{theorems}[numbered]
\title{Catalan Numbers}
\author{Maths and Physics Club}
\date[23-08-2020]{23rd August 2020}
\institute[IITB]{IIT Bombay}
\usetheme{Warsaw}
% \usecolortheme{beetle}
\usepackage{graphicx}

\newcommand{\id}{\operatorname{id}}
\renewcommand{\exp}{\operatorname{exp}}

\theoremstyle{definition}
\newtheorem{defn}{Definition}
\newtheorem{prop}{Proposition}
\newtheorem{thm}{Theorem}

%Slide 1
\begin{document}
\begin{frame}
    \titlepage
\end{frame}

%slide 2
\begin{frame}{Introduction}
    %yet to decide
\end{frame}

%slide 3
\begin{frame}{Polygon Triangulation}
For n$\geq$3, let $C_{n-2}^1$ denotes the number of ways to \emph{triangulate} a n-sided convex polygon. Find $C_{n-2}^1$ for n$\geq$3. 
\begin{figure}
    \centering
    \includegraphics[width=7.5 cm]{PolyTriang.png}
    \caption{Illustration for small values of n}
    \label{fig:PolyTriang}
\end{figure}
\end{frame}

%slide 4
\begin{frame}{Approach- Recursion!!!}
    \begin{enumerate}
        \uncover<2->{\item Define $C_0^1=$1 for n$=$2. (Why?)}
        \uncover<3->{\item For a given polygon of n$\geq$3 vertices, Fix an edge, and consider the triangle containing that edge. ($n-2$ ways)
        \begin{figure}
            \centering
            \includegraphics[width=4cm]{PolyTri2.JPG}
            \caption{Illustration for $n=8$}
            \label{fig:PolyTri2}
        \end{figure}}
        \uncover<4->{\item Triangulate \emph{left} k gon in $C_{k-2}^1$ ways, and \emph{right} $n-k+1$ gon in $C_{n-k-1}^1$ ways.}
        \uncover<5->{\item Combine! ($C_{k-2}^1 C_{n-k-1}^1$ ways)}
        \uncover<6->{\item Sum it over $n-2$ expressions}
    \end{enumerate}
\end{frame}

%slide 5
\begin{frame}{Polygon Triangulation-Recursion}
    Define $C_0^1=$1.\\
    For n$\geq$3, let $C_{n-2}^1$ denotes the number of ways to triangulate a n-sided convex polygon.\\\\
    Then the sequence $\{C_n^1\}_{n=0}^\infty$ is given by,  
    $$C_{n-2}^1 = \sum_{k = 0}^{n-1}\ C_{k-2}^1 C_{n-k-1}^1$$. 
\end{frame}

%slide 6
\begin{frame}{Hands across a table}
    For n$\geq$1, suppose $2n$ people are sitting around a round table. Let $C_n^2$ denotes the number of ways in which all of them be can simultaneously shake hands with another person at the table in such a way that none of the arms cross each other. Find $C_n^2$.
    \begin{figure}
        \centering
        \includegraphics[width=7.5cm]{HandCross.JPG}
        \caption{Illustration for small values of n}
        \label{fig:my_label}
    \end{figure}
\end{frame}

%slide 7
\begin{frame}{Approach- again recursion!}
    \begin{enumerate}
        \uncover<2->{\item Again define $C_0^2=$1 for n$=$0. (Why?)}
        \uncover<3->{\item For a given n$\geq$1, Choose a pair. Legal pattern: even number of pairs on each side.}
        \uncover<4->{\item Again recursion!\\
        k pairs on the left \longrightarrow $C_{k}^2$ ways.\\ 
        $n-k+1$ pairs on right \longrightarrow $C_{n-k-1}^2$ ways.}
        \uncover<5->{\item Combine! ($C_{k}^2 C_{n-k-1}^2$ ways)}
        \uncover<6->{\item Sum it over all $n$ expressions.}
        \uncover<7->{\item Recurrence relation $$C_{n}^2 = \sum_{k = 0}^{n-1}\ C_{k}^2 C_{n-k-1}^2$$.}
        \uncover<8->{\item Analogy with $\{C_n^1\}_{n=0}^\infty$ ??!}
    \end{enumerate}
\end{frame}

%Sangraam Slides


\end{document}

