---
layout: page
title: Projects
permalink: "projects.html"
---

I'm very interested in modern approaches to mathematical texts. I've been using [preTeXt][1], an xml derived typesetting language, to build textbooks and course notes. Most of these projects are works in progress, but I'm happy to share.

## Open source texts

#### Hilbert Spaces: A sequel to linear algebra

This text is inspired by and partly based on the outstanding "Introduction to Hilbert Spaces" by N. J. Young, which is sadly out of print. This book fills a niche that is somewhat unique: a course on Hilbert space theory that is rigorous but follows from a strong undergraduate curriculum, rather than a more typical second year graduate course in functional analysis. The long-term goal is for this text to serve as a follow-up to Sheldon Axler's _Linear Algebra Done Right_, which lays a lot of the linear algebraic groundwork for operator theory.

This is very much a work in progress. Current topics include: inner products, norms and metric spaces, closed linear subspaces, limits in Hilbert space, $$\ell^2$$, $$L^2$$, and a bit of Hilbert space geometry. Future topics will include Fourier series and an introduction to operators.

The text can be found [here][2], and the source, which is compiled from preTeXt, is [here][3].


#### Mathematical Cryptography

These are course notes from a class I taught to a group of computer science students that asked for a more rigorous introduction to the theory of cryptography. The notes loosely follow the structure of ["An Introduction to Mathematical Cryptography"][4], by Hoffstein, Pipher, and Silverman. The book is an excellent text, but the mathematics were a bit proof heavy for the course I ran. I tried to split the difference between mathematical rigor and implementation. I taught this course in python, and the text has interactive code demonstrations that execute in the text using SageMath's CoCalc server.

The text can be found [here][5] and the source is [here][6].

#### Numerical Analysis

These are course notes I prepared for an upper division course in numerical analysis. The audience was largely engineers, so I focused on implementation of various ideas. The language I used in this course was Octave, as I didn't have a site license for Matlab, which was my preferred language. On the plus side, Octave can be rendered in executable blocks in preTeXt, so choosing Octave was a net positive. Topics include root-finding, polynomial approximation, interpolation, numerical integration, and an introduction to Fourier series.

The text can be found [here][7] and the source is [here][8].

### Operator Theory Community

#### OPT-IN

The Operator Theory Information Network is an in-development community hub for mathematicians and grad students interested in operator theory. It was inspired by the Operator Algebra Searchable Information Site ([OASIS][9]) and the [Internet Analysis Seminar][10]. I designed the website and the directory. The initiative is loosely led by me, Kelly Bickel, and J. E. Pascoe.

#### OTTER

Operator Theory Talks for Early Researchers ([OTTER][11]) is a related project aimed specifically at mathematical discourse and professional guidance for graduate students and postdocs. I'm involved in the project as a mentor and speaker.

[1]:<https://pretextbook.org/>
[2]:<https://rtullydo.github.io/hilbert/hilbert.html>
[3]:<https://github.com/rtullydo/hilbert>
[4]:<https://www.math.brown.edu/~jhs/MathCryptoHome.html>
[5]:<https://rtullydo.github.io/cryptography-notes/cryptography.html>
[6]:<https://github.com/rtullydo/cryptography-notes>
[7]:<https://rtullydo.github.io/numerical-analysis-unh/minimal.html>
[8]:<https://github.com/rtullydo/numerical-analysis-unh>
[9]:<https://operatoralgebras.org/index.html>
[10]:<http://internetanalysisseminar.gatech.edu/index.html>
[11]:<https://sites.google.com/view/otter-math/home>