# Homotopy (type) theory

A doctoral course on homotopy theory and homotopy type theory given by
[Andrej Bauer](http://www.andrej.com) and [Jaka Smrekar](https://www.fmf.uni-lj.si/~smrekar/)
at the [Faculty of mathematics and Physics](http://www.fmf.uni-lj.si/), University of Ljubljana,
in the Spring of 2019.

In this course we first overview the basics of classical homotopy theory. Starting with
the notion of locally trivial bundles, we motivate the classical definitions of
fibrations, from which we proceed to identify the abstract strucure of Quillen model
categories. We outline the basics of abstract homotopy theory in a Quillent model.

In the second part we introduce homotopy type theory from the point of view of classical
homotopy theory, deliberately avoiding the connections between homotopy type theory and
computer science. We show how type theory can be used to carry out homotopy-theoretic
arguments abstractly and "synthetically". The fact that any construction expressed in type
theory is homotopy invariant is both a blessing and a curse: a blessing because it never
lets us step outside of the realm of homotopy theory, and a curse because we it never lets
us step outside of the realm of homotopy theory.

## Course administration

We meet weekly on Tuesdays from 14:00 to 16:00 in lecture room 3.06 at the Mathematics
department.

There will be two take-home exams, one for each part of the course.


## Resources


### Homotopy theory

There is a wealth of resources available on the topic of homotopy theory. The following literature is recommended as reading material:

* J. Davis & P. Kirk, [Lecture Notes in Algebraic Topology](http://www.indiana.edu/~jfdavis/teaching/m623/book.pdf) (Chapter 4)
* R. Piccinini, [Lectures on Homotopy Theory](https://www.sciencedirect.com/bookseries/north-holland-mathematics-studies/vol/171) (Chapter 2)
* M. Hovey, [Model categories](https://web.math.rochester.edu/people/faculty/doug/otherpapers/hovey-model-cats.pdf) (Chapters 1-3)
* A. Strom, [The homotopy category is a homotopy category](https://mathscinet.ams.org/mathscinet/search/publdoc.html?arg3=&co4=AND&co5=AND&co6=AND&co7=AND&dr=all&pg4=AUCN&pg5=TI&pg6=PC&pg7=ALLF&pg8=ET&r=1&review_format=html&s4=strom&s5=the%20homotopy%20category&s6=&s7=&s8=All&sort=Newest&vfpref=html&yearRangeFirst=&yearRangeSecond=&yrop=eq)
* P. G. Goerss & J. F. Jardine, [Simplicial homotopy theory](https://www.springer.com/us/book/9783034601887) (Chapters I and II)
 * Daniel G. Quillen, [Homotopical algebra](https://www.springer.com/gp/book/9783540039143)

### Homotopy type theory

All lectures are recorded on video and can be watched in the [HoTT-2019 video channel](https://vimeo.com/channels/1457250). The lecture notes are also available [here](http://www.andrej.com/zapiski/HoTT-2019/).


Being a new topic, homotopy type theory is still developing. Consequently, reading
material and resources are a bit more fluid and scattered. A central resource is the "HoTT book", although it is hard-going for the unexperienced:

* Univalent foundations program, [Homotopy type theory: Univalent foundations of mathematics](https://homotopytypetheory.org/book/)

The following introductory notes are targeted at teaching homotopy type theory:

* Egbert Rijke, [Introduction to Homotopy Type Theory](http://www.andrew.cmu.edu/user/erijke/hott/), a graduate course taught at Carnegie Mellon University. The accompanying [lecture notes](http://www.andrew.cmu.edu/user/erijke/hott/hott_intro.pdf) is recommended as reading material.

* [Martín Escardó](https://www.cs.bham.ac.uk/~mhe/), [Introduction to Univalent Foundations of Mathematics with Agda](https://www.cs.bham.ac.uk/~mhe/HoTT-UF-in-Agda-Lecture-Notes/HoTT-UF-Agda.html) is a set of lecture notes written in literal Agda (text interspersed with [Agda code](http://wiki.portal.chalmers.se/agda)). It explains the basics very thoroughly and very well. You may safely ignore the fact that it is all formalized and computer-checked, altought you may also be interested in learning how to use Agda, in which case you can consult the [lecture notes GitHub repository](https://github.com/martinescardo/HoTT-UF-Agda-Lecture-Notes).

Here are some additional resources:

* [Daniel Grayson](https://faculty.math.illinois.edu/~dan/): [An introduction to univalent foundations for mathematicians](https://arxiv.org/pdf/1711.01477.pdf), targeted at a general mathematical audience,
* [Michael Shulman](https://home.sandiego.edu/~shulman/): [Homotopy type theory: the logic of space](https://arxiv.org/abs/1703.03007),
  worth reading if you would like to expand your understanding of "space",
* [Steve Awodey](http://www.andrew.cmu.edu/user/awodey/) and [Michael Warren](http://mawarren.net): [Homotopy theoretic models of identity types](https://arxiv.org/abs/0709.0248), the original paper introducing the interpreation of identity types in Quillen model categories.

## Course outline

### Homotopy theory

####  Background & bundles

##### Background

* What does (a part of) math deal with?
* Distinguishing between objects: relax, distinguish, stiffen
* Homotopy theory as a natural domain of algebraic invariants
* Homotopy theory as means of rephrasing a geometric problem

#### Bundles

* Bundles are omnipresent
* Vector bundle and its frame bundle
* Bundles with structure group
* Principal bundles and classification
* Lifting properties
* Homotopization of bundles

####  Fibrations of topological spaces, and their classification

* Hurewicz fibrations; definition in terms of the right lifting property with respect to inclusions Z->Zx[0,1]
* Pullbacks and retracts of fibrations are fibrations
* Any map decomposes functorially as a composite of a SDR inclusion followed by fibration
* The concept of a lifting function
* The fibres of a fibration are homotopy equivalent
* Homotopy fibre
* Puppe sequence

####  Cofibrations & model structure

* Homotopy extension property, cofibration, Eckmann-Hilton duality
* Pushouts and retracts of cofibrations are cofibrations
* Any map decomposes functorially as a composite of a cofibration followed by a `trivial` fibration
* Quillen closed model category
* Model category on Top with homotopy equivalences, Hurewicz fibrations, and Hurewicz cofibrations

####  Loop spaces, suspensions and other gadgets

### Homotopy type theory

#### Type theory (motivated by simplicial sets): `Π`, `Σ`

[Video](https://vimeo.com/330992581) and [notes](http://www.andrej.com/zapiski/HoTT-2019/HoTT-2019-04-16/HoTT-2019-04-16%20Type%20theory.pdf).

Outline:

* Type theory as a theory of constructions
* The notion of a dependent type
* Types as sets, dependent types as families of sets
* Types as spaces, dependent types as fibrations
* Basic type-theoretic constructions:
    * dependent products
    * dependent sums
    * basic types `0`, `1`, `N`

#### Identity types as path objects

[Video](https://vimeo.com/332004992) and [notes](http://www.andrej.com/zapiski/HoTT-2019/HoTT-2019-04-23/HoTT-2019-04-23%20Identity%20types.pdf).

Outline:

* Identity types as path objects
* Type-theoretic rules for identity types
* Basic homotopy-theoretic constructions in terms of identity types:
    * the groupoid of paths
* Iterated identity types

#### Truncations

* Contractible spaces
* Propositions, sets, and h-levels
* Truncation as a type-theoretic construction
* The embedding of logic into type theory (using propositional truncation)
* Basic homotopy-theoretic constructions in terms of truncation:
    * loop space vs. fundamental group
    * path-connectedness vs. contractibility
    * surjectivity vs. split epimorphism
* Whiteheads's principle

#### Synthetic homotopy theory

* Inductive types, examples
* Higher-inductive types (HITs)
* Examples: circle, interval, suspension
* Truncations as HITs

#### Univalence axiom

* The idea that equivalent structures are equal
* Homotopy equivalences in type theory
* Univalence axiom
* Consequences of the univalence axiom

#### Applications of univalence: loop space, `π₁(S¹) = Z`

* The loop space of a pointed space
* The fundamental group of a pointed space
* Proof that `π₁(S¹) = Z`


