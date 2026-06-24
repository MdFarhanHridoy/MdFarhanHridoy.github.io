\documentclass[]{resume-openfont}

\pagestyle{fancy}
\resetHeaderAndFooter

%--------------------------------------------------------------
% Convenience commands
%--------------------------------------------------------------

\newcommand{\resumeHeading}[4]{\runsubsection{\uppercase{#1}}\descript{ | #2}\hfill\location{#3 | #4}\fakeNewLine}

\newcommand{\educationHeading}[4]{\runsubsection{#1}\hspace*{\fill}  \location{#3 | #4}\\
\descript{#2}\fakeNewLine}

\newcommand{\projectHeading}[3]{\Project{#1}{#2}
\descript{#3}\\}

%--------------------------------------------------------------
\begin{document}

%--------------------------------------------------------------
% Profile
%--------------------------------------------------------------

\newcommand{\yourName}{Md. Farhan Rakib Hridoy}
\newcommand{\yourEmail}{farhan.rakib.hridoy@gmail.com}
\newcommand{\yourPhone}{+8801540799921}
\newcommand{\githubUserName}{MdFarhanHridoy}
\newcommand{\linkedInUserName}{farhan-rakib-hridoy}

\begin{center}
    \Huge \scshape \latoRegular{\yourName} \\ \vspace{2pt}
    \small 
    \href{mailto:\yourEmail}{\underline{\yourEmail}}  $|$
    \yourPhone $|$
    \href{https://www.linkedin.com/in/\linkedInUserName}{\underline{linkedin/\linkedInUserName}} $|$
    \href{https://github.com/\githubUserName}{\underline{github/\githubUserName}}
\end{center}

%--------------------------------------------------------------
% Professional Summary
%--------------------------------------------------------------

\section{Professional Summary}

\textbf{Full-stack Software Engineer} with experience building scalable web and mobile applications using modern technologies including \textbf{Next.js, React, Flutter, Laravel, and .NET}. Skilled in designing secure APIs, implementing responsive UI/UX, optimizing performance, and deploying production systems on cloud and VPS environments. Experienced in translating business requirements into reliable software solutions, collaborating with cross-functional teams, and delivering high-quality applications across web and mobile platforms.

\sectionsep

%--------------------------------------------------------------
% Education
%--------------------------------------------------------------

\section{Education}

\educationHeading
{BRAC University}
{B.Sc. in Computer Science and Engineering}
{Dhaka, Bangladesh}
{2024}

\textbf{Thesis:} Predicting Kidney Disease using Machine Learning and Neural Networks

\sectionsep

%--------------------------------------------------------------
% Experience
%--------------------------------------------------------------

\section{Work Experience}

\resumeHeading
{\href{https://www.linkedin.com/company/at-nation/}{Atnation}}
{Full-stack Software Engineer}
{Dhaka, Bangladesh}
{July 2025 -- Present}

\begin{bullets}

\item Designed and deployed scalable web applications using \textbf{JavaScript, TypeScript, React, and Next.js} with responsive UI and optimized performance.

\item Developed and maintained \textbf{cross-platform mobile applications using Flutter}, managing the full lifecycle from development to App Store and Google Play deployment.

\item Customized and optimized \textbf{WordPress themes and plugins}, improving performance, security, and maintainability.

\item Transformed \textbf{Figma design systems} into pixel-perfect responsive interfaces across web and mobile platforms.

\item Managed production deployments including \textbf{domain configuration, VPS setup, server management, and CI/CD pipelines}.

\item Implemented \textbf{Cloudflare caching, CDN, SSL configuration, and security protection} to enhance application performance and reliability.

\item Conducted \textbf{technical SEO audits, keyword research, and analytics} using SEMrush to improve search visibility and organic traffic.

\item Collaborated with \textbf{clients, designers, and product stakeholders} to gather requirements and deliver scalable software solutions.

\item Provided mentorship to junior developers through \textbf{code reviews, technical guidance, and best practice training}.

\end{bullets}

\sectionsep

\resumeHeading
{\href{https://www.khaninnovation.com/}{Khan Innovation}}
{Junior Software Developer}
{Dhaka, Bangladesh}
{June 2024 -- June 2025}

\begin{bullets}

\item Contributed to development of a \textbf{Billing and ERP Management System} using \textbf{C\#, .NET, and WPF} following the \textbf{MVVM architecture}.

\item Designed interactive \textbf{ERP dashboards and reporting interfaces} to improve usability and business insights.

\item Implemented \textbf{secure authentication and role-based access control} to protect enterprise data.

\item Designed and maintained relational \textbf{database schemas} supporting product management, customer records, invoices, and transaction history.

\item Collaborated with cross-functional teams to analyze requirements and deliver maintainable enterprise software solutions.

\end{bullets}

\sectionsep

%--------------------------------------------------------------
% Projects
%--------------------------------------------------------------

\section{Projects}

\projectHeading
{Acedevelopers Real Estate Platform}
{https://acedevelopers.com.bd/}
{Next.js, Contentful, Tailwind CSS, SEO}

Built a production real estate platform using \textbf{Next.js SSR} and \textbf{Contentful headless CMS}. Implemented SEO optimization, responsive UI components, and automated deployment pipelines while achieving \textbf{90+ Lighthouse performance scores}.

\sectionsep

\projectHeading
{Masalacha Social Matchmaking App}
{https://masalacha.com/}
{Flutter, Laravel, MySQL, Firebase, REST API}

Developed a full-stack matchmaking platform with a \textbf{Flutter mobile application} and \textbf{Laravel REST API backend}. Implemented JWT authentication, Firebase real-time chat, profile matching algorithms, and payment integration while reducing application load times by \textbf{40\%} through optimized state management and caching.

\sectionsep

\projectHeading
{Traliventa Sports Event Platform}
{https://traliventa.com/}
{Next.js, TypeScript, GSAP, Tailwind CSS}

Engineered a high-performance event platform using \textbf{Next.js and TypeScript}. Integrated dynamic event updates and animation frameworks while improving \textbf{Core Web Vitals} and increasing organic traffic through technical SEO and structured data implementation.

\sectionsep

\projectHeading
{ATnation Interactive Portfolio}
{https://github.com/MdFarhanHridoy/ATnation-website}
{Next.js, Three.js, Spline, GSAP}

Designed an immersive portfolio platform using \textbf{Three.js, WebGL, and Spline} for interactive 3D experiences. Optimized rendering performance to maintain \textbf{60 FPS animations} while ensuring responsive layouts.

\sectionsep

\projectHeading
{Karmogroup E-commerce Platform}
{https://karmogroup.com/}
{Next.js, TypeScript, NextAuth, SQLite}

Developing a dual \textbf{B2B/B2C e-commerce system} with role-based authentication, modular architecture, and scalable UI components. Leveraging \textbf{NextAuth.js and incremental static regeneration} to improve performance and maintain secure authentication workflows.

\sectionsep

\projectHeading
{Inventory Management System}
{https://github.com/MdFarhanHridoy/Stock-Management-System}
{ASP.NET MVC, C\#, Entity Framework, SQL Server}

Built a full-featured inventory management system with stock tracking, transaction processing, role-based access control, and automated low-stock alerts to support warehouse operations.

\sectionsep

%--------------------------------------------------------------
% Skills
%--------------------------------------------------------------

\section{Technical Skills}

\textbf{Programming Languages}

TypeScript \textbullet{} JavaScript \textbullet{} Dart \textbullet{} Python \textbullet{} Java \textbullet{} PHP \textbullet{} C\# \textbullet{} C++ \textbullet{} Kotlin

\sectionsep

\textbf{Frameworks and Libraries}

React.js \textbullet{} Next.js \textbullet{} Node.js \textbullet{} Laravel \textbullet{} Django \textbullet{} ASP.NET \textbullet{} Flutter \textbullet{} TensorFlow \textbullet{} Keras \textbullet{} Pandas \textbullet{} NumPy

\sectionsep

\textbf{Tools and Platforms}

Git \textbullet{} Docker \textbullet{} Firebase \textbullet{} Cloudflare \textbullet{} REST APIs \textbullet{} VPS Management \textbullet{} Linux Server Administration \textbullet{} cPanel \textbullet{} hPanel \textbullet{} aaPanel \textbullet{} MySQL

\end{document}