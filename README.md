# test1CS
\documentclass{article}

\usepackage{pgfplots}
\usepackage[margin=0.75in, paperwidth=8.5in, paperheight=11in]{geometry}
\usepackage{setspace}
\usepackage{fancyvrb} % extended verbatim environments
\usepackage{framed}%To get shade behind text

\definecolor{shadecolor}{rgb}{0.9,0.9,0.9}%setting shade color


\begin{document}
\pagenumbering{gobble}

\doublespacing
\textbf{IB Computer Science }                        %%%(class number and section) 
 \hfill                             %%%(date of test)
$ {\bf Name:Jin Huang } (3 points)

\begin{centering}
\vspace{1cm}
\textbf{Exam 1}\\
\end{centering}
\vspace{1cm}
 
$\bf{1)}$ Determine what each of the following Python expressions will return.  In other words, if these expressions were entered into the Python terminal, what would they return?
(5 points each)

\vspace{1cm}
  
 a.  
 \begin{verbatim}
 		5/2    Answer:2
 \end{verbatim}

 
 b.   \begin{verbatim}
 		5./2.  Answer:2.5
 \end{verbatim}
  \vspace{1cm}
 
 c.  
  \begin{verbatim}
 		5%3    Answer:2
 \end{verbatim}
 \vspace{1cm}
  
 d. 
  \begin{verbatim}
 		not(5>6) and (True or False)  Answer:Ture
 \end{verbatim}
 \vspace{1cm}
 
 e. 
  \begin{verbatim}
 		(5==4) or (not True)  Answer:False
 \end{verbatim}
 \vspace{1cm}

  \newpage
  
 $\bf{2)}$ Write the output of the following programs. (8 points each)
 
 \vspace{1cm}

  
 a.   \begin{verbatim}
 for i in range(3):
       print i*i
 print "hi" 
 Answer:0
        1
        4
        hi
 \end{verbatim}
 \vspace{1cm}
 
 b.  \begin{verbatim}
 s=0
 for x in [5,3,1]:
       s=s+x
 print s
 Answer:5
        8
        9
 \end{verbatim}
 \vspace{1cm}
 
 c.  \begin{verbatim}
 x=16
 while x  > 5:
       x=x/2
 print x
 Answer:X=4
 \end{verbatim}
 \vspace{1cm}
 
 d.   \begin{verbatim}
 a=7
 if a%2==1:
       print "yoda"
 else:
       print "do yoga"
Answer:yoda
 \end{verbatim}
 \vspace{1cm}
  \newpage

  
  $\bf{3)}$  The following questions are about Git. (10 points each)
  \vspace{0.5cm}
    
  a.  Explain how to create a new git repository.  Include all terminal commands and things you must do on github.  Assume your github user name is "Charlie" and your project is in a folder named "Project" in your Documents folder.  Name the repository "ProjRepo".
 
  Answer:#cd documents 
        
         #mkdir Project
        
         #cd Project
        
         put files in project
        
         #git init
        
         #git add .
        
         #git commit - m" my comment"
        
         #git remote add orgin https://github.com/Charlie/Project.git
        
         #git push origin master
    \vspace{8cm}

  b.  Explain how to clone a repository name "Awesome" from github user named "Barry22".  Clone the repository into your Documents folder.
  
  Answer:in the termina,type #cd path/to/where u want/folder
  and git clone https://github.com/Barry22/Awesome
    \vspace{4cm}
  
  \newpage
  
  $\bf{4)}$ Write a program that constructs an array filled with all of the prime numbers between 2 and 100. (20 points)

 Answer:a=[ ]
 
 for i in range(2,100):
     
     prime=true

 for x in range(2,i):
    
    if i%x==0
   
    prime=false
   
    if prime:
   
    a=a+[i]
 
  \vspace{0.5cm}
  
  
  
  
  

 
\end{document}
