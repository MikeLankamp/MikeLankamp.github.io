# Curriculum Vitae

Below is my Curriculum Vitae containing my personal information, educational history, work experience and my skills and qualifications.

## Personalia

{% assign birthTimestamp = "1983-09-30" | date: "%s" %}
{% assign nowTimestamp = "now" | date: "%s" %}
{% assign age = nowTimestamp | minus: birthTimestamp | divided_by: 3600 | divided_by: 24 | divided_by: 365 | round: 0 %}

<img src="https://www.gstatic.com/images/branding/product/2x/contacts_2022_96dp.png" style="vertical-align: middle; width: 16px"> {{ age }} years old<br />
<img src="https://maps.gstatic.com/favicon.ico" style="vertical-align: middle; width: 16px"/> Utrecht, Netherlands<br />
<img src="https://ssl.gstatic.com/ui/v1/icons/mail/images/favicon_gmail_2026_v2.ico" style="vertical-align: middle; width: 16px"> [mike.lankamp@gmail.com](mailto:mike.lankamp@gmail.com).

## Socials

<img src="https://www.linkedin.com/favicon.ico" style="vertical-align: middle; width: 16px"> [LinkedIn](https://linkedin.com/in/mikelankamp)<br />
<img src="assets/images/gamedev.ico" style="vertical-align: middle; width: 16px"> [GameDev.net](https://www.gamedev.net/user/141103-mikenl/)<br />
<img src="https://github.com/favicon.ico" style="vertical-align: middle; width: 16px"> [GitHub](https://github.com/MikeLankamp)

## Work Experience

### <img src="assets/images/tomtom.png" style="height: 1em; vertical-align: middle"/> TomTom <span style="float: right">2014–present</span>
**Staff Software Engineer** <span style="float: right">2022–present</span><br />
**Senior Software Architect** <span style="float: right">2022–2022</span><br />
**Software Architect** <span style="float: right">2020–2022</span>

Promoted to Software Architect and later to Senior Architect (which was renamed to Staff Software Engineer later that year) within the same team. In 2023, moved to the team responsible for the common map data access layer used by TomTom’s core navigation library.
- Drove solution designs that impacted multiple teams, aligning with internal and external stakeholders.
- Participated in inter-company meetings and working groups for the shared NDS standard and its tooling.
- Participated in a company-wide working group for evaluation of new NDS technology.
- Spearheaded several team initiatives for code quality improvements and technical debt removal.
- Ensured work items were well documented, scoped and coupled to business goals.
- Participated in team code reviews, focusing on architectural issues and quality of code.
- Guided and advised software engineers in the team on technical issues.

**Expert Software Engineer / Tech Lead** <span style="float: right">2017–2020</span><br />
**Senior Software Engineer / Tech Lead** <span style="float: right">2016–2017</span><br />
**Senior Software Engineer** <span style="float: right">2014–2016</span>

Part of the team responsible for system-level issues and NDS Map Management in TomTom’s core navigation library ("NavKit", later "Navigation SDK"). Took on the role of Tech Lead of said team after a little over a year, and got promoted to Expert Software Engineer a year after that.
- Participated in team code reviews, focusing on architectural issues and quality of code.
- Guided and advised software engineers in the team on technical issues.
- Responsible for component architecture and documentation of features.
- Ensured work items were well documented, scoped and coupled to business goals (Tech Lead).
- Aligned on technical matters with internal and external stakeholders (Tech Lead).
- Spearheaded several initiatives for code quality improvements and technical debt removal (Tech Lead).

### <img src="assets/images/infor.png" style="height: 1em; vertical-align: middle"/> Infor <span style="float: right">2011–2014</span>
**Senior Software Engineer** <span style="float: right">2014–2014</span><br />
**Software Engineer** <span style="float: right">2011–2014</span>

Part of the team responsible for developing and maintaining Infor’s next-generation ERP web frontend (HTML/CSS/GWT), replacing a Java applet-based frontend.
- Prototyped, developed and maintained the next-generation frontend.
- Triaged and handled customer-reported issues.
- Helped design, develop and maintain an intra-company library of widgets and components.
- Coached junior software engineers.

### <img src="assets/images/uva.png" style="height: 1em; vertical-align: middle"/> University of Amsterdam <span style="float: right">2005–2011</span>
**Ph.D. Candidate Computer Science** <span style="float: right">2007–2011</span>

Started as a Ph.D. candidate after completing my M.Sc. with the same research group to continue research into multithreaded chip multiprocessors with hardware multithreading support.
- Researched, designed, implemented and evaluated a novel multithreaded many-core architecture.
- Wrote and maintained system simulation software in C++ to support evaluation of said architecture.
- Steered the group’s research direction based on findings from own research.

**Web developer** <span style="float: right">2005–2007</span>

Worked part-time at the Computer Science department I was studying at, developing a custom CMS and conference paper submission system (LAMP stack).
- Built and maintained a CMS and conference website system for the department.\

### Web developer — Multidisk <span style="float: right">2000–2007</span>
Worked part-time at a small record label company maintaining their website and webshop (ASP/VB/MS Access).
- Built and maintained small company’s website with online shop.

## Education

**Ph.D. Computer Science** — University of Amsterdam <span style="float: right">2007–2015</span><br />
Thesis: _"Design and Evaluation of a Multithreaded Many-core Architecture"_

**M.Sc. Grid Computing** — University of Amsterdam <span style="float: right">2004–2007</span><br />
Thesis: _"Developing a reference implementation for a microgrid of microthreaded microprocessors."_

**B.Sc. Computer Science** — University of Amsterdam <span style="float: right">2001–2004</span><br />
Thesis: _"Developing an online database for the UvA light scattering experiment."_

## Skills and Qualifications
- Fluent in Dutch and English.
- Experienced with programming languages: C, modern C++, C#, Javascript, Java, Kotlin, PHP, assembly (x86, Alpha, Sparc), Lua, Python and Visual Basic.
- Experienced with development tools: operating systems (Linux, Windows, OS X), compilers (gcc, clang), package managers (Conan), build systems (CMake, Ninja), VCS (Git, Perforce), CI (GitHub Actions), IDEs (Visual Studio, VS Code), Atlassian tools (JIRA/Confluence).
- Experienced with technologies: databases (SQL, MySQL, SQLite), "plain" web development (HTML, CSS, Javascript), computer graphics (DirectX/HLSL, OpenGL/GLSL, Vulkan), 3D CG Software (3D Studio Max, Blender), reverse engineering, decompilation, CI (GitHub Actions), Agile development.

## Publications

1. _Apple-CORE: Microgrids of SVP cores (invited paper)_ (Raphael Poss, Mike Lankamp, Qiang Yang, Jian Fu, Michiel W. van Tol, Chris Jesshope), In Proc. 15th Euromicro Conference on Digital System Design (DSD 2012) (Smail Niar, ed.), IEEE Computer Society, 2012.
2.	_Heterogeneous integration to simplify many-core architecture simulations_ (Raphael Poss, Mike Lankamp, M. Irfan Uddin, Jaroslav Sýkora, Leoš Kafka), In Proceedings of the 2012 Workshop on Rapid Simulation and Performance Evaluation: Methods and Tools, 2012.
3.	_The implementation of an SVP many-core processor and the evaluation of its memory architecture_ (Chris Jesshope, Mike Lankamp, Li Zhang), In SIGARCH Comput. Archit. News, ACM, volume 37, 2009.
4.	_Evaluating CMPs and Their Memory Architecture_ (Chris Jesshope, Mike Lankamp, Li Zhang), In ARCS '09: Proceedings of the 22nd International Conference on Architecture of Computing Systems, Springer-Verlag, 2009.
5.	_An implementation of the SANE Virtual Processor using POSIX threads_ (M. W. van Tol, C. R. Jesshope, M. Lankamp, S. Polstra), In J. Syst. Archit., Elsevier North-Holland, Inc., volume 55, 2009.
6.	_Implementation and evaluation of a microthread architecture_ (K. Bousias, L. Guang, C. R. Jesshope, M. Lankamp), In J. Syst. Archit., Elsevier North-Holland, Inc., volume 55, 2009.
7.	_Making multi-cores mainstream - from security to scalability_ (Chris Jesshope, Michael Hicks, Mike Lankamp, Raphael Poss, Li Zhang), In International Conference on Parallel Computing (ParCo), Springer (LNCS), 2009.
8.	_Compiling the Functional Data-Parallel Language SAC for Microgrids of Self-Adaptive Virtual Processors_ (Clemens Grelck, Stephan Herhut, Chris Jesshope, Carl Joslin, Mike Lankamp, Sven-Bodo Scholz, Alex Shafarenko), In 14th Workshop on Compilers for Parallel Computing (CPC'09), IBM Research Center, Zurich, Switzerland, 2009.
9.	_A general model of concurrency and its implementation as many-core dynamic RISC processors_ (T. Bernard, K. Bousias, L. Guang, C. R. Jesshope, M. Lankamp, M. W. van Tol, L. Zhang), In Proc. Intl. Conf. on Embedded Computer Systems: Architecture, Modeling and Simulation, SAMOS-2008 (W. Najjar, H. Blume, eds.), 2008.
10.	_Developing a Reference Implementation for a Microgrid of Microthreaded Microprocessors_ (M. Lankamp), Master's thesis, University of Amsterdam, 2007.
11.	_A Microthreaded Architecture and its Compiler_ (T. Bernard, K. Bousias, B. de Geus, M. Lankamp, L. Zhang, A.D. Pimentel, P.M.W. Knijnenburg, C.R. Jesshope), In Proc. 12th International Workshop on Compilers for Parallel Computers (CPC) (M. Arenez, R. Doallo, B.B. Fraguela, J. Tourino, eds.), 2006.