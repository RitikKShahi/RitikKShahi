\documentclass[a4paper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{xcolor}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{tabularx}

% ---------- COLOR ----------
\definecolor{accent}{HTML}{2563EB}

% ---------- PAGE STYLE ----------
\pagestyle{fancy}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% ---------- MARGINS ----------
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

% ---------- SECTION FORMAT ----------
\titleformat{\section}
  {\vspace{-4pt}\scshape\raggedright\large\bfseries\color{accent}}
  {}
  {0em}
  {}[\color{accent}\titlerule \vspace{-5pt}]

% ---------- BEGIN DOCUMENT ----------
\begin{document}

% ---------- NAME ----------
\begin{center}
    {\Huge \textbf{\color{accent} Ritik Kumar Shahi}}\\
    \vspace{4pt}
    Full Stack Developer | Competitive Programmer | System Enthusiast\\
    \vspace{4pt}
    \href{mailto:yourmail@gmail.com}{yourmail@gmail.com} $|$
    \href{https://github.com/YOUR_USERNAME}{github.com/YOUR_USERNAME} $|$
    \href{https://linkedin.com/in/ritik-kumar-shahi-792466288}{LinkedIn}
\end{center}

\vspace{6pt}

% ---------- SUMMARY ----------
\section{Summary}
Passionate Full Stack Developer with strong foundations in backend systems, operating systems concepts, and competitive programming. Experienced in building scalable applications and system-level projects using C, C++, and modern web technologies.

% ---------- SKILLS ----------
\section{Technical Skills}

\textbf{Languages:} C, C++, Java, JavaScript, Go \\
\textbf{Frontend:} HTML, CSS, React, Next.js, TailwindCSS \\
\textbf{Backend:} Node.js, Express.js, EJS \\
\textbf{Databases:} MongoDB, PostgreSQL, MySQL \\
\textbf{Tools:} Docker, Linux, Git, POSIX Sockets

% ---------- PROJECTS ----------
\section{Projects}

\textbf{Dynamic CSV Reader (C)}  
\begin{itemize}[leftmargin=*]
    \item Implemented efficient file parsing with dynamic memory allocation.
    \item Optimized for handling large datasets with minimal memory overhead.
\end{itemize}

\textbf{Shell Wars – Terminal Game (Raylib)}  
\begin{itemize}[leftmargin=*]
    \item Developed a custom terminal-based game using Raylib.
    \item Implemented event loops, rendering pipelines, and system-level input handling.
\end{itemize}

\textbf{Socket-Based Networking System}  
\begin{itemize}[leftmargin=*]
    \item Built TCP client-server architecture using POSIX sockets.
    \item Implemented low-level communication protocols and manual packet handling.
\end{itemize}

% ---------- EXPERIENCE ----------
\section{Experience}
\textbf{Full Stack Developer (College Projects)}  
\begin{itemize}[leftmargin=*]
    \item Built scalable web applications using MERN stack.
    \item Implemented authentication, routing, and database integration.
\end{itemize}

% ---------- ACHIEVEMENTS ----------
\section{Achievements}

\begin{itemize}[leftmargin=*]
    \item Solved 1000+ Data Structures and Algorithms problems.
    \item Active Competitive Programmer.
    \item Strong understanding of OS concepts and backend system design.
\end{itemize}

\end{document}
