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

<b>Information about Attending:</b>

The event will be taking place in <b>GHC 6115</b>. The doors to the building and upper-floor elevators will be open on this day.

Parking should be free on Saturday if you park at either:
 * [Morewood Gardens Lot](https://goo.gl/maps/93FuEaoig6UNufwQA) (The entry is between the Stever and Morewood dorms when coming from Fifth ave).
 * [East Campus Garage](https://goo.gl/maps/2UoBoBFRVLgiGEVb8) (Along Forbes ave, by the stadium)

You can also see these annotated maps of how to get from the [Morewood Gardens Lot to GHC](/blellochfest/docs/MorewoodToGHC.pdf) and from the [East Campus Garage to GHC](/blellochfest/docs/EastCampusToGHC.pdf).

Wi-Fi info can be found [here](/blellochfest/wifi).

<b>Virtual Participation:</b> We will stream and record the event on zoom here: [https://mit.zoom.us/j/97916094809](https://mit.zoom.us/j/97916094809).

### Schedule and Speaker List

* <b>Morning Session</b>
  * <b>8:30--9:00</b> --- Breakfast at GHC

  * <b>9:00--9:25</b> --- Highlights from 35 Papers with Guy (*Phil Gibbons*)
  * <b>9:25--9:50</b> --- Parallelizing Sequential Iterative Algorithms using Parallel Data Structures (*Yihan Sun*)
  * <b>9:50--10:15</b> --- Data-Oblivious Algorithms for Multicores (*Elaine Shi*)

  * <b>10:15--11:00</b> --- Coffee Break

  * <b>11:00--11:25</b> ---  Fast and Fair Lock-Free Locks (*Naama Ben-David*)
  * <b>11:25--11:50</b> ---  Parallel external-memory algorithms: theory to practice (and back to theory again?) (*Harsha Simhadri*)

* <b>Lunch</b>
  * <b>12:00--2:00</b> --- Lunch at Cafe Carnegie

* <b>Afternoon Session</b>
  * <b>2:00--2:25</b> --- Verification of Cost in Dependent Type Theory (*Bob Harper*)
  * <b>2:25--2:50</b> --- ALADDIN, Consciousness and Free Will from a TCS perspective  (*Lenore Blum and Manuel Blum*)
  * <b>2:50--3:15</b> --- Parallel Batch-Dynamic Graph Algorithms (*Julian Shun*)
  * <b>3:15--3:40</b> --- Parallel Hierarchical Agglomerative Graph Clustering (*Laxman Dhulipala*)

  * <b>3:40--4:15</b> --- Coffee Break

  * <b>4:15--4:40</b> --- TBD (*Umut Acar*)
  * <b>4:40--5:05</b> --- Computational Models for Modern Architecture (*Yan Gu*)
  * <b>5:05--5:35</b> --- The Yug of Guy, and A Trifle (*Siddhartha Chatterjee*)
  * <b>5:35--6:00</b> -- TBD (*Charles Leiserson*)
  * <b>6:00</b> -- Closing Remarks (*Guy Blelloch*)

* <b>7:00</b> -- Dinner at Lucca Ristorante

### Titles and Abstracts


<b>Highlights from 35 Papers with Guy</b> <em>([Phil Gibbons][phil])</em>

<b> Abstract:</b>
Guy and I have co-authored 35 conference and journal publications, spanning 27 years. This talk will highlight this body of joint work: the good, the bad, and the ugly.


<b>Parallelizing Sequential Iterative Algorithms using Parallel Data Structures</b> <em>([Yihan Sun][yihans])</em>

<b> Abstract:</b>
Designing parallel algorithms in general is hard, and therefore many simple problems in the sequential setting become more complicated in parallel.
Some recent research (including many of Guy's papers!) reveals an interesting observation: many sequential iterative algorithms are inherently "parallel" when the dependences among iterations are carefully analyzed. Such algorithms are usually practical and easy to understand, due to their simplicity and connections to sequential algorithms.

This talk will review some recent advances in parallelizing sequential iterative algorithms. In particular, for some problems, we will show how parallel data structures can be used to greatly simplify the algorithm, and enable efficient work and low span.



<b>Data-Oblivious Algorithms for Multicores</b> <em>([Elaine Shi][elaine])</em>

<b> Abstract:</b>
I will talk about privacy-preserving algorithms in the binary fork-join model, which is the de facto model of computation for modern multi-core processors proposed by Guy Blelloch and others. I will also discuss applications of these techniques to privacy-preserving algorithms in other models such as Massively Parallel Computation. (Joint work with Vijaya Ramachandran)


<b>Title: Fast and Fair Lock-Free Locks</b> <em>([Naama Ben-David][naama])</em>

<b>Abstract:</b>
Locks are frequently used in concurrent systems to simplify code and ensure safe access to contended parts of memory. However, they are also known to cause bottlenecks in concurrent code, leading practitioners and theoreticians to sometimes opt for more intricate lock-free implementations. In this talk, I’ll give an overview of joint work with Guy which shows that, despite the seeming contradiction, it is possible to design practically and theoretically efficient lock-free locks. I’ll discuss how we model and reason about concurrent systems theoretically, and present a lock-free lock algorithm with good bounds on running time and fairness.


<b>Verification of Cost in Dependent Type Theory</b> <em>([Bob Harper][bob])</em>

<b> Abstract:</b>
Dependent type theory is a natural setting for expressing and proving the behavior of programs, chiefly by equational reasoning.  In standard formulations of type theory any two sorting algorithms would be equal, simply because they sort.  But then what would it mean to specify that one sort is more efficient than another?  Recent developments in type theory provide a natural way to reconcile cost and behavior of programs.
I'm not aware of previous work that used Spira's algorithm (which is designed
for a quite different probabilistic model, and for the APSP problem) in a
parallel setting.


<b>ALADDIN, Consciousness and Free Will from a TCS perspective</b>
<em>([Lenore Blum](lenore) and [Manuel Blum](manuel))</em>

<b>Abstract:</b>
Lenore will say some words about the NSF ALADDIN Center which she co-directed with Guy. Then Lenore and Manuel will say some words about what they have been working on for the past several years.


<b>Parallel Batch-Dynamic Graph Algorithms</b>
<em>([Julian Shun][julian])</em>

<b>Abstract:</b> As many real-world graphs change rapidly, it is crucial to design dynamic algorithms that efficiently maintain graph statistics upon updates, since the cost of re-computation from scratch can be prohibitive. Furthermore, due to the high frequency of updates, we can improve performance by using parallelism to process batches of updates at a time. We will present some of our research on designing parallel batch-dynamic graph algorithms to address these needs. Our research is inspired by Guy’s pioneering work on formalizing the batch-dynamic setting and designing efficient algorithms in it.


<b>Parallel Hierarchical Agglomerative Graph Clustering</b> <em>([Laxman Dhulipala][laxman])</em>

<b> Abstract:</b>
I will share some recent work on designing practical parallel algorithms for hierarchical agglomerative graph clustering. Although the problem is P-complete, we give a near-linear work RNC algorithm for a natural approximate version of the problem that can quickly process massive graphs. Along the way I will talk about some stories from working with Guy.


<b>Computational Models for Modern Architecture</b> <em>([Yan Gu][yan])</em>

<b> Abstract:</b>
Guy has designed many computational models for modern computer architecture that have been widely used.  In this talk, I will talk about my stories when working on these models with Guy, as well as some later work based on them.






<b>The Yug of Guy, and A Trifle</b> <em>([Siddhartha Chatterjee][sid])</em>

<b> Abstract:</b>
The talk will be in two parts. First, I will share some reflections on Guy through anecdotes during my time at CMU. Second, I will present a cute little divisibility problem that I worked on recently. ("Trifle" can be interpreted either as something trivial, or as a dessert.)




### Organizing Committee
* Umut Acar
* Naama Ben-David
* Laxman Dhulipala
* Yan Gu
* Julian Shun
* Virginia Williams


[acmharass]: https://www.acm.org/special-interest-groups/volunteer-resources/officers-manual/policy-against-discrimination-and-harassment
[spaa]: https://spaa.acm.org/
[laxman]: https://ldhulipala.github.io/
[yan]: https://www.cs.ucr.edu/~ygu/
[naama]: https://sites.google.com/corp/view/naama-ben-david/home
[yihans]: https://www.cs.ucr.edu/~yihans/
[phil]: http://www.cs.cmu.edu/~gibbons/
[elaine]: http://elaineshi.com/
[bob]: http://www.cs.cmu.edu/~rwh/
[sid]:https://www.cs.utexas.edu/people/faculty-researchers/siddhartha-chatterjee
[kuba]: https://research.google/people/105517/
[lars]: https://scholar.google.de/citations?user=G5XO7J4AAAAJ&hl=en
[brian]: https://brianwheatman.com/
[julian]: https://people.csail.mit.edu/jshun/
[zoomlink]: https://docs.google.com/document/d/1om-PvjaC49-zOxKRjcUxOGXcDayXjpq6VtrXr8CEoEg
[form]: https://forms.gle/myvcibc9Bs7wrJPd7
[lenore]: http://www.cs.cmu.edu/~lblum/
[manuel]: https://www.cs.cmu.edu/~mblum/
