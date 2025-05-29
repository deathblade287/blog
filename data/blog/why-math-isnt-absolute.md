---
title: why math isn't absolute
date: '2022-04-08'
tags: []
draft: false
summary: Discusses the inherent limitations of mathematics. He references Gödel's Incompleteness Theorem, which asserts that mathematics is incomplete, inconsistent, and undecidable.
images: []
layout: PostLayout
canonicalUrl:
---

The boundary of human naïveté knows no end. We have this innate belief that math is certain but we couldn’t be further from the truth. German mathematician David Hilbert gave a fiery speech in 1930 which ended with the words, “Our slogan shall be, we must know — we will know”. These words are literally on his grave. To his great disappointment however and the common man’s amusement, it was his speech that triggered a full-blown revolt in mathematics ending with the conclusion that our beloved subject is, after all, relatively unpredictable or rather the “best approximate” of reality. A logician attending the said speech later released a paper on what is now called “Gödel’s Incompleteness Theorem”, which proved mathematics incomplete, inconsistent and undecidable. I’m going to take a stab at simplifying the same in this article.

![David Hilbert](https://static.wixstatic.com/media/58948c_d6e8a76cd78d4810a22a2cd7d3cd6212~mv2.png/v1/fill/w_684,h_502,al_c,lg_1,q_85,enc_auto/58948c_d6e8a76cd78d4810a22a2cd7d3cd6212~mv2.png)

Twin primes are prime numbers that are 1 count apart, for example, 3 and 5, 11 and 13, 17 and 19, etc. Going up the number line, prime numbers are already hard to spot and an even more arduous task is to find twin primes which makes one ask the question, “Are there infinite twin primes?”. Logically, the answer is yes but mathematicians are yet to prove this. The uncanny part, however, is that we might never be able to. This is because what has been proven is that in any system of mathematics where we are able to perform basic arithmetics, there will always be factual statements that are impossible to prove, which means that math is inherently incomplete.
Imagine a town with only fully grown men and a single barber (just humour me). This town has only 2 rules (no, that does not mean murder is allowed). The first one is that the barber can’t shave men who shave their own beards and the second one is, the barber has to shave men that don’t shave their own beard. Simple enough right? However, the question now arises — who shaves the barber’s beard? If he shaves his own beard then the barber can’t shave his beard but he is the barber and visa versa as well which results in the conclusion “the barber can only shave his beard if he cannot shave his beard”. This eerie concept is known as self-reference. While conducting thought experiments, British mathematician and philosopher, Bertrand Russell discovered a loophole in set theory using this paradox. An axiom of sets is that they can contain other sets as well or even contain themselves. The problem arises when we consider a set of all sets that don’t contain themselves. Let’s name this set R. If R doesn’t contain itself then it must by definition it must contain itself and if it does contain itself then by definition it must not contain itself. So, “R contains itself, if and only if, it doesn’t”. This problem was later solved by removing self-referential sets like “the set of all sets” and “the set of all sets that contain themselves”, however, as perplexing and mind-bending as it is, this loophole helped label math as inconsistent meaning that it is essentially not free of contradictions.
Alan Turing (also known as “the father of modern computers”, no big deal) was in pursuit of answering the question “Is there an algorithm that can always determine whether a statement follows the axioms?” when he came up with the idea of the machine you’re reading this on. Essentially what he tries to explain is if you take a machine that either halts or loops when a program is executed. Can you create another machine that determines whether the first one will halt or loop after looking at the code? We don’t know right now but let’s assume that we made one and somehow it just works every time. We’ll name this machine h. Now, let’s add a condition to the end of it; if the code outputs halts then the machine’s final output should be “loop” and if the code outputs loop then the final output should be “halt”. We name this new machine h+. If we then input h+’s code back into h+, what will be the output? Well if it loops the output will be “halt” and if it halts the output will be “loop” which are contradictions since h+ is predicting the result of its own code. Hence proved that math is undecidable as well and the answer to the initial equation is no, you cannot create an algorithm that predicts whether a statement will follow the axioms.
If what I’m saying is true then why are we even studying mathematics in school? It’s because while mathematics has many fundamental flaws, it is in exploring the unknown that we discover new things only later to realize their use case in the real world.

<hr />

### Credits & Further Research

Inspiration for this article was taken from the following video by Vertasium : https://www.youtube.com/watch?v=HeQX2HjkcNo&t=566s

https://www.britannica.com/science/twin-prime-conjecture

https://www.quantamagazine.org/how-godels-incompleteness-theorems-work-20200714/#:~:text=G%C3%B6del%20numbers%20are%20integers%2C%20and,%3A%20the%20formula%200%20%3D%200.

https://artofproblemsolving.com/wiki/index.php/Zermelo-Fraenkel_Axioms#:~:text=The%20Zermelo%2DFraenkel%20Axioms%20are,could%20be%20called%20a%20set

https://en.wikipedia.org/wiki/Turing_machine
