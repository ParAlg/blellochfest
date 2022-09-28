---
layout: default
title: Blelloch Fest
---

# Blelloch Fest

We will be celebrating Guy Blelloch's 60th birthday (and his 30th
anniversary of joining CMU) on <b>Saturday October 15th, 2022 in
Pittsburgh at the Gates Hillman Center (GHC)</b>. The event will
include talks from Guy's colleagues, friends, and students. The talks
will revolve around Guy's interests in parallel languages,
cost-models, and algorithms.

### Schedule and Speaker List

* Morning Session
  * <b>8:30--9:00</b> --- Breakfast at GHC

  * <b>9:00--9:30</b> --- Highlights from 35 Papers with Guy (Phil Gibbons)
  * <b>9:30--10:00</b> --- Parallelizing Sequential Iterative Algorithms using Parallel Data Structures (Yihan Sun)
  * <b>10:00--10:30</b> --- Data-Oblivious Algorithms for Multicores (Elaine Shi)

  * <b>10:30--11:00</b> --- Coffee Break

  * <b>11:00--11:30</b> ---  TBD (Naama Ben-David)
  * <b>11:30--12:00</b> ---  TBD (Short talks?)

* Lunch
  * <b>12:00--2:00</b> --- Lunch at Cafe Carnegie (Carnegie Museum of Natural History)

* Afternoon Session
  * <b>2:00--2:30</b> --- Verification of Cost in Dependent Type Theory (Bob Harper)
  * <b>2:30--3:00</b> --- TBD (Lenore and Manuel Blum)
  * <b>3:00--3:30</b> --- TBD (Julian Shun)
  
  * <b>3:30--4:00</b> --- Coffee Break

  * <b>4:00--4:30</b> --- TBD (Laxman?)
  * <b>4:30--5:00</b> --- TBD (Yan Gu)
  * <b>5:30--5:30</b> --- The Yug of Guy, and A Trifle (Siddhartha Chatterjee)
  * <b>5:30--6:00</b> -- Closing Remarks

* <b>7:00</b> -- Dinner at TBA

### Titles and Abstracts


<b>Title:Highlights from 35 Papers with Guy</b> <em>([Phil Gibbons][phil])</em>

<b> Abstract:</b>
Guy and I have co-authored 35 conference and journal publications, spanning 27 years. This talk will highlight this body of joint work: the good, the bad, and the ugly. 


<b>Title:Parallelizing Sequential Iterative Algorithms using Parallel Data Structures</b> <em>([Yihan Sun][yihans])</em>

<b> Abstract:</b>
Designing parallel algorithms in general is hard, and therefore many simple problems in the sequential setting become more complicated in parallel. 
Some recent research (including many of Guy's papers!) reveals an interesting observation: many sequential iterative algorithms are inherently "parallel" when the dependences among iterations are carefully analyzed. Such algorithms are usually practical and easy to understand, due to their simplicity and connections to sequential algorithms. 

This talk will review some recent advances in parallelizing sequential iterative algorithms. In particular, for some problems, we will show how parallel data structures can be used to greatly simplify the algorithm, and enable efficient work and low span. 



<b>Title:Data-Oblivious Algorithms for Multicores</b> <em>([Elaine Shi][elaine])</em>

<b> Abstract:</b>
I will talk about privacy-preserving algorithms in the binary fork-join model, which is the de facto model of computation for modern multi-core processors proposed by Guy Blelloch and others. I will also discuss applications of these techniques to privacy-preserving algorithms in other models such as Massively Parallel Computation. The full abstract is below, this is joint work with Vijaya Ramachandran.

As secure processors such as Intel SGX (with hyperthreading) become widely adopted, there is a growing appetite for private analytics on big data. Most prior works on data-oblivious algorithms adopt the classical PRAM model to capture parallelism. However, it is widely understood that PRAM does not best capture realistic multicore processors, nor does it reflect parallel programming models adopted in practice. 
In this paper, we initiate the study of parallel data oblivious algorithms on realistic multicores, best captured by the binary fork-join model of computation. We first show that data-oblivious sorting can be accomplished by a binary fork-join algorithm with optimal total work and optimal (cache-oblivious) cache complexity, and in O(log n log log n) span (i.e., parallel time) that matches the best-known insecure algorithm. Using our sorting algorithm as a core primitive, we show how to data-obliviously simulate general PRAM algorithms in the binary fork-join model with non-trivial efficiency. We also present results for several applications including list ranking, Euler tour, tree contraction, connected components, and minimum spanning forest. For a subset of these applications, our data-oblivious algorithms asymptotically outperform the best known insecure algorithms. For other applications, we show data oblivious algorithms whose performance bounds match the best known insecure algorithms. 
Complementing these asymptotically efficient results, we present a practical variant of our sorting algorithm that is self-contained and potentially implementable. It has optimal caching cost, and it is only a log log n factor off from optimal work and about a log n factor off in terms of span; moreover, it achieves small constant factors in its bounds.


### Organizing Committee
* Umut Acar
* Naama Ben-David
* Laxman Dhulipala
* Yan Gu
* Julian Shun
* Virginia Williams

<b>Virtual Participation:</b> We will stream and record the event on zoom (meeting info TBA).



[acmharass]: https://www.acm.org/special-interest-groups/volunteer-resources/officers-manual/policy-against-discrimination-and-harassment
[spaa]: https://spaa.acm.org/
[laxman]: https://ldhulipala.github.io/
[yan]: https://www.cs.ucr.edu/~ygu/
[yihans]: https://www.cs.ucr.edu/~yihans/ 
[phil]: http://www.cs.cmu.edu/~gibbons/
[kuba]: https://research.google/people/105517/
[lars]: https://scholar.google.de/citations?user=G5XO7J4AAAAJ&hl=en
[brian]: https://brianwheatman.com/
[julian]: https://people.csail.mit.edu/jshun/
[zoomlink]: https://docs.google.com/document/d/1om-PvjaC49-zOxKRjcUxOGXcDayXjpq6VtrXr8CEoEg
[form]: https://forms.gle/myvcibc9Bs7wrJPd7
