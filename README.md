pubmed
======

You will need to download the PUBMED dataset distributed for the WebScience dataset visualisation:
[publications-1809-2013.tar.gz (1.4GB)](http://carl.cs.indiana.edu/data/websci2014/publications-1809-2013.tar.gz)


The proposed visualisation presents the results from 3 individual and parallel data analyses. These analyses are based on the information provided from the PUBMED dataset only[1, 2]. The first analysis and visualisation is based on the construction of the annual co-authorship graph (see “Collaboration in research” in the submitted visualisation). For each year, a graph is constructed where the nodes represent authors and edges represent co-authorships. The result of this analysis shows that the size of the graph (number of nodes and number of edges) increases exponentially over time. More interestingly, the density of the graph is increasing. This is depicted through various measurements, such as the relative increase in edges, the increase in entropy [3] and average clustering coefficient. These measurements allow us to draw the conclusion that each year research is conducted by more researchers, produces more publications and becomes more collaborative in nature.
The second analysis is focusing on profiling the activity of researchers. To this end, the profile of the authors is described by introducing and extracting the following author-attributes:
• Year of first publication,
• year of last publication,
• number of publications,
• duration of research activity, as the difference of the first two attributes.
In the two figures of the second analysis (entitled as “Academic throughput & retention”), the values of the above attributes are exploited. Researchers are classified under the same category if (and only if) they make their first publica- tion on the same year (i.e. a researcher who makes his first publication in 1979 belongs to the category of “researchers of 1979”). This time-based projection of the researchers’ activity shows that the average duration of an active research career decreases progressively. The projection starts from 1965 and ends in 2001. The decision to disregard researchers that started their research activity more recently was made on the assumption that younger researchers may not have ended their activity yet, despite a long “intermission” of zero publications. The two figures show that researchers are more publication-productive but tend to go inactive sooner than in previous years. These observations may be accounted for by the fact that a) research becomes more collaborative and publications con- tain more co-authors, and b) young researchers, such as Ph.D. students, do not follow an academic career as their predecessors (academic retention decreases1).
The third analysis (“Terminology - evolution”) is exploiting the title of the publications. Starting from 1950 and ending in 2009, a stepwise, 5-year time period is used to group together all publication titles and form a unified corpus (e.g. “the 1950-1955” titles corpus). For each corpus, a frequency distribution dictionary of terms is constructed. More specifically, this dictionary holds en- tries that contain single terms and their corresponding percentage of occurrence (similarly to Google Books n-gram2 limited for n=1). The figures of this visuali- sation show the evolution in the usage of different terms or disjunction of terms. Figures are grouped thematically, depending on the intention of the message. The terms in the themes were hand-picked and show the following observations:
• Diseases that have either been cured or are not considered threatening anymore tend to decline,
• new diseases and disease risk factors appear in contemporary research,
• terms that describe the methodology change over time. For instance the
term “microscope” is rarely used in titles nowadays but was popular in the 1950s; “computer” gained momentum in the 1970s until the 1990s and nowadays “algorithms” emerge (presumably because computers are considered the de facto standard today). Similar observations are made for the usage of term “clinical”, which appears to complement “patients” (i.e. modern medicine stresses a lot the importance of patient awareness and empowerment, contrary to the traditional “clinic-based” medicine, see for example [4]).


References
[1] G. LaRowe, S. Ambre, J. Burgoon, W. Ke, and K. B ̈orner. The scholarly database and its utility for scientometrics research. Scientometrics, 79(2), May 2009.
[2] R. P. Light, D. E. Polley, and K. B ̈orner. Open data and open code for big science of science studies. In Proceedings of International Society of Scientometrics and Informetrics Conference, pages 1342–1356, 2013.
[3] M. Rowe and M. Strohmaier. The semantic evolution of online communities (pre-print). In Proceedings of the 23rd international conference on World Wide Web. International World Wide Web Conferences Steering Committee, 2014.
[4] D. Williamson and T. Stewart. Behavior and lifestyle: approaches to treat- ment of obesity. The Journal of the Louisiana State Medical Society: official organ of the Louisiana State Medical Society, 157:S50–5, 2005.
