# Math 614, Spring 2026: Mirror symmetry for toric varieties

## Course description
Let $X$ be an $n$-dimensional smooth projective toric variety over the complex numbers. 
In the 90s, Morelli [M] showed that there is injective homomorphism from the Grothendieck group of torus-equivariant vector bundles on $X$ into constructible functions $\mathbf{R}^n \to \mathbf{Z}$. 
Moreover, Morelli explicitly identified the image of this map. 
Around 2010, Fang–Liu–Treumann–Zaslow [FLTZ] proved the natural categorification of this: they provided a fully faithful embedding of torus-equivariant quasicoherent sheaves on $X$ into constructible sheaves on $\mathbf{R}^n$. 
Moreover, they explicitly identified the essential image of their embedding in terms of a microsupport condition. 

To goal of this course is to explain a proof the Fang–Liu–Treumann–Zaslow, however we will prove the result over the sphere spectrum. 
We'll use the path to this theorem as an opportunity to introduce a number of tools, starting with toric varieties and derived/spectral algebraic geometry, then moving on to tools more specific to the proof. 
Our exposition will follow a recent paper of Bai and Hu [BH]. 
In particular, we plan to explain how to deduce a nonequivariant version of the theorem (originally proved by Kuwagaki) from the equivariant one. 

### Expected topics
+ Toric geomerty
+ How to work with ∞-categories
+ Spectra and spectral algebraic geometry
+ Constructible sheaves
+ The six functor formalism on topological spaces
+ Toric mirror symmetry

## General information
**Instructor** Peter Haine
+ Office: KAP 248C
+ e-mail: [phaine@usc.edu](mailto:phaine@usc.edu)

**Time** 12:00pm–1:20pm on Mondays and Wednesdays, occassionally a Friday may replace some lectures

**Location** KAP 427 ~KAP 265~ 

**Office hour** Wednesdays at 2:00pm in KAP 248C (though we can adjust to a different time if this is inconvenient for people)

## Assignments/Grading

