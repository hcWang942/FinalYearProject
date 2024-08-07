# Final Year Project

This repository stores my final year project **Formalization of Auction Theory Using Lean and Mathlib**.

## Abstract

This thesis presents the formalization of fundamental theorems in Auction Theory using the Lean theorem prover and its accompanying mathematical library, Mathlib. Auction Theory, a component of economic theory, involves the design and analysis of auction mechanisms, which are formalized here to ensure mathematical precision. This project focuses on formalizing theorems related to first-price and second-price auctions, as well as Myerson's Lemma.

First, the fundamental concepts of first-price and second-price auctions are explored. In a first-price auction, the highest bidder wins and pays their bid amount, while in a second-price auction, the highest bidder wins but pays the second-highest bid. Formal statements and proofs for theorems regarding dominant strategies and bidder utility are developed. Specifically, the first-price auction is shown to have no dominant strategy, whereas the second-price auction incentivizes bidders to bid their true valuations.

Myerson's Lemma, a cornerstone of auction theory, is also formalized. It states that an allocation rule is implementable if and only if it is monotone, and it provides a unique payment rule ensuring the mechanism is dominant strategy incentive compatible (DSIC). The formalization process includes defining auction structures, bidding strategies, utility functions, and formal proofs of these theorems using Lean.

The contribution of these formalized results into Mathlib4 demonstrates the capabilities of modern proof assistants in handling complex economic models. This work not only contributes to the Lean community but also enhances the application of formal methods in economics and computer science, paving the way for future research and development in auction theory and mechanism design.

## Repository

This project is available at the following repository:
[https://github.com/math-xmum/gametheory](https://github.com/math-xmum/gametheory)

## Relevant Pull Requests to Mathlib

You can view the relevant pull requests to Mathlib at the following links:
- [Pull Request #13248](https://github.com/leanprover-community/mathlib4/pull/13248)
- [Pull Request #14163](https://github.com/leanprover-community/mathlib4/pull/14163)

## References

1. Roughgarden, Tim. *Twenty Lectures on Algorithmic Game Theory*. Cambridge University Press, 2020. [Link](https://www.cambridge.org/core/books/twenty-lectures-on-algorithmic-game-theory/A9D9427C8F43E7DAEF8C702755B6D72B)

2. Zipperer, Max. *Using Lean in the Mathematics Classroom*. Master's Thesis, 2022. [Link](https://www.contrib.andrew.cmu.edu/~avigad/Students/zipperer_ms_thesis.pdf)

3. Brasca, Riccardo. *Luxembourg 2021 Presentation*. Conference Presentation, 2021. [Link](https://webusers.imj-prg.fr/~riccardo.brasca/event/luxembourg-2021/pres.pdf)

4. The Lean Community. *The Lean Programming Language*. Official Website, 2023. [Link](https://lean-lang.org/)

5. The Lean Community. *The Lean Book: Formal Methods with Lean*. Online Book, Cambridge University Press, 2023. DOI: [10.1017/CBO9781316779309](https://doi.org/10.1017/CBO9781316779309)

6. The Lean Community. *Functional Programming in Lean*. Online Documentation, 2023. [Link](https://lean-lang.org/functional_programming_in_lean/getting-to-know/summary.html)

7. Avigad, Jeremy. *Practical Foundations for Formal Methods - Slides*. Lecture Slides, 2019. [Link](https://www.andrew.cmu.edu/user/avigad/Teaching/practical/slides_upitt.pdf)

8. The Lean Community. *The Lean Community Website*. Website, 2023. [Link](https://leanprover-community.github.io/)

9. Massot, Patrick. *Lean Blueprint*. GitHub Repository, 2023. [Link](https://github.com/PatrickMassot/leanblueprint)

10. Tao, Terence. *Formalizing the Proof of PFR in Lean4 Using Blueprint: A Short Tour*. Blog Post, 2023. [Link](https://terrytao.wordpress.com/2023/11/18/formalizing-the-proof-of-pfr-in-lean4-using-blueprint-a-short-tour/)

11. Author Names. *Title of the Paper*. *arXiv*, vol. 1910, no. 09336, 2023. [Link](https://arxiv.org/abs/1910.09336)

12. Buzzard, Kevin. *Tactics in Lean: Rewrite*. Part of the Formalising Mathematics 2023 Series on the Xena Project Website, 2023. [Link](https://www.ma.imperial.ac.uk/~buzzard/xena/formalising-mathematics-2023/Part_C/tactics/rw.html)

13. The Lean Community. *How to Contribute to Lean*. Contribution Guidelines on the Lean Community Website, 2023. [Link](https://leanprover-community.github.io/contribute/index.html)

14. The Lean Community. *Contribution Guide*. Website Section, 2023. [Link](https://leanprover-community.github.io/contribute/index.html)

15. The Lean Community. *Zulip Chat Search: Xiamen*. Lean Prover Community Zulip Chat, 2023. [Link](https://leanprover.zulipchat.com/#narrow/search/xiamen)

16. The Lean Community. *GitHub Permission Discussion for XMUM LEAN Group*. Topic on Lean Prover Community Zulip Chat, 2023. [Link](https://leanprover.zulipchat.com/#narrow/stream/287929-mathlib4/topic/github.20permission_XMUM.20LEAN.20group/near/434086443)

17. The Lean Community. *Mathlib4: The Lean Mathematical Library*. 2023. [Link](https://github.com/leanprover-community/mathlib4)

18. The Lean Community. *Naming Conventions*. Contribution Guidelines on the Lean Community Website, 2023. [Link](https://leanprover-community.github.io/contribute/naming.html)

19. The Lean Community. *Style Guide*. Contribution Guidelines on the Lean Community Website, 2023. [Link](https://leanprover-community.github.io/contribute/style.html)

20. GitHub. *About Pull Requests*. GitHub Documentation, 2023. [Link](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

21. Liu, Zhou, Lizhong Zhang, Siyu Tang, Yining Ma, and Hongyu Wang. "Formalization of Mathematics and AI: Interactions and Implications." In *Formal Methods for the Analysis of Complex Systems: A Tribute to the Work of Martin Wirsing on the Occasion of His 75th Birthday*, pp. 177-195. Springer, 2024. [Link](https://link.springer.com/chapter/10.1007/978-981-99-4833-8_9)
