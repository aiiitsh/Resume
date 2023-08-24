%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,10pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}


\usepackage{xcolor}

\definecolor{hyber}{HTML}{BE3455}

\usepackage{xcolor}
% \usepackage{hyperref}

% \hypersetup{
%     colorlinks=true,
%     linkcolor=blue,
%     urlcolor=hyber,
%     citecolor=blue
% }


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small #3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small #1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      #1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}


\begin{center}
    \textbf{\huge \scshape Ahmed Hesham Hassan} \\ \vspace{1pt}
    \href{mailto:ahesham368@gmail.com}{{  \small \underline {ahesham368@gmail.com}}} $|$ 
    \small +20 1024204493 $| $ 
    \href{https://www.linkedin.com/in/aiiitsh/}{{ \small 
 \underline{LinkedIn}}} $| $
 \href{https://www.behance.net/aiiitsh}{{ \small 
 \underline{Design Portfolio}}} $| $
 \href{https://github.com/aiiitsh}{{ \small \underline{GitHub}}} 
    
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Helwan University}{Cario, Egypt}
      {Computer Engineering, Grade: \textbf{A-}}{Expected Jul 2025}
        \resumeItemListStart
        \resumeItem{Relevant Coursework: Data structures, Algorithms, Microprocessors and Micro-controllers, DBMS, and OOP.}
        \resumeItem{Created 4 digital arts committees with 100+ students, by heading the arts department in the student union.}
      \resumeItemListEnd

    % \vspace{1pt}
    \resumeSubheading
      {Kazan Federal University}{Kazan, Russia}
      {Digital Economy - Summer University}{Jul 2023}
        \resumeItemListStart
        \resumeItem{Orchestrated an AI-driven media agency's start-up, from idea selection and prototyping to the go-to-market strategy, securing second place among 340+ peers in the pitching competition.}
      \resumeItemListEnd
  \resumeSubHeadingListEnd


%-----------EXPERIENCE-----------
\section{Experience}
  \resumeSubHeadingListStart
  
    \resumeSubheading
      {Software Engineering Intern }{Jul 2023–Aug 2023}
      {Vodafone}{Cairo, Egypt}
      \resumeItemListStart
        \resumeItem{Created a \textbf{Django}, dynamic platform to filter \textbf{100k+} tuples, integrating \textbf{Pandas}, \textbf{Plotly}, and \textbf{Numpy} for data analysis and representation and employed HTML, CSS, and Bootstrap for seamless frontend interaction.}
        \resumeItem{Created an interactive \textbf{Streamlit} webpage, enhancing insights extraction from datasets exceeding \textbf{80k+} tuples.}
        
        
    \resumeItemListEnd
    % \vspace{1pt}
%ITI
    \resumeSubheading
      {Software Engineering Intern }{Aug 2023}
      {The Information Technology Institute (ITI)}{Cairo, Egypt}
      \resumeItemListStart
        \resumeItem{Enhanced workflow efficiency for architecture engineers creating a \textbf{React Native} application, Benud.}
        \resumeItem{Collaborated with a cross-functional team to gather requirements, construct the architecture, design the UI/UX, and choose the stack, enabling the users to access it on the \textbf{Google Play store. }}   
    \resumeItemListEnd
  
%Veribuy
\resumeSubheading
      {Founding Software Engineer}{Dec 2022–Jul 2023}
      {VeriBuy }{San Francisco, CA}
      \resumeItemListStart
        \resumeItem{Developed a social commerce marketplace using \textbf{React Native}, \textbf{Firebase}, and \textbf{Redux} for \textbf{iOS} and \textbf{Android}.}
        \resumeItem{Held 120+ market research interviews to design a sufficient application’s UI/ UX, architecture, and brand identity, reducing MVP launch time by 25\% using Agile/ Scrum methodologies. } 
        \resumeItem{Received recognition as one of the top \textbf{10\%} applicants for \textbf{Y-Combinator's} S22 \& S23 batches.}
    \resumeItemListEnd

%Gaimiz
\resumeSubheading
      {Founding Software Engineer and Start-up Lead}{Oct 2020–Mar 2023}
      {Gaimiz}{Cairo, Egypt}
      \resumeItemListStart
        \resumeItem{Generated \textbf{\$3K+} in revenue by leading a cross-functional team of \textbf{13} members iterating on process automation.}
        \resumeItem{Drove product popularity with a strategic plan targeting all university campuses and offline retailers.} 
        \resumeItem{Increased user engagement by creating a captivating \textbf{Figma} UI/UX, front-end, and brand identity for the website.}
    \resumeItemListEnd
    
  \resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
    \resumeSubHeadingListStart
%White Jack
      \resumeProjectHeading
          {\textbf{WhiteJack} $|$ \textit{Java}}{}
          \resumeItemListStart
            \resumeItem{Led the development of the game from scratch with my team and coded the GUI.}
            \resumeItem{Designed the game's user UI/UX, including creating all the necessary icons and buttons, and created a promotional video for the game.}
          \resumeItemListEnd

%Bill Splitter
      \resumeProjectHeading
          {\textbf{Bill Splitter} $|$ \textit{Flutter, Dart}}{}
          \resumeItemListStart
            \resumeItem{Built a cross-platform application for Android and iOS utilizing Flutter and Dart.}
            \resumeItem{Designed a full-interactive demo on Adobe XD conducting 10+ interviews to achieve UI/UX simplicity.}
            
            
          \resumeItemListEnd

%Digital Clock
      \resumeProjectHeading
          {\textbf{DIGITAL-CLOCK} $|$ \textit{C, Microprocessor)}}{}
          \resumeItemListStart
            \resumeItem{Collaborated with 4 engineering students to develop an interactive digital clock using ATMEGA32 with a range of features such as temperature sensing, light control, humidity sensing, a timer, an alarm, a stopwatch, leap year detection, and the potential for a calendar.}
          \resumeItemListEnd
%Clinic Data Management
      \resumeProjectHeading
          {\textbf{Clinic Data Management} $|$ \textit{C++)}}{}
          \resumeItemListStart
            \resumeItem{Collaborated with 4 students to develop a comprehensive system to manage medical data, including patient records, billing, and appointments incorporating Object Oriented Programming, multi-threading, and memory management.}
          \resumeItemListEnd


    \resumeSubHeadingListEnd




%
%-----------PROGRAMMING SKILLS-----------
\section{Skills \& Courses}
 \begin{itemize}[leftmargin=0.15in, label={}]
    {\item{
     \textbf{Technical}{: C/C++, Python, SQL, JavaScript, HTML/CSS, Java, React Native,VHDL, Flutter, Git, Django.} \\
     \textbf{Business \& Design}{: SCRUM, Agile methodologies, Microsoft Office Suit, Figma, XD, Photoshop, Illustrator, Premiere.} \\
     \textbf{Courses}{: Harvard: LBTECHX1, SW47X. USCANDIEGO: Algorithmic Toolbox, Data structures and algorithms. Wharton: Full entrepreneurship specialization of 5 courses. OpenClassrooms: Agile/ Scrum.} \\
    }}
 \end{itemize}

%-------------------------------------------
\end{document}