### Lecture notes
Shortly after every lecture, [below](#lecture-schedule--notes) I will post detailed handwritten notes for the lecture. The only work for this course will be to type up these notes in a class Overleaf/Git Repo. I'll likely edit them a bit after you type them.

I'll type the notes for the first two lectures. 
In the first week, we'll create a rotating schedule for typing up the notes. 
Here are the basic expectations:
+ You should finish typing the lecture notes by the lecture one week later.
  (So if you're typing up notes for Wednesday, 1/21, you should do so by Wednesday 1/28).
+ You should do a nice job of typing the notes, formatting them in a style consistent with the previous notes (using the first two lectures as an example), checking for typos, filling small gaps, and adding references when it makes sense.
+ Please try to format the LaTeX code nicely.
  This makes editing easier.

[Below](#guidelines-for-typing-up-the-lecture-notes) you can find detailed guidelines for typing up the notes.

### Grading scheme
100% typing up lecture notes.

## Lecture schedule & notes
_The topics of the lectures that haven't yet been given are tentative._

+ [Overleaf for typed notes](https://www.overleaf.com/read/kpkwrssmtzrm#f9bb46) (viewable by anyone with the link)
+ [Git Repo for typed notes](https://github.com/peterjhaine/toric_mirror_symmetry_notes) (to get access, ask me)
+ Order that we'll cycle through for typing the notes (after the first two lectures): Baran, Jiayi, Michael, Yahya, Yash, Yijie.

[**Zoom link for any online lectures**](https://usc.zoom.us/j/98589530508?pwd=hVHu7e5haipMekaYUBw4OSD4SLEsRC.1)


|   \#    |   Day  | Date  | Lecture title | References | Scribe |
| :----:  | :----: | :---  |    :----:      | :----      | :----      |
|   1     |   M    | 1/12  | Overview <br> [Notes](lecture_notes/01-12-2026.pdf), [Recording](https://youtu.be/Vln_P_1s9Fo)  |  [BH, [§1](https://arxiv.org/pdf/2501.06649#section.1)]          | Peter |
|   2     |   W    | 1/14  | Toric geometry I: <br> Monoid algebras & cones <br> [Notes](lecture_notes/01-14-2026.pdf), [Recording](https://youtu.be/MfMJuqZ23XA)    |  [F, Chapter 1]          | Peter |
|         |   M    | 1/19   |  **MLK Day** <br> No Lecture    |           |    |
|   3     |   W    | 1/21  | Toric geometry II: <br> Fans & toric schemes <br> [Notes](lecture_notes/01-21-2026.pdf), [Recording](https://youtu.be/70ivBuZpZUs)    |  [F, Chapter 1]          | Baran   |
|   4     |   M    | 1/26  | Toric geometry III: <br> Results from convex geometry <br> [Notes](lecture_notes/01-26-2026.pdf), [Recording](https://youtu.be/lZkx98dk_NM)   | [F, Chapter 1]          | Jiayi   |
|   5     |   W    | 1/28  | Toric geometry IV: <br> Functoriality & smoothness <br> [Notes](lecture_notes/01-28-2026.pdf), [Recording](https://youtu.be/S2f9Zr6V-oo) |   [F, §2.1]        | Michael |
|   6     |   M    | 2/2   | Toric geometry V: <br> Properness & polytopes <br> [Notes](lecture_notes/02-02-2026.pdf), [Recording](https://youtu.be/MO99ZampdQA)   | [F, §§1.5, 2.4]          | Yahya   |
|   7     |   W    | 2/4   |  Toric geometry VI: <br> Torus-equivariant divisors & polytopes <br> [Notes](lecture_notes/02-04-2026.pdf), [Recording](https://youtu.be/ibrvIcWAogo)    | [F, §3.4]          | Yash    |
|         |   M    | 2/9   | **No Lecture**     |           |    |
|   8     |   W    | 2/11   | Introduction to ∞-categories I <br> [Notes](lecture_notes/02-11-2026.pdf), [Recording](https://youtu.be/mSTgGZuNNW8)     |     [C, Chapter 1]      | Yijie   |
|         |   M    | 2/16  | **Presidents' Day** <br> No Lecture    |           |    |
|   9     |   W    | 2/18  | Introduction to ∞-categories II <br> [Notes](lecture_notes/02-18-2026.pdf), [Recording](https://youtu.be/iAT_rQZ6GHg)   |     [C, Chapter 1]      | Baran   |
|   10    |   M    | 2/23  | More on higher categories and (commutative) monoids <br> [Notes](lecture_notes/02-23-2026.pdf), [Recording](https://youtu.be/jMFlpmDazZg)    |  [C, Chapter 4]         | Jiayi   |
|   11    |   W    | 2/25  | Spectra I <br> [Notes](lecture_notes/02-25-2026.pdf), [Recording](https://youtu.be/tcZ4L0TwKeQ)     | [C, Chapter 3]          | Michael |
|   12    |   W    | 3/4   | Spectra II <br> [Notes](lecture_notes/03-04-2026.pdf), [Recording](https://youtu.be/tbjHwgT0nhQ)    | [C, Chapter 3]          | Yahya   |
|   13    |   F    | 3/6   | Spectra III/Review of the functor of points <br> [Notes](lecture_notes/03-06-2026.pdf), [Recording](https://youtu.be/QtdX0pZdpFA)   | [C, §§16.2–16.3; H, §§2.7 & 7.1]          | Yash    |
|   14    |   M    | 3/9   | More on the functor of points <br> [Notes](lecture_notes/03-09-2026.pdf), [Recording](https://youtu.be/L1azQ64I5vs)    |  [H, §4]         | Yijie   |
|   15    |   W    | 3/11  | Spectral algebraic geometry I <br> [Notes](lecture_notes/03-11-2026.pdf), [Recording](https://youtu.be/v5FIxrDYN_o)   | [C, §5.1]          | Baran   |
|   16    |   F    | 3/13  | Spectral algebraic geometry II <br> [Notes](lecture_notes/03-13-2026.pdf), [Recording](https://youtu.be/hby9xqlOMe0)    | [HTT, [§6.5.4](https://www.math.ias.edu/~lurie/papers/HTT.pdf#subsection.6.5.4)]        | Jiayi   |
|         |   M    | 3/16  |  **Spring Break** <br> No Lecture    |           |    |
|         |   W    | 3/18  |  **Spring Break** <br> No Lecture    |           |    |
|   17    |   M    | 3/23  | Starting the proof of toric mirror symmetry <br> [Notes](lecture_notes/03-23-2026.pdf), [Recording](https://youtu.be/68bQHOEq3O0)   | [BH, §§[1.2](https://arxiv.org/pdf/2501.06649#subsection.1.2) & [2](https://arxiv.org/pdf/2501.06649#section.2)], and for idempotent algebras see [CSY, [§5.1](https://arxiv.org/pdf/2007.13089#subsection.5.1); HA, [§4.8.2](https://www.math.ias.edu/~lurie/papers/HA.pdf#subsection.4.8.2)]         | Michael |
|   18    |   W    | 3/25  | Quasicoherent sheaves on affine toric stacks I <br> [Notes](lecture_notes/03-25-2026.pdf), [Recording](https://youtu.be/CZ63xk6luy0)     | [BH, [§3](https://arxiv.org/pdf/2501.06649#section.3)]          | Yahya   |
|   19    |   M    | 3/30  | Quasicoherent sheaves on affine toric stacks II <br> [Notes](lecture_notes/03-30-2026.pdf), [Recording](https://youtu.be/pVBzlK-NWOk)    | [BH, [§3](https://arxiv.org/pdf/2501.06649#section.3)], split simplicial objects [Kerodon, [Tag 04S6](https://kerodon.net/tag/04S6)], (co)monadic descent [HA, [§4.7.5](https://www.math.ias.edu/~lurie/papers/HA.pdf#subsection.4.7.5)],           | Yash    |
|   20    |   W    | 4/1   | Quasicoherent sheaves on affine toric stacks III <br> [Notes](lecture_notes/04-01-2026.pdf), [Recording](https://youtu.be/dmvmiDMSzVQ)    | [BH, [§3.3](https://arxiv.org/pdf/2501.06649#subsection.3.3)], monads [HA; [§4.7](https://www.math.ias.edu/~lurie/papers/HA.pdf#section.4.7); R, [Chapter 5](https://emilyriehl.github.io/files/context.pdf#chapter.5)]          | Yijie   |
|   21    |   W    | 4/8   | Presentability & the six functors <br> [Notes](lecture_notes/04-08-2026.pdf), [Recording](https://youtu.be/aCQ59eD5j9c)  | [Kerodon, [Tag 04S6](https://kerodon.net/tag/04KE)]    | Baran   |
|   22    |   F    | 4/10  | The six functors & convolution products <br> [Notes](lecture_notes/04-10-2026.pdf), [Recording](https://youtu.be/DxH2mI3SmsE)  | six functors [HM; V], convolution products [BH, [§4.1](https://arxiv.org/pdf/2501.06649#subsection.4.1)]           | Jiayi   |
|   23    |   M    | 4/13  | From the combinatorial model to constructible sheaves <br> [Notes](lecture_notes/04-13-2026.pdf), [Recording](https://youtu.be/Li8EP0Sdv5A)  |  [BH, §§[4.1](https://arxiv.org/pdf/2501.06649#subsection.4.1)–[4.3](https://arxiv.org/pdf/2501.06649#subsection.4.3)], recognition criterion for locally constant sheaves [[HPT](https://arxiv.org/abs/2010.06473)]         | Michael |
|   24    |   W    | 4/15  | Descent for idempotent algebras <br> [Notes](lecture_notes/04-15-2026.pdf), [Recording](https://youtu.be/MZ8WnH0zu2M)     |  idempotent algebras [[C-AdRC8](https://www.ihes.fr/~dustin/files/AlgebraicDeRham/Lec8.pdf)], [BH, [§4.5](https://arxiv.org/pdf/2501.06649#subsection.4.5)]         | Yahya   |
|   25    |   M    | 4/20  | Towards full faithfulness of $\kappa_{\Sigma}$ <br> [Notes](lecture_notes/04-20-2026.pdf), [Recording](https://youtu.be/MIn7xseIPJw)  | [BH, [§4.5](https://arxiv.org/pdf/2501.06649#subsection.4.5)], limits of fully faithful functors [HSR, [Proposition 2.1](https://arxiv.org/pdf/2503.03916#equation.2.1)]          | Yash    |
|   26    |   W    | 4/22  | Compact generators for spectral presheaves & the FLTZ stratification <br> [Notes](lecture_notes/04-22-2026.pdf), [Recording](https://youtu.be/weyovOuR4Bc) | compact generators for spectral presheaves [Rot, [§2.2](https://www.math.ias.edu/~lurie/papers/Waldhaus.pdf#page=9)], the FLTZ stratification [BH, [§4.4](https://arxiv.org/pdf/2501.06649#subsection.4.4)]          | Yijie   |
|   27    |   M    | 4/27  | Exodromy & finishing the proof that $\kappa_{\Sigma}$ is fully faithful | [BH, [§4.4](https://arxiv.org/pdf/2501.06649#subsection.4.4)]           | Michael |
|   28    |   W    | 4/29  | Microsupport & microlocal characterization of the image of $\kappa_{\Sigma}$  | [BH, [§5](https://arxiv.org/pdf/2501.06649#section.5)]          | TBA |
|   29    |   M    | 5/04  | De-equivariantization & loose ends | [BH, [§6.1](https://arxiv.org/pdf/2501.06649#subsection.4.4)]          | TBA |

## References

**[BH]** Q. Bai and Y. Hu, _Toric mirror symmetry for homotopy theorists_, Jan. 2025, [arXiv:2501.06649](https://arxiv.org/abs/2501.06649).

**[C-AdRC8]** D. Clausen, _Lecture 8: Derived quasi-coherent sheaves_, Lecture notes for _Algebraic de Rham cohomology_, available at [ihes.fr/~dustin/files/AlgebraicDeRham/Lec8.pdf](https://www.ihes.fr/~dustin/files/AlgebraicDeRham/Lec8.pdf).

**[C]** B. Cnossen, _Stable homotopy theory and higher algebra_, Book in progress, available at [sites.google.com/view/bastiaan-cnossen/home](https://sites.google.com/view/bastiaan-cnossen/home).

**[CSY]** S. Carmeli, T. M. Schlank, and L. Yanovski, _Ambidexterity and height_, Adv. Math., vol. 385, Paper No. 107763, 90, 2021. DOI: [10.1016/j.aim.2021.107763](https://doi.org/10.1016/j.aim.2021.107763), [arXiv:2007.13089](https://arxiv.org/abs/2007.13089).

**[F]** W. Fulton, _Introduction to toric varieties_, Annals of Mathematics Studies. Princeton University Press, Princeton, NJ, 1993, vol. 131, pp. xii+157, ISBN: 0-691-00049-2. DOI: [10.1515/9781400882526](https://doi.org/10.1515/9781400882526), The William H. Roever Lectures in Geometry.

**[FLTZ]** B.Fang, C.-C. M. Liu, D. Treumann, and E. Zaslow, _A categorification of Morelli's theorem_, Invent. Math., vol. 186, no.1, pp.79–114, 2011. DOI: [10.1007/s00222-011-0315-x](https://doi.org/10.1007/s00222-011-0315-x), [arXiv:1007.0053](https://arxiv.org/abs/1007.0053).

**[H]** M. Hoyois, _Algebraic geometry_, Lecture notes, available at [hoyois.app.uni-regensburg.de/WS26/alggeo1/script.pdf](https://hoyois.app.uni-regensburg.de/WS26/alggeo1/script.pdf).

**[HA]** J. Lurie, _Higher algebra_, Sep. 2017. Available at [math.ias.edu/~lurie/papers/HA.pdf](https://www.math.ias.edu/~lurie/papers/HA.pdf).

**[HM]** C. Heyer and L. Mann, $6$_-functor formalisms and smooth representations_, Oct. 2024, [arXiv:2410.13038](https://arxiv.org/abs/2410.13038).

**[HPT]** P. J. Haine, M. Porta, and J.-B. Teyssier, _The homotopy-invariance of constructible sheaves_, Homology Homotopy Appl., vol.25, no.2, pp. 97–128, 2023. DOI: [10.4310/hha.2023.v25.n2.a6](https://doi.org/10.4310/hha.2023.v25.n2.a6), [arXiv:2010.06473](https://arxiv.org/abs/2010.06473).

**[HSR]** P. J. Haine, J. Steinebrunner, and M. Ramzi, _Fully faithful functors and pushouts of ∞-categories_, Mar. 2025, [arXiv:2503.03916](https://arxiv.org/abs/2503.03916).

**[HTT]** J. Lurie, _Higher topos theory_, Annals of Mathematics Studies. Princeton, NJ: Princeton University Press, 2009, vol. 170, pp. xviii+925, ISBN:978-0-691-14049-0;0-691-14049-9. Available at [math.ias.edu/~lurie/papers/HTT.pdf](https://www.math.ias.edu/~lurie/papers/HTT.pdf).

**[K]** T. Kuwagaki, _The nonequivariant coherent-constructible correspondence for toric stacks_, Duke Math. J., vol. 169, no. 11, pp. 2125–2197, 2020. DOI: [10.1215/00127094-2020-0011](https://doi.org/10.1215/00127094-2020-0011), [arXiv:1610.03214](https://arxiv.org/abs/1610.03214).

**[Kerodon]** J. Lurie, _Kerodon_, [kerodon.net](https://kerodon.net/).

**[M]** R. Morelli, _The_ $\mathrm{K}$_-theory of a toric variety_, Adv. Math., vol. 100, no. 2, pp. 154–182, 1993. DOI: [10.1006/aima.1993.1032](https://doi.org/10.1006/aima.1993.1032).

**[R]** E. Riehl _Category theory in context_, Aurora Dover Modern Math Originals. Dover Publications, Inc., Mineola, NY, 2016, pp.xvii+240, ISBN: 978-0-486-80903-8;0-486-80903-X, Available at [emilyriehl.github.io/files/context.pdf](https://emilyriehl.github.io/files/context.pdf).

**[Rot]** J. Lurie, _Rotation invariance in algebraic $\mathrm{K}$-theory_, Sep. 2015. Available at [math.ias.edu/~lurie/papers/Waldhaus.pdf](https://www.math.ias.edu/~lurie/papers/Waldhaus.pdf).

**[V]** M. Volpe, _The six operations in topology_, J. Topol., vol. 18, no. 4, Paper No. e70050, 69 pp., 2025. DOI: [110.1112/topo.70050](https://doi.org/110.1112/topo.70050), [arXiv:2110.10212](https://arxiv.org/abs/2110.10212).

## Guidelines for typing up the lecture notes
Before your first time typing up notes, start by looking over the notes from Lectures 1 & 2 along with their LaTeX code.
Use both the writing style and code as models for how to type the notes for the lectures you're assigned. 
If you have any questions, math-related, LaTeX-related, or otherwise, please ask!

### General LaTeX guidelines
The goal is to format the code nicely and use the convenient hyperlinking that LaTeX provides.
+ Please write every sentence as a separate line of code.
  This makes things much easier to edit in the future.
+ Please use indentations when using environments.
+ Make reasonable labels for theorems, equations, etc. that you refer back to, using underscores to separate words. For example, `prop:compatibility_with_Fourier_transform`.

Below is a good example demonstrating the previous three points:
```
\begin{theorem}[(Fourier transform)]\label{thm:Fourier_transform}
  Let $ n \geq 1 $ be an integer.
  There is an equivalence of \categories
  \begin{equation*}
    \begin{tikzcd}[sep=3em]
      \FT \colon \QCoh(\Bup((\GGm)^{\cross n})) \arrow[r, "\sim"{yshift=-0.25em}] & \Sh(\ZZ^n;\Sp) = \Fun(\ZZ^n,\Sp) \period
    \end{tikzcd}
  \end{equation*}
  Here, on the right-hand sides we regard $ \ZZ^n $ as a discrete topological space and as a discrete category.
  Moreover, this equivalence is symmetric monoidal where the left-hand side is given the usual tensor product of quasicoherent sheaves and the right-hand side is given the convolution product.
\end{theorem}
```

+ When you refer back to theorems, equations, etc. use the [`cleveref`](https://ctan.org/pkg/cleveref?lang=en) package. That way, the environment name will be included and it will be hyperlinked properly. For example, you'd refer to the thorem with label `prop:compatibility_with_Fourier_transform` by typing `\Cref{prop:compatibility_with_Fourier_transform}`. Here is a good example of this:
```
One might notice that in order to make the Fourier tranform identification in \Cref{prop:compatibility_with_Fourier_transform}, we really need to choose an isomorphism $ T \equivalent (\GGm)^{\cross n} $.
```
So you don't need to write the word Proposition or anything—LaTeX takes care of it.

### Equations
Please don't use the old `$$ … $$` environment for out-of-line equations (see [here](https://tex.stackexchange.com/questions/503/why-is-preferable-to) for why). 
Instead, use the `equation*` or `equation` environments for single-line equations, and the `align*` or `align` environments for multi-line equations

### Macros
For symbols, etc. that are used a lot, please use [macros](https://en.wikibooks.org/wiki/LaTeX/Macros)! For example, instead of writing `\mathbf{R}` every time, just write `\RR`.
I already have a standard collection in place in `standard_macros.sty`.
You can look there for already existing things.
If you want to add a new macro, please feel free to do so, but add it to `document_macros.sty` (and not in the main document or  `standard_macros.sty`).

### Commutative diagrams
Use the [`tikzcd`](https://ctan.math.washington.edu/tex-archive/graphics/pgf/contrib/tikz-cd/tikz-cd-doc.pdf) package for diagrams. 
If you have trouble typing them, [quiver](https://q.uiver.app/) is a nice visual interface—you can just copy the code from there.

### Figures
Especially in the secion on toric geometry, there are a lot of hand-drawn figures in the lecture notes. 
Please include these in the typed notes by taking a screenshot and saving it as a `pdf` (LaTeX has issues with `jpeg` and other formats), adding the `pdf` to the `figures` folder, and then using the code
```
  \begin{figure}[!h]
        \centering
        \includegraphics[width=\linewidth]{figures/figure_name.jpeg}
        \caption{A caption}
        \label{fig:figure_label}
    \end{figure}
```
You can also modify the width of the figure to look nicer by replacing `width=\linewidth` by `width=0.6\linewidth` or however wide you want it to be.
Try to name the figures something indicative (and unique).

Ideally, I would like to make nice versions of all of the images in Adobe Illustrator (like I did for Lecture 2). 
If you also want to make some nice versions, let me know!
