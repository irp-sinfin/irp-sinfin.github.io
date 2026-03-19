---
id: 1467
title: ''
date: '2019-09-15T10:07:13-03:00'
author: 'Alejandro Díaz-Caro'
excerpt: ''
layout: revision
guid: 'http://www.lia-sinfin.org/?p=1467'
permalink: '/?p=1467'
---

<div style="text-align: center;"><span style="font-size: x-large;">Logic and Foundations of Programming Languages Day</span>  
**May 21, 2018  
Departamento de Computación, FCEN, Universidad de Buenos Aires  
Aula 8, Pabellón 2  
Ciudad Universitaria, Buenos Aires**</div>The Laboratoire International Associé INFINIS organize a day on logic and foundations of programming languages. The intention is to bring together researchers from the Río de la Plata region. We will profit from the visit of several French colleagues who will be in the region on that date.

### Program:

**09:30 - 10:00** Welcome coffee

**10:00 - 10:25** [Beta Ziliani](https://people.mpi-sws.org/~beta/): Introducing Mtac2: first-class tactics with first-class types in Coq \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-BZiliani.pdf)\]  
**10:25 - 10:50** [Benoît Valiron](http://www.monoidal.net/): From symmetric pattern-matching to quantum control \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-BValiron.pdf)\]  
**10:50 - 11:15** [Alejandro Díaz-Caro](https://www-2.dc.uba.ar/staff/adiazcaro): A lambda calculus for density matrices \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-ADiazCaro.pdf)\]

**11:15 - 11:40** Mate Break

**11:40 - 12:05** [Antonio Bucciarelli](https://www.irif.fr/~buccia/): n-dimensional Boolean algebras \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-ABucciarelli.pdf)\]  
**12:05 - 12:30** [Olivier Carton](https://www.irif.fr/~carton/): Randomness with constraints \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-OCarton.pdf)\]  
**12:30 - 12:55** [Santiago Figueira](http://www.glyc.dc.uba.ar/santiago/): Probing the Flexibility of the Language of Thought \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-SFigueira.pdf)\]

**12:55 - 14:40** Lunch

**14:40 - 15:05** [Alexandre Miquel](https://www.fing.edu.uy/~amiquel/): Implicative algebras: a new foundation for realizability and forcing  
**15:05 - 15:30** [Mauricio Guillermo](http://www.cmat.edu.uy/~mauricio/index-english.html): A cardinals’ heresy in classical realizability  
**15:30 - 15:55** [Pierre Pradic](https://dblp.uni-trier.de/pers/hd/p/Pradic:Pierre): A Curry-Howard Approach to Church’s Synthesis  
**15:55 - 16:20** [Luc Pellissier](https://lipn.univ-paris13.fr/~pellissier/): Intersection types, approximations and resource modalities \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-Pellissier.pdf)\]

**16:20 - 16:45** Mate Break

**16:45 - 17:10** [Delia Kesner](https://www.irif.fr/~kesner/): Call by need, neededness and all that  
**17:10 - 17:35** [Andrés Viso](https://www.linkedin.com/in/andres-ezequiel-viso-a971b739/): Type Soundness for Path Polymorphism \[[slides](http://infinis.org/wp-content/uploads/2018/05/Slides-AViso.pdf)\]  
**17:35 - 18:00** [Pablo Barenbaum](https://scholar.google.is/citations?user=sBPpMY8AAAAJ): Factoring Derivation Spaces via Intersection Types

Local organizers:  
Andrés Viso (aeviso@dc.uba.ar)  
Alejandro Díaz-Caro (adiazcaro@icc.fcen.uba.ar)

### Abstracts

- **Beta Ziliani: Introducing Mtac2: first-class tactics with first-class types in Coq**  
    Mtac2 is a novel language for building tactics in the Coq theorem prover. A tactic is a program which solves the current goal, perhaps creating new subgoals. The novelty in Mtac2 is that its tactics are written in the same language of the prover and, more importantly, have their types embedded in the language. Therefore, an Mtac2 tactic could precisely state in its type what kind of goals it is able to solve, leading to self-documented, more-maintainable tactics.  
    In this talk I will introduce the main ideas behind Mtac2, and its application in the widely-used Iris logic framework.
- **Benoît Valiron: From symmetric pattern-matching to quantum control**  
    From a programmer's perspective, quantum algorithms are simply classical algorithms having access a special kind of memory featuring particular operations: quantum operations. They therefore feature two kinds of control flow. One is purely conventional and is concerned in the classical part of the algorithm. The other -- dubbed quantum control -- is more elusive and still subject to debate: if the notion of quantum test is reasonnably consensual, the quantum counterpart of loops is still not believed to be meaningful.  
    In this talk, we argue that, under the right circumstances, a reasonnable notion of quantum loop is possible. To this aim, we propose a typed, reversible language with lists and fixpoints, extensible to linear combinations of terms. The language admits a reduction strategy in the spirit of algebraic lambda-calculi. Under the restriction of structurally recursive fixpoints, it is shown to capture unitary operations. It is expressive enough to represent several of the unitaries one might be interested in expressing.
- **Alejandro Díaz-Caro: A lambda calculus for density matrices**  
    In this talk I will present two flavors of a quantum extension to the lambda calculus. The first one, λρ, follows the approach of classical control/quantum data, where the quantum data is represented by density matrices. We provide an interpretation for programs as density matrices and functions upon them. The second one, λρ°, take advantage of the density matrices presentation in order to follow the mixed trace of programs in a kind of generalised density matrix. Such a control can be seen as a weaker form of the quantum control and data approach. In addition, I will comment on some advances on ongoing works with Malena Ivnisky and Henrán Melgratti (fix point operator), Agustín Borgna (translation to a well-known quantum lambda calculus, and possible extension of the languages), Lucas Romero (polymorphisme) and Alan Rodas and Pablo E. Martínez López (a Haskell implementation).
- **Antonio Bucciarelli: n-dimensional Boolean algebras**  
    n-dimensional Boolean algebras (nBA) generalise BA to the case of n perfectly symmetric truth values. The talk provides an overview of their algebraic structure and of the corresponding propositional calculus (joint work in progress with A.Ledda, F. Paoli and A. Salibra)
- **Olivier Carton: Randomness with constraints**  
    We first recall the definition of normality which is a kind of weak randomness. We show how some constraints can be imposed without loosing randomness. We even give an sharp upper bound of what can be imposed.
- **Santiago Figueira: Probing the Flexibility of the Language of Thought**  
    Recent approaches to human concept learning have successfully combined the power of symbolic, infinitely productive rule systems and statistical learning. Many of these studies focus on uncovering the underlying language structuring these representations and providing the substrate for thought. Here, we perform two concept learning experiments to show the strong dependence of concept difficulty with prior concept exposure. We model concept learning times using a probabilistic grammar with Bayesian updating, which accurately captures the entire observed patterns. By portraying the Language of Thought as a flexible system of rules, we highlight the difficulties of trying to pin it down empirically.
- **Alexandre Miquel: Implicative algebras: a new foundation for realizability and forcing**  
    In this talk, I will introduce the notion of implicative algebra, a simple algebraic structure intended to factorize the model constructions underlying intuitionistic forcing (Kripke), classical forcing (Cohen), intuitionistic realizability (Kleene) and classical realizability (Krivine). As we shall see, the salient feature of implicative algebras is that their elements can be seen both as truth values and as (generalized) realizers, thus blurring the frontier between proofs and types. I will show that implicative algebras induce a broad family of triposes (i.e. models of higher-order logic) - the implicative triposes - that encompass Heyting triposes, Boolean triposes, intuitionistic realizability triposes and classical realizability triposes, thus providing a unified framework for expressing forcing and realizability, both in intuitionistic and classical logic. I shall conclude by presenting the perspectives in the construction of new models of set theory.
- **Mauricio Guillermo: A cardinals’ heresy in classical realizability**  
    The simplest coherent and non-trivial model to define in classical realizability is the so called *Threads Model*. Despite being simple to define, this model has amazing properties. It does not satisfy the full axiom of choice, even though is compatible with the dependent choice axiom. Moreover, it denies the continuum hypothesis in a violent way, since the intermediate cardinals between ℵ<sub>0</sub> and the continuum are not even well founded.  
    We will visit some ideas of "Realizability algebras II: new models of ZF + DC", by Krivine; using as reference the presentation homonymous of this talk, by Miquel.
- **Pierre Pradic: A Curry-Howard Approach to Church’s Synthesis**  
    We propose LMSO, a proof system inspired from Linear Logic, as a proof-theoretical framework to extract finite-state stream transducers from linear-constructive proofs of omega-regular specifications. We advocate LMSO as a stepping stone toward semi-automatic approaches to Church’s synthesis combining computer assisted proofs with automatic decisions procedures. LMSO is correct in the sense that it comes with an automata-based realizability model in which proofs are interpreted as finite-state stream transducers. It is moreover complete, in the sense that every solvable instance of Church’s synthesis problem leads to a linear-constructive proof of the formula specifying the synthesis problem.
- **Luc Pellissier: Intersection types, approximations and resource modalities.**  
    Intersection types are widely used to prove normalization properties of different calculi. We show here how common intersection type systems can be defined from a notion of approximation, and how their usual proofs of adequation with respect to a notion of reduction is a direct consequence of normalization of propositional linear logic.  
    Finally, we show that the approximations are only used here as a way to use resource modalities in a very general semantics of linear logic which is a wide-ranging generalization of species of structures.
- **Delia Kesner: Call by need, neededness and all that**  
    We show that call-by-need is observationally equivalent to weak-head needed reduction. The proof of this result uses a semantical argument based on a (non-idempotent) intersection type system called V. Interestingly, system V also allows to syntactically identify all the weak-head needed redexes of a term.
- **Andrés Viso: Type Soundness for Path Polymorphism**  
    Path Polymorphism is the ability to define functions that can operate uniformly over arbitrary recursively specified data structures. Its essence is captured by patterns of the form xy which decompose a compound data structure into its parts. Typing these kinds of patterns is challenging since the type of a compound should determine the type of its components. We propose a static type system (i.e. no run-time analysis) for a pattern calculus that captures this feature. Our solution combines type application, constants as types, union types and recursive types. We address the fundamental properties of Subject Reduction and Progress that guarantee a well-behaved dynamics. Both these results rely crucially on a notion of pattern compatibility and also on a coinductive characterisation of subtyping.
- **Pablo Barenbaum: Factoring Derivation Spaces via Intersection Types**  
    In this talk we will introduce a non-idempotent intersection type system for the λ-calculus in which proof normalization is confluent. The system enjoys the expected good properties: subject reduction, strong normalization, and a very regular theory of residuals. A correspondence with the λ-calculus is established by means of simulation theorems. The machinery of non-idempotent intersection types allows us to track the usage of resources required to obtain an answer. In particular, it induces a notion of garbage: a computation is garbage if it does not contribute to obtaining an answer. Using these notions, we show that the derivation space of a λ-term may be factorized using a variant of the Grothendieck construction for semilattices. This means, in particular, that any derivation in the λ-calculus can be uniquely written as a garbage-free prefix followed by garbage.

## Photos of the event

- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_115150-1024x768-1024x768.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_115150-1024x768-1024x768.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_121900-1024x768-1024x768.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_121900-1024x768-1024x768.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_154835-1024x768-1024x768.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_154835-1024x768-1024x768.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_160516-1024x768-1024x768.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_160516-1024x768-1024x768.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_171812-768x1024-768x1024.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_171812-768x1024-768x1024.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_174545-768x1024-768x1024.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_174545-768x1024-768x1024.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_174555-1024x768-1024x768.jpg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/small-IMG_20180521_174555-1024x768-1024x768.jpg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.54.39-768x1024-768x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.54.39-768x1024-768x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.14-1-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.14-1-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.15-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.15-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.16-1-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.16-1-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.17-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.17-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.20-1-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.20-1-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.21-1-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.21-1-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.21-2-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.21-2-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.24-2-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.24-2-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.25-2-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.57.25-2-576x1024-576x1024.jpeg)</figure>
- <figure>[![](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.58.42-576x1024-576x1024.jpeg)](http://www.lia-sinfin.org/wp-content/uploads/2019/09/WhatsApp-Image-2018-05-21-at-22.58.42-576x1024-576x1024.jpeg)</figure>