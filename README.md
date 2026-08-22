\documentclass[9pt,a4paper]{article}

%================================================
% PACKAGES
%================================================
\usepackage[
    left=0.42in,
    right=0.42in,
    top=0.34in,
    bottom=0.32in
]{geometry}

\usepackage[T1]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage{lmodern}
\usepackage{microtype}
\usepackage{xcolor}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{tabularx}
\usepackage{array}
\usepackage{ragged2e}
\usepackage{hyperref}
\usepackage{fontawesome5}

%================================================
% COLORS
%================================================
\definecolor{primary}{HTML}{1769AA}
\definecolor{accent}{HTML}{0B84F3}
\definecolor{dark}{HTML}{1F2937}
\definecolor{textgray}{HTML}{4B5563}
\definecolor{lightgray}{HTML}{6B7280}
\definecolor{linegray}{HTML}{D9E2EC}
\definecolor{softblue}{HTML}{EAF4FF}

%================================================
% PAGE
%================================================
\pagestyle{empty}

\setlength{\parindent}{0pt}
\setlength{\parskip}{0pt}

%================================================
% HYPERLINKS
%================================================
\hypersetup{
    colorlinks=true,
    urlcolor=primary,
    linkcolor=primary
}

%================================================
% SECTION STYLE
%================================================
\titleformat{\section}
{\color{dark}\large\bfseries}
{}
{0pt}
{}
[\vspace{-4pt}\color{primary}\rule{\linewidth}{1.2pt}]

\titlespacing*{\section}
{0pt}
{4pt}
{2pt}

%================================================
% BULLETS
%================================================
\setlist[itemize]{
    leftmargin=13pt,
    itemsep=0pt,
    topsep=1pt,
    parsep=0pt,
    partopsep=0pt
}

