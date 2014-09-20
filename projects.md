---
title: Current research projects
layout: page
---

## Transfer Learning in Software Engineering

_2013 -- 2017_

NSF, SHF: Medium: Collaborative, #1302216

<img align=right src="{{site.baseurl}}/img/nsf1v.jpg">

The goal of the research is to enable software
engineers to find software development best
practices from past empirical data. The increasing
availability of software development project data,
plus new machine learning techniques, make it
possible for researchers to study the
generalizability of results across projects using
the concept of transfer learning. Using data from
real software projects, the project will determine
and validate best practices in three areas:
predicting software development effort; isolating
software detects; effective code inspection
practices.

This research will deliver new data mining
technologies in the form of transfer learning
techniques and tools that overcome current
limitations in the state-of-the-art to provide
accurate learning within and across projects. It
will design new empirical studies, which apply
transfer learning to empirical data collected from
industrial software projects. It will build an
on-line model analysis service, making the
techniques and tools available to other researchers
who are investigating validity of principles for
best practice.

The broader impacts of the research will be to make
empirical software engineering research results more
transferable to practice, and to improve the
research processes for the empirical software
engineering community. By providing a means to test
principles about software development, this work
stands to transform empirical software engineering
research and enable software managers to rely on
scientifically obtained facts and conclusions rather
than anecdotal evidence and one-off studies. Given
the immense importance and cost of software in
commercial and critical systems, the research has
long-term economic impacts.

##  GALE: Geometric Active Learning for Search-Based Software Engineering

with _Joseph Krall,_, WVU

<img align=right width=300 src="{{site.baseurl}}/img/gale.png">
Multi-objective evolutionary algorithms
(MOEAs) help software engineers find novel solutions
to complex problems. When MOEAs explore too many
options, they are slow to use and hard to
comprehend. GALE is a near-linear time MOEA that
builds a piecewise approximation to the surface of
best solutions along the Pareto frontier. For each
piece, GALE mutates solutions towards the better
end. In numerous case studies, GALE finds comparable
solutions to standard methods (NSGA-II, SPEA2) using
far fewer evaluations (e.g. 20 evaluations, not
1000). GALE is recommended when a model is expensive
to evaluate, or when some audience needs to browse
and understand how an MOEA has made its conclusions.

## Evolutionary Search with Strong Heuristics for Software Product Line Configuration

with _Abdel Salam Sayyad,_ WVU

<img align=right width=300 src="{{site.baseurl}}/img/spl.png">
Software design is a process of trading off
competing objectives. In this study, we configure
software product lines (expressed as feature
models). As we increase the number of objectives,
standard optimizers in widespread use (e.g. NSGA-II,
SPEA2) perform much worse than IBEA (Indicator-Based
Evolutionary Algorithm) since IBEA makes most use of
user preferences. Also, IBEA generates far more
products with no violations of domain
constraints. This research presents two methods for
scaling IBEA to very large feature models with many
objectives.  Our “PUSH” technique forces the
evolutionary search to respect certain rules and
dependencies defined by the feature models. Also,
our “PULL” technique gives higher weight to
constraint satisfaction as an optimization objective
and thus achieves a higher percentage of
fully-compliant configurations within short
runtimes. Using IBEA+PUSH+PULL, we can extract valid
products in a matter of minutes, even from very
large feature models of Linux kernels. Our
conclusion is that the methods we apply in
search-based software engineering need to be
carefully chosen, particularly when studying complex
decision spaces with many optimization objectives.
As shown here, better and faster optimizers can be
built when designers take full advantage of
naturally occurring domain constraints.


## Cross Trees: Visualizing Estimations using Decision Trees

with _Naveen Kumar Lekkalapudi,_ WVU

<img align=right width=300 src="{{site.baseurl}}/img/crosstrees.png">
Optimization has been the goal of almost every human
thought and action. With growing computational
capabilities, solutions to problems are also
exponentially increasing. Literature proves that
with rising demand for data and analytics on this
large data, solutions to problems are
multiplied. These solutions are supported with
strong statistical and analytical reasoning that
does help experts narrow down solutions. Optimizing
these large set of solutions can get tricky to
experts who seek knowledge of how these solutions
have improved and what decisions need to be taken
for remaining solutions to improve. This problem
persists in software engineering with managers and
experts taking decisions which decide the course of
project.

This thesis proposes a method for optimizing
solutions along with providing decisions that help
improve a solution. Literature supports that
landscape visualization of data gives an inside
scoop of data behaviour. A method is proposed which
takes benefit of visualizing data and improving
solutions based on their position in
landscape. Cross Trees are built by grouping data
based on their similarities. Traversing from bad
group of solutions to better group of solutions
require few decisions to taken. These decisions are
proposed by CrossTree and are tested for how valid
they are. CrossTree is tested with two models which
simulate software projects-POM3 and XOMO.  Also,
models are simluated with one of the best genetic
algortihms NSGA-II, to generate set of optimized
solutions. CrossTree is compared against results
from NSGA-II to validate performance.

