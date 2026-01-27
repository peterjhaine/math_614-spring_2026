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

**Time** 12:00pm–1:20pm on Mondays and Wednesdays

**Location** KAP 265 

**Office hour** Wednesdays at 2:00pm in KAP 248C (though we can adjust to a different time if this is inconvenient for people)

## Assignments/Grading

### Lecture notes
Shortly after every lecture, [below](#lecture-schedule--notes) I will post detailed handwritten notes for the lecture. The main work for this course will be to type up these notes in a class Overleaf/Git Repo. I'll likely edit them a bit after you type them.

I'll type the notes for the first two lectures. 
In the first week, we'll create a rotating schedule for typing up the notes. 
Here are the basic expectations:
+ You should finish typing the lecture notes by the lecture one week later.
  (So if you're typing up notes for Wednesday, 1/21, you should do so by Wednesday 1/28).
+ You should do a nice job of typing the notes, formatting them in a style consistent with the previous notes (using the first two lectures as an example), checking for typos, filling small gaps, and adding references when it makes sense.
+ Please try to format the LaTeX code nicely.
  This makes editing easier.

[Below](#guidelines-for-typing-up-the-lecture-notes) you can find detailed guidelines for typing up the notes.

### Final presentation
The second component of the course will be an in-class presentation on a topic related to the course, but outside of what we covered. It will be during the last weeks of class. More on this later.

### Grading scheme
50% typing up lecture notes + 50% final presentation.

## Lecture schedule & notes

+ [Overleaf for typed notes](https://www.overleaf.com/read/kpkwrssmtzrm#f9bb46) (viewable by anyone with the link)
+ [Git Repo for typed notes](https://github.com/peterjhaine/toric_mirror_symmetry_notes) (to get access, ask me)
+ Order that we'll cycle through for typing the notes (after the first two lectures): Baran, Jiayi, Michael, Yahya, Yash, Yijie.


| Date  | Lecture title | References | Scribe |
| :---  |    :----:      | :----      | :----      |
| 1/12   | Overview <br> [Notes](lecture_notes/01-12-2026.pdf), [Recording](https://youtu.be/Vln_P_1s9Fo)  |  [BH, [§1](https://arxiv.org/pdf/2501.06649#section.1)]          | Peter |
| 1/14   | Toric geometry I <br> [Notes](lecture_notes/01-14-2026.pdf), [Recording](https://youtu.be/MfMJuqZ23XA)    |  [F, Chapter 1]          | Peter |
| 1/21   | Toric geometry II <br> [Notes](lecture_notes/01-21-2026.pdf), [Recording](https://youtu.be/70ivBuZpZUs)    |  [F, Chapter 1]          | Baran   |
| 1/26   | Toric geometry III <br> [Notes](lecture_notes/01-26-2026.pdf)    |           | Jiayi   |
| 1/28   | Toric geometry IV     |           | Michael |
| 2/2    |      |           | Yahya   |
| 2/4    |      |           | Yash    |
| 2/9    |      |           | Yijie   |
| 2/11   |      |           | Baran   |
| 2/18   |      |           | Jiayi   |
| 2/23   |      |           | Michael |
| 2/25   |      |           | Yahya   |
| 3/2    |      |           | Yash    |
| 3/4    |      |           | Yijie   |
| 3/9    |      |           | Baran   |
| 3/11   |      |           | Jiayi   |
| 3/23   |      |           | Michael |
| 3/25   |      |           | Yahya   |
| 3/30   |      |           | Yash    |
| 4/1    |      |           | Yijie   |
| 4/6    |      |           | Baran   |
| 4/8    |      |           | Jiayi   |
| 4/13   |      |           | Michael |
| 4/15   |      |           | Yahya   |
| 4/20   |      |           | Yash    |
| 4/22   |      |           | Yijie   |
| 4/27   |  Probably final presentations    |           | N/A |
| 4/29   |  Probably final presentations    |           | N/A |

## References

**[BH]** Q. Bai and Y. Hu, _Toric mirror symmetry for homotopy theorists_, Jan.2025, [arXiv:2501.06649](https://arxiv.org/abs/2501.06649).

**[F]** W. Fulton, _Introduction to toric varieties_, Annals of Mathematics Studies. Princeton University Press, Princeton, NJ, 1993, vol. 131, pp. xii+157, ISBN: 0-691-00049-2. DOI: [10.1515/9781400882526](https://doi.org/10.1515/9781400882526), The William H. Roever Lectures in Geometry.

**[FLTZ]** B.Fang, C.-C. M. Liu, D. Treumann, and E. Zaslow, _A categorification of Morelli's theorem_, Invent. Math., vol. 186, no.1, pp.79–114, 2011. DOI: [10.1007/s00222-011-0315-x](https://doi.org/10.1007/s00222-011-0315-x), [arXiv:1007.0053](https://arxiv.org/abs/1007.0053).

**[K]** T. Kuwagaki, _The nonequivariant coherent-constructible correspondence for toric stacks_, Duke Math. J., vol. 169, no. 11, pp. 2125–2197, 2020. DOI: [10.1215/00127094-2020-0011](https://doi.org/10.1215/00127094-2020-0011), [arXiv:1610.03214](https://arxiv.org/abs/1610.03214).

**[M]** R. Morelli, _The_ $\mathrm{K}$_-theory of a toric variety_, Adv. Math., vol. 100, no. 2, pp. 154–182, 1993. DOI: [10.1006/aima.1993.1032](https://doi.org/10.1006/aima.1993.1032).

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