%================================================
% CUSTOM COMMANDS
%================================================
\newcommand{\projecttitle}[2]{
    \textbf{\large #1}
    \hfill
    {\color{primary}\textbf{#2}}
}

\newcommand{\entrytitle}[2]{
    \textbf{#1}
    \hfill
    {\color{primary}\textbf{#2}}
}

\newcommand{\skillline}[2]{
    \textbf{#1} \hspace{2pt} #2
}

%================================================
% DOCUMENT
%================================================
\begin{document}

%================================================
% HEADER
%================================================

\begin{center}

{\fontsize{23}{24}\selectfont\bfseries\color{dark} SK ISMAIL}

\vspace{1pt}

{\normalsize\bfseries\color{primary}
Data Analyst \;|\; Machine Learning Enthusiast}

\vspace{4pt}

{\small
\faPhone\; +91 8249511537
\quad
\textcolor{linegray}{|}
\quad
\faEnvelope\; \href{mailto:skismailkhan256@gmail.com}
{skismailkhan256@gmail.com}
\quad
\textcolor{linegray}{|}
\quad
\faLinkedin\; \href{https://www.linkedin.com/in/sk-ismail-738bb736a}
{linkedin.com/in/sk-ismail-738bb736a}
\quad
\textcolor{linegray}{|}
\quad
\faGithub\; \href{https://github.com/skismailkhan256-source}
{skismailkhan256-source}
}

\vspace{4pt}

\color{primary}\rule{0.88\linewidth}{1.2pt}

\end{center}

%================================================
% PROFILE SUMMARY
%================================================

\section*{Profile Summary}

{\small
Aspiring Data Analyst and Machine Learning enthusiast with hands-on experience in data analysis, data cleaning, exploratory data analysis (EDA), data visualization, dashboard development, and machine learning. Skilled in Python, SQL, Power BI, Tableau, and Excel, with practical experience in statistical analysis, data preprocessing, KPI reporting, and data-driven problem solving. Currently pursuing MCA with a specialization in Machine Learning and seeking opportunities to apply analytical and technical skills to real-world business problems.
}

%================================================
% EDUCATION
%================================================

\section*{Education}

\entrytitle{Master of Computer Applications (MCA)}{2025--2027}

Centurion University, Jatani, Bhubaneswar, Odisha
\hfill
\textbf{CGPA: 8.35/10}

\vspace{1pt}

\entrytitle{Bachelor of Science (B.Sc.) -- Botany Honours}{2022--2025}

A.P. College, Raruan, Mayurbhanj, Odisha
\hfill
\textbf{74.36\%}

\vspace{1pt}

\entrytitle{Higher Secondary (12th) -- Science}{2022}

Gorumahisani Iron Higher Secondary School, Mayurbhanj, Odisha
\hfill
\textbf{61.33\%}

\vspace{1pt}

\entrytitle{High School Certificate (10th)}{2020}

Rairangpur High School, Rairangpur, Mayurbhanj, Odisha
\hfill
\textbf{50.50\%}

%================================================
% INTERNSHIP
%================================================

\section*{Internship}

\entrytitle{Data Analytics Intern -- Data Analysis \& Reporting}
{May 2025--June 2025}

\textbf{Central Tool Room \& Training Centre (CTTC), Bhubaneswar, Odisha}

\begin{itemize}
    \item Processed and organized 5,000+ records with focus on accuracy, consistency, and data quality, reducing data errors by \textasciitilde20\%.
    \item Built Excel macro-driven templates to automate recurring reporting tasks, cutting manual prep time by \textasciitilde30\%.
    \item Prepared scheduled reports and interactive dashboards to support timely, data-driven decision-making.
    \item Communicated analytical findings through structured reports and presentations for non-technical audiences.
    \item Collaborated with a cross-functional team of 4+ members to complete analytics tasks within deadlines.
\end{itemize}

%================================================
% PROJECTS
%================================================

\section*{Projects}

\projecttitle{Clipkart Sales Analytics Dashboard}{Aug 2026}

{\small\textit{\color{textgray}Power BI \;|\; Power Query \;|\; Excel}}

\begin{itemize}
    \item Cleaned, transformed, and validated raw e-commerce sales data using Power Query for analysis and dashboard development.
    \item Built an interactive Power BI dashboard with 5+ KPIs to monitor revenue, orders, quantity, average order value, and top product performance.
    \item Analyzed revenue across product categories, top-performing products, and cities using charts, tables, filters, and KPI visualizations.
    \item Generated data-driven insights on sales performance, category contribution, regional performance, and price-revenue relationships to support business decision-making.
\end{itemize}

\vspace{1pt}

\projecttitle{Movie Recommendation System}{In Progress}

{\small\textit{\color{textgray}Python \;|\; KNN \;|\; Pandas \;|\; Movie API}}

\begin{itemize}
    \item Developed a movie recommendation system using the K-Nearest Neighbors (KNN) algorithm.
    \item Processed and analyzed 4,000+ movie records using Python for data preprocessing and recommendation analysis.
    \item Integrated an external movie API to retrieve posters and additional movie information.
    \item Generated Top 5 personalized movie recommendations based on user preferences and similarity analysis.
\end{itemize}

%================================================
% TECHNICAL SKILLS
%================================================

\section*{Technical Skills}

\begin{tabularx}{\linewidth}{@{}>{\bfseries\color{primary}}p{1.25in} X@{}}

Programming
&
Python, SQL, Java, C
\\[1.5pt]

Data Analytics
&
Data Analysis, Data Cleaning, EDA, Data Preprocessing, Statistical Analysis
\\[1.5pt]

Libraries
&
Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
\\[1.5pt]

Machine Learning
&
Regression, Classification, Decision Tree, Random Forest, K-Means, Model Evaluation
\\[1.5pt]

BI \& Visualization
&
Power BI, Tableau, Microsoft Excel
\\[1.5pt]

Tools
&
Git, GitHub, Jupyter Notebook, Visual Studio Code

\end{tabularx}

%================================================
% CERTIFICATIONS
%================================================

\section*{Certifications}

\begin{tabularx}{\linewidth}{@{}X r@{}}

\textbf{Data Analytics Training / Internship Certificate -- CTTC, Bhubaneswar}
& \textbf{13 June 2026}
\\

\textbf{30 Days Power BI Micro Course -- SkillCourse}
& \textbf{07 August 2026}
\\

\textbf{Microsoft Excel Beginners To Advance -- SkillCourse}
& \textbf{20 August 2026}
\\

\textbf{30 Days SQL Micro Course -- SkillCourse}
& \textbf{21 August 2026}
\\

\textbf{The AI MasterClass -- Dhruv Rathee Academy}
& \textbf{26 July 2026}

\end{tabularx}

%================================================
% COURSES + STRENGTHS
%================================================

\section*{Courses}

\begin{tabularx}{\linewidth}{@{}X X@{}}

\textbf{The Ultimate Job Ready Data Science Course -- CodeWithHarry}
&
\textbf{Data Analytics Course}
\\[2pt]

\textbf{30 Days Python Micro Course -- SkillCourse}
&
\textbf{30 Days SQL Micro Course -- SkillCourse}
\\

\end{tabularx}

\vspace{2pt}

\section*{Strengths / Soft Skills}

\begin{center}

\colorbox{softblue}{
\parbox{0.92\linewidth}{
\centering
\textbf{\color{dark}
Analytical Thinking
\quad | \quad
Problem Solving
\quad | \quad
Communication
\quad | \quad
Teamwork
\quad | \quad
Adaptability
}
}

\end{center}

\end{document}
