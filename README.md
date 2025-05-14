%%%%%%%%%%%%%%%%%
% This is an sample CV template created using altacv.cls
% (v1.7.2, 28 Aug 2024) written by LianTze Lim (liantze@gmail.com), based on the
% CV created by BusinessInsider at http://www.businessinsider.my/a-sample-resume-for-marissa-mayer-2016-7/?r=US&IR=T
%
%% It may be distributed and/or modified under the
%% conditions of the LaTeX Project Public License, either version 1.3
%% of this license or (at your option) any later version.
%% The latest version of this license is in
%%    http://www.latex-project.org/lppl.txt
%% and version 1.3 or later is part of all distributions of LaTeX
%% version 2003/12/01 or later.
%%%%%%%%%%%%%%%%

%% Use the "normalphoto" option if you want a normal photo instead of cropped to a circle
% \documentclass[10pt,a4paper,normalphoto]{altacv}

\documentclass[10pt,a4paper,ragged2e,withhyper]{altacv}
%% AltaCV uses the fontawesome5 and simpleicons packages.
%% See http://texdoc.net/pkg/fontawesome5 and http://texdoc.net/pkg/simpleicons for full list of symbols.

% Change the page layout if you need to
\geometry{left=1.25cm,right=1.25cm,top=1.5cm,bottom=1.5cm,columnsep=1.2cm}

% The paracol package lets you typeset columns of text in parallel
\usepackage{paracol}


% Change the font if you want to, depending on whether
% you're using pdflatex or xelatex/lualatex
% WHEN COMPILING WITH XELATEX PLEASE USE
% xelatex -shell-escape -output-driver="xdvipdfmx -z 0" mmayer.tex
\iftutex
  % If using xelatex or lualatex:
  \setmainfont{Lato}
\else
  % If using pdflatex:
  \usepackage[default]{lato}
\fi

% Change the colours if you want to
\definecolor{VividPurple}{HTML}{3E0097}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
% \colorlet{name}{black}
% \colorlet{tagline}{PastelRed}
\colorlet{heading}{VividPurple}
\colorlet{headingrule}{VividPurple}
% \colorlet{subheading}{PastelRed}
\colorlet{accent}{VividPurple}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

% Change some fonts, if necessary
% \renewcommand{\namefont}{\Huge\rmfamily\bfseries}
% \renewcommand{\personalinfofont}{\footnotesize}
% \renewcommand{\cvsectionfont}{\LARGE\rmfamily\bfseries}
% \renewcommand{\cvsubsectionfont}{\large\bfseries}

% Change the bullets for itemize and rating marker
% for \cvskill if you want to
\renewcommand{\cvItemMarker}{{\small\textbullet}}
\renewcommand{\cvRatingMarker}{\faCircle}
% ...and the markers for the date/location for \cvevent
% \renewcommand{\cvDateMarker}{\faCalendar*[regular]}
% \renewcommand{\cvLocationMarker}{\faMapMarker*}


% If your CV/résumé is in a language other than English,
% then you probably want to change these so that when you
% copy-paste from the PDF or run pdftotext, the location
% and date marker icons for \cvevent will paste as correct
% translations. For example Spanish:
% \renewcommand{\locationname}{Ubicación}
% \renewcommand{\datename}{Fecha}


%% Use (and optionally edit if necessary) this .tex if you
%% want to use an author-year reference style like APA(6)
%% for your publication list
% \input{pubs-authoryear.tex}

%% Use (and optionally edit if necessary) this .tex if you
%% want an originally numerical reference style like IEEE
%% for your publication list
\input{pubs-num.tex}

%% sample.bib contains your publications
\addbibresource{sample.bib}

