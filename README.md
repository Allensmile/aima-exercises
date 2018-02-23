# `aima-exercises`

Exercises for the book *Artificial Intelligence: A Modern Approach.* The idea is that in the fourth edition of the book, exercises will be online only (they will not appear in the book). This site will showcase the exercises, and will be a platform for students and teachers to add new exercises.

The first step will be to translate the LaTeX exercises (in the [`latex`](https://github.com/aimacode/aima-exercises/tree/master/latex) subdirectory) into markdown. Note that in the files there, the use of the `\begin{uexercise}` and `\begin{iexercise}` macros. Those are for the US and International versions of the book, which are slightly different. For this online version, we will present all the exercises to all the users. Macros are defined in the [`aima3e.sty`](https://github.com/aimacode/aima-exercises/blob/master/latex/aima3e.sty) file and figures (pictures/diagrams) are in the [`figures`](https://github.com/aimacode/aima-exercises/tree/master/latex/figures) directory.

# Index of Files

Here is a table of the latex and markdown version of the exercise files for *Artificial Intelligence: A Modern Approach,* with their respository location. Unimplemented files and the *future exercises* file are a good place for new contributors to start.

| **Chapter** | **LaTex File** | **Status** | **Jupyter Notebook**| **Markdown** |
|:------------|:---------------|:-----------|:-----------------|:-----------------|
| 1-Introduction| [`intro-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/intro-exercises.tex) | Implemented | [`intro-exercises.ipynb`](Jupyter%20notebook/intro-exercises.ipynb)|
| 2-Intelligent-Agents| [`agents-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/agents-exercises.tex) | Implemented | [`agents-exercises.ipynb`](Jupyter%20notebook/agents-exercises.ipynb)| [`agents-exercises.md`](markdown/agents-exercises.md)|
| 3-Solving-Problems-By-Searching| [`search-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/search-exercises.tex) | Implemented | [`search-exercises.ipynb`](Jupyter%20notebook/search-exercises.ipynb)| [`search-exercises.md`](markdown/search-exercises.md)|
| 4-Beyond-Classical-Search| [`advanced-search-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/advanced-search-exercises.tex) | Implemented | [`advanced-search-exercises.ipynb`](Jupyter%20notebook/advanced-search-exercises.ipynb)|[`advanced-search-exercises.md`](markdown/advanced-search-exercises.md)|
| 5-Adversarial-Search | [`game-playing-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/game-playing-exercises.tex) | Implemented | [`game-playing-exercises.ipynb`](Jupyter%20notebook/game-playing-exercises.ipynb)|[`game-playing-exercises.md`](markdown/game-playing-exercises.md)|
| 6-Constraint-Satisfaction-Problems | [`csp-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/csp-exercises.tex) | Implemented | [`csp-exercises.ipynb`](Jupyter%20notebook/csp-exercises.ipynb)|[`csp-exercises.md`](markdown/csp-exercises.md)|
| 7-Logical-Agents | [`knowledge+logic-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/knowledge%2Blogic-exercises.tex) | Implemented | [`knowledge+logic-exercises.ipynb`](Jupyter%20notebook/knowledge+logic-exercises.ipynb)|[`knowledge-logic-exercises.md`](markdown/knowledge-logic-exercises.md)|
| 8-First-Order-Logic | [`fol-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/fol-exercises.tex) | Implemented | [`fol-exercises.ipynb`](Jupyter%20notebook/fol-exercises.ipynb)|[`fol-exercises.md`](markdown/fol-exercises.md)|
| 9-Inference-In-First-Order-Logic | [`logical-inference-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/logical-inference-exercises.tex) | Implemented | [`logical-inference-exercises.ipynb`](Jupyter%20notebook/logical-inference-exercises.ipynb)|[`logical-inference-exercises.md`](markdown/logical-inference-exercises.md)|
| 10-Classical-Planning | [`planning-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/planning-exercises.tex) | Implemented | [`planning-exercises.ipynb`](Jupyter%20notebook/planning-exercises.ipynb)|[`planning-exercises.md`](markdown/planning-exercises.md)|
| 11-Planning-And-Acting-In-The-Real-World | [`advanced-planning-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/advanced-planning-exercises.tex) | Implemented | [`advanced-planning-exercises.ipynb`](Jupyter%20notebook/advanced-planning-exercises.ipynb)|[`advanced-planning-exercises.md`](markdown/advanced-planning-exercises.md)|
| 12-Knowledge-Representation | [`kr-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/kr-exercises.tex) | Implemented | [`kr-exercises.ipynb`](Jupyter%20notebook/kr-exercises.ipynb)|[`kr-exercises.md`](markdown/kr-exercises.md)|
| 13-Quantifying-Uncertainity | [`probability-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/probability-exercises.tex) | Implemented | [`probability-exercises.ipynb`](Jupyter%20notebook/probability-exercises.ipynb)|[`probability-exercises.md`](markdown/probability-exercises.md)|
| 14-Probabilistic-Reasoning | [`bayes-nets-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/bayes-nets-exercises.tex) | Implemented | [`bayes-nets-exercises.ipynb`](Jupyter%20notebook/bayes-nets-exercises.ipynb)|[`bayes-nets-exercises.md`](markdown/bayes-nets-exercises.md)|
| 15-Probabilistic-Reasoning-Over-Time | [`dbn-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/dbn-exercises.tex) | Implemented | [`dbn-exercises.ipynb`](Jupyter%20notebook/dbn-exercises.ipynb)|[`dbn-exercises.md`](markdown/dbn-exercises.md)|
| 16-Making-Simple-Decisions | [`decision-theory-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/decision-theory-exercises.tex) | Implemented | [`decision-theory-exercises.ipynb`](Jupyter%20notebook/decision-theory-exercises.ipynb)|[`decision-theory-exercises.md`](markdown/decision-theory-exercises.md)|
| 17-Making-Complex-Decisions| [`complex-decisions-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/complex-decisions-exercises.tex) | Implemented | [`complex-decisions-exercises.ipynb`](Jupyter%20notebook/complex-decisions-exercises.ipynb)|[`complex-decisions-exercises.md`](markdown/complex-decisions-exercises.md)|
| 18-Learning-From-Examples | [`concept-learning-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/concept-learning-exercises.tex) | Implemented | [`concept-learning-exercises.ipynb`](Jupyter%20notebook/concept-learning-exercises.ipynb)|[`concept-learning-exercises.md`](markdown/concept-learning-exercises.md)|
| 19-Knowledge-In-Learning | [`ilp-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/ilp-exercises.tex) | Implemented | [`ilp-exercises.ipynb`](Jupyter%20notebook/ilp-exercises.ipynb)|[`ilp-exercises.md`](markdown/ilp-exercises.md)|
| 20-Learning-Probabilistic-Models | [`bayesian-learning-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/bayesian-learning-exercises.tex) | Implemented | [`bayesian-learning-exercises.ipynb`](Jupyter%20notebook/bayesian-learning-exercises.ipynb)|[`bayesian-learning-exercises.md`](markdown/bayesian-learning-exercises.md)|
| 21-Reinforcement-Learning | [`reinforcement-learning-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/reinforcement-learning-exercises.tex) | Implemented | [`reinforcement-learning-exercises.ipynb`](Jupyter%20notebook/reinforcement-learning-exercises.ipynb)|[`reinforcement-learning-exercises.md`](markdown/reinforcement-learning-exercises.md)|
| 22-Natural-Language-Processing | [`nlp-communicating-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/nlp-communicating-exercises.tex) | Implemented | [`nlp-communicating-exercises.ipynb`](Jupyter%20notebook/nlp-communicating-exercises.ipynb)|[`nlp-communicating-exercises.md`](markdown/nlp-communicating-exercises.md)|
| 23-Natural-Language-For-Communication | [`nlp-english-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/nlp-english-exercises.tex) | Implemented | [`nlp-english-exercises.ipynb`](Jupyter%20notebook/nlp-english-exercises.ipynb)|[`nlp-english-exercises.md`](markdown/nlp-english-exercises.md)|
| 24-Perception | [`perception-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/perception-exercises.tex) | Implemented | [`perception-exercises.ipynb`](Jupyter%20notebook/perception-exercises.ipynb)|[`perception-exercises.md`](markdown/perception-exercises.md)|
| 25-Robotics | [`robotics-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/robotics-exercises.tex) | Implemented | [`robotics-exercises.ipynb`](Jupyter%20notebook/robotics-exercises.ipynb)|[`robotics-exercises.md`](markdown/robotics-exercises.md)|
| 26-Philosophical-Foundations | [`philosophy-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/philosophy-exercises.tex) | Implemented | [`philosophy-exercises.ipynb`](Jupyter%20notebook/philosophy-exercises.ipynb)|[`philosophy-exercises.md`](markdown/philosophy-exercises.md)|
| 27-AI-The-Present-And-Future |  |  | |
| Future Exercises | [`future-exercises.tex`](https://github.com/aimacode/aima-exercises/blob/master/latex/future-exercises.tex)| Implemented | [`future-exercises.ipynb`](Jupyter%20notebook/future-exercises.ipynb)|[`future-exercises.md`](markdown/future-exercises.md)|