\begin{document}
\name{Asaduzzaman}
\tagline{Software Developer \& Problem Solver}
% Cropped to square from https://en.wikipedia.org/wiki/Marissa_Mayer#/media/File:Marissa_Mayer_May_2014_(cropped).jpg, CC-BY 2.0
%% You can add multiple photos on the left or right
\photoR{2.5cm}{asad.jpg}
% \photoL{2cm}{Yacht_High,Suitcase_High}
\personalinfo{%
  % Not all of these are required!
  % You can add your own with \printinfo{symbol}{detail}
 
  \phone{+8801771191720}
  \mailaddress{asadcse1st@gmail.com}
  \location{Mymensingh,Bangladesh}

  % \twitter{@marissamayer}

  \linkedin{linkedin.com/in/ak5s} \github{https://github.com/GitAsaduzzaman/}
  \homepage{https://asadcseshu.blogspot.com/}% I'm just making this up though.
%   \orcid{0000-0000-0000-0000} % Obviously making this up too.
  %% You can add your own arbitrary detail with
  %% \printinfo{symbol}{detail}[optional hyperlink prefix]
  % \printinfo{\faPaw}{Hey ho!}
  %% Or you can declare your own field with
  %% \NewInfoFiled{fieldname}{symbol}[optional hyperlink prefix] and use it:
  % \NewInfoField{gitlab}{\faGitlab}[https://gitlab.com/]
  % \gitlab{your_id}
	%%
  %% For services and platforms like Mastodon where there isn't a
  %% straightforward relation between the user ID/nickname and the hyperlink,
  %% you can use \printinfo directly e.g.
  % \printinfo{\faMastodon}{@username@instace}[https://instance.url/@username]
  %% But if you absolutely want to create new dedicated info fields for
  %% such platforms, then use \NewInfoField* with a star:
  % \NewInfoField*{mastodon}{\faMastodon}
  %% then you can use \mastodon, with TWO arguments where the 2nd argument is
  %% the full hyperlink.
  % \mastodon{@username@instance}{https://instance.url/@username}
}

\makecvheader

%% Depending on your tastes, you may want to make fonts of itemize environments slightly smaller
\AtBeginEnvironment{itemize}{\small}

%% Set the left/right column width ratio to 6:4.
\columnratio{0.6}

% Start a 2-column paracol. Both the left and right columns will automatically
% break across pages if things get too long.
\begin{paracol}{2}

\cvsection{Experience}

\cvevent{Full-Stack Web Development Intern}{BA Systems Ltd.}{Jan 2025 -- Apr 2025}{Online (45 hours)}
\begin{itemize}
    \item  Completed a 3-month internship with practical training in full-stack development.
    \item \textbf{Front-end:} HTML5, CSS, Bootstrap, JavaScript, AJAX, Select2, DataTables
    \item \textbf{Back-end:} PHP (OOP), Laravel (MVC, Auth, Plugins)
    \item \textbf{Database:} MySQL – CRUD operations, query optimization
    \item \textbf{APIs \& Tools:} RESTful API, Postman, Git, LAMP stack
    \item \textbf{Professional Practices:} SDLC, Requirement Analysis, Manual/Automation Testing, OWASP, VAPT, and AI-based development
    \item \textbf{Capstone Project:} Industry-ready software with AI integration and secure coding standards
    \item \textbf{Schedule:} Saturdays \& Wednesdays, 11:00 AM – 1:00 PM
    \item \textbf{Supervisor:} Md. Majbah Uddin, Team Lead (WebCrafter)
\end{itemize}


\divider


\cvsection{Projects}

\cvsubsection{Software Projects}
\cvachievement{\faLaptopCode}{Online Study Portal}{All-in-one study platform with 14 key features for students (Django)}
\cvachievement{\faUsersCog}{Human Resource Management}{University HRM system built with PHP}
\cvachievement{\faMobile}{E-Sromo Bazar}{Local worker-finding mobile app (Flutter)}
\cvachievement{\faMicrochip}{Quantum}{Text-to-speech desktop app developed in C\#}
\cvachievement{\faComments}{Chat-boot}{Q/A chatbot built using Assembly Language}

\divider

\cvsubsection{Hardware Projects}
\cvachievement{\faTools}{Arduino-based Passenger Counter}{Counts passengers and calculates rent using sensors}
\cvachievement{\faWifi}{Smart Attendance System}{IoT-based system built with NodeMCU for automated attendance}


% \divider

% \cvevent{Product Engineer}{Google}{23 June 1999 -- 2001}{Palo Alto, CA}

% \begin{itemize}
% \item Joined the company as employe \#20 and female employee \#1
% \item Developed targeted advertisement in order to use user's search queries and show them related ads
% \end{itemize}


% use ONLY \newpage if you want to force a page break for
% ONLY the currentc column
\cvsection{Publications}

\cvachievement{\faBook}{AI Based Traffic Control System}{Paper Review — Asaduzzaman, December 2024}

\divider

\cvachievement{\faNewspaper}{Smart Health Care Booth (SHCB)}{Press Release — Asaduzzaman, September 2022}

\switchcolumn
\cvsection{Life Philosophy}
\begin{quote}
``If you don't have any shadows, you're not standing in the light.''
\end{quote}

\cvsection{Most PROUD OF}

\cvachievement{\faTrophy}{Hult Prize OnCampus Champion}{Selected as the best International Business Idea provider at university level}

\divider

\cvachievement{\faGlobe}{Hult Prize Regional Finalist}{Competed at international level with innovative business ideas}

\divider

\cvachievement{\faUsers}{University Press Association}{Active member of the ad hoc committee involved in organizing and publishing activities}

\divider

\cvachievement{\faHandsHelping}{Nirvoy Foundation}{Volunteered for community-focused initiatives and social outreach}


% Don't overuse these \cvtag boxes — they're just eye-candies and not essential. If something doesn't fit on a single line, it probably works better as part of an itemized list (probably inlined itemized list), or just as a comma-separated list of strengths.

% The `ragged2e` document class option might cause automatic linebreaks between \cvtag to fail.
% Either remove the ragged2e option; or 
% add \LaTeXraggedright in the paragraph for these \cvtag
\cvsection{SKILLS}
{\LaTeXraggedright
\cvtag{Hard-working}
\cvtag{Eye for detail}
\cvtag{Motivator \& Leader}
\cvtag{Mobile, Web \& Desktop Applications}
\cvtag{MySQL} \cvtag{SQLite}
\cvtag{Problem Solving}
\cvtag{UI/UX}
\cvtag{Laravel}
\cvtag{Django}
\cvtag{Flutter}
\cvtag{Web Hosting}

\cvtag{Assembly}
\cvtag{C/C++}
\cvtag{Python}
\cvtag{PHP}

\cvsection{Education}

% \cvref{name}{email}{mailing address}
\cvevent{B.Sc.\ in Computer Science and Engineering}{Netrokona University}{January 2020 -- January 2024} {} {}
\cvsection{Referees}

\cvref{Assistant Prof.Abdullah Al Shiam\ }{Netrokona University}{shiam.cse@shu.edu.bd}
2400-Netrokona,Banglasesh.

\end{paracol}

\end{document}