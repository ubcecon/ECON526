# ECON526 - Fall 2024

This is a MA-level course in quantitative economics, data science, and causal inference in economics.


This course will have a combination of coding, theory, and development of mathematical background.  All coding is done in Python.
[Link to Jesse's Lecture Slides](https://ubcecon.github.io/ECON526/lectures/index.html) and [Paul's HTML Slides](https://ubcecon.github.io/ECON526/paul/), [source](https://github.com/ubcecon/526)


# Course materials
- Get a [GitHub](www.github.com) ID and apply for the [Student Developer Pack](https://education.github.com/pack) to get further free features
- Consider clicking `Watch` at the top of this repository to see file changes

All materials will be on github, and canvas will be used to submit assignments/communication.

There is no assigned physical textbook, but we will be using lecture notes from:
- [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)
- [QuantEcon Python and Data Science Lectures](https://quantecon.org/projects/#filter=lecture)

# Computing Environment
While you can use the [UBC JupyterOpen](https://open.jupyter.ubc.ca/) for this course, we strongly suggest installing Python on your local machine.  The easiest way to do this is:
- Install [Anaconda](https://www.anaconda.com/download) to install python and its packages for your operating system
- Install [git](https://git-scm.com/downloads) for your operating system
- Optionally: install (a) [Github Desktop](https://desktop.github.com/); (b) [VS Code](https://code.visualstudio.com/) to make it easier to manage downloaded notebooks.
- Then clone the following repositories onto your local machine using a terminal, using either git directly (e.g. in terminal go `git clone https://github.com/ubcecon/ECON526.git`), [GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop), or [VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_clone-a-repository-locally)
    - https://github.com/ubcecon/ECON526
    - https://github.com/QuantEcon/lecture-python-intro.notebooks
    - https://github.com/QuantEcon/lecture-python.notebooks
    - https://github.com/QuantEcon/lecture-datascience.notebooks
    - In some cases you will need to manually install packages (by doing `pip install -r requirements.txt` within some of those repositories, or manually installing packages as required)

We recommend using [VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_clone-a-repository-locally) to access repositories since you will likely begin using the VSCode editor as your primary Python (and latex) editor sooner than later.

## Syllabus
See [Syllabus](syllabus.md) for more details

## Problem Sets and Exams

The course has one midterm, weekly to bi-weekly problem sets, and a final data project due the last day of class.

1. **September 8th Midnight:** [Problem Set 1](problem_sets/problem_set_1.ipynb)
2. **September 18th Midnight:** [Problem Set 2](problem_sets/problem_set_2.ipynb)
3. **September 25th Midnight:** [Problem Set 3](problem_sets/problem_set_3.ipynb)
4. **October 6th Midnight:** [Problem Set 4](problem_sets/problem_set_4.ipynb)
5. **October 16th:** Midterm Logistics Practice and Review [Midterm Practice Problems](problem_sets/midterm_practice_1.ipynb)
6. **October 21st:** IN CLASS MIDTERM
7. **December 15th Midnight:** Data Project Due

See the `/problem_sets` folder within this repository for the problem sets as jupyter notebooks.  You should modify them directly as Jupyter notebooks, and the TA will explain how to submit them.

## Lectures
This year the course will be taught in two parts where the later parts of the course will follow material in [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html).

This lecture begins assuming you have completed the math/programming bootcamp for our masters students, or had an existing python-based programming course.  To refresh your knowledge, see basics in [QuantEcon Data Science Lectures](https://datascience.quantecon.org/) or [QuantEcon Python Programming for Economics and Finance](https://python-programming.quantecon.org/intro.html).

Slides for the lectures can be found [here](https://ubcecon.github.io/ECON526/lectures/index.html) and after his section starts: [Paul's HTML Slides](https://ubcecon.github.io/ECON526/paul/), [source](https://github.com/ubcecon/526)

### Jesse

- **September 4**: Introduction to Numerical Linear Algebra and its Applications in Data Science
   - **Topics:** Overview of computational complexity and numerical precision, solving systems of equations, geometric interpretations of linear algebra, matrix decompositions, linear least squares, and eigenvalues and eigenvectors.  Preparation for applications.
   - **Material:**
     - [Linear Algebra Foundations](https://ubcecon.github.io/ECON526/lectures/lectures/linear_algebra_foundations.html), [Jupyter](lectures/lectures/linear_algebra_foundations.ipynb), [PDF](lectures/lectures/linear_algebra_foundations.pdf)
   - **Self-study:**
     - Basics of linear algebra, matrices, norms, and linear independence: https://python.quantecon.org/linear_algebra.html
     - Numerical optimization: https://datascience.quantecon.org/scientific/optimization.html
     - Systems of Equations: https://python.quantecon.org/linear_algebra.html#solving-systems-of-equations
     - Eigenvectors and eigenvalues: https://python.quantecon.org/linear_algebra.html#eigenvalues-and-eigenvectors
     - Downloading and manipulating data in Python: https://intro.quantecon.org/long_run_growth.html and https://intro.quantecon.org/business_cycle.html
   - **(Optional) Extra Material**:
     - Introductory material on linear algebra: https://intro.quantecon.org/linear_equations.html and https://datascience.quantecon.org/scientific/applied_linalg.html
     - Matrix decompositions and other topics: https://python.quantecon.org/linear_algebra.html#further-topics

- **September 9**: Continuing on Introduction to Numerical Linear Algebra
   - **Topics:** Overview of computational complexity and numerical precision, solving systems of equations, geometric interpretations of linear algebra, matrix decompositions, linear least squares, and eigenvalues and eigenvectors.  Preparation for applications.
   - **Material:**
     - [Linear Algebra Foundations](https://ubcecon.github.io/ECON526/lectures/lectures/linear_algebra_foundations.html), [Jupyter](lectures/lectures/linear_algebra_foundations.ipynb), [PDF](lectures/lectures/linear_algebra_foundations.pdf)
   - **Self-study:**
     - Basics of linear algebra, matrices, norms, and linear independence: https://python.quantecon.org/linear_algebra.html
     - Numerical optimization: https://datascience.quantecon.org/scientific/optimization.html
     - Systems of Equations: https://python.quantecon.org/linear_algebra.html#solving-systems-of-equations
     - Eigenvectors and eigenvalues: https://python.quantecon.org/linear_algebra.html#eigenvalues-and-eigenvectors
     - Downloading and manipulating data in Python: https://intro.quantecon.org/long_run_growth.html and https://intro.quantecon.org/business_cycle.html
   - **(Optional) Extra Material**:
     - Introductory material on linear algebra: https://intro.quantecon.org/linear_equations.html and https://datascience.quantecon.org/scientific/applied_linalg.html
     - Matrix decompositions and other topics: https://python.quantecon.org/linear_algebra.html#further-topics

- **September 11**: Applications of Linear Algebra (Eigenvalues and Discounting)
   - **Topics:** Geometric series and present values, difference equations, steady states, and convergence, unemployment dynamics, present discounted values
   - **Material:**
     - Finishing off [Linear Algebra Foundations](https://ubcecon.github.io/ECON526/lectures/lectures/linear_algebra_foundations.html)
     - [Eigenvalues and Stability](https://ubcecon.github.io/ECON526/lectures/lectures/eigenvalue_applications.html), [Jupyter](lectures/lectures/eigenvalue_applications.ipynb), [PDF](lectures/lectures/eigenvalue_applications.pdf)
   - **Self-study:**
     - Geometric Series and Present Values: https://intro.quantecon.org/geom_series.html#example-interest-rates-and-present-values
     - Portfolio example: https://datascience.quantecon.org/scientific/applied_linalg.html#portfolios
     - Unemployment Dynamics example: https://datascience.quantecon.org/scientific/applied_linalg.html#unemployment-dynamics
   - **(Optional) Extra Material**:
     - Supply and Demand: https://intro.quantecon.org/intro_supply_demand.html
     - More on Competitive Equilibrium: https://intro.quantecon.org/supply_demand_multiple_goods.html

- **September 16**: Latent Variables and Intro to Unsupervised Learning
   - **Topics:** Review eigenvalues and dynamics, principle components, and present discounted values
   - **Material:**
     -  [Latent Variables and Unsupervised Learning](https://ubcecon.github.io/ECON526/lectures/lectures/latent_variables.html), [Jupyter](lectures/lectures/latent_variables.ipynb), [PDF](lectures/lectures/latent_variables.pdf)
   - **Self-study:**
     - [scikit-learn PCA docs](https://scikit-learn.org/stable/modules/decomposition.html#principal-component-analysis-pca)
     - [seaborn tutorials](https://seaborn.pydata.org/tutorial/introduction.html)

- **September 18**: More on Latent Variables and Clustering
   - **Topics:** Finish off continuous latent variables, PCA, auto-encoders, clustering, and started dynamics
   - **Material:**
     - [Latent Variables and Unsupervised Learning](https://ubcecon.github.io/ECON526/lectures/lectures/latent_variables.html)
   - **Self-study:**
     - [scikit-learn k-means docs](https://scikit-learn.org/stable/modules/clustering.html#k-means)
- **September 23**: Dynamics
   - **Topics:** Dynamical systems, stability, fixed points, linearization, intro to the Solow-Swan growth model
   - **Material:**
     - [Linear and Nonlinear Dynamics](https://ubcecon.github.io/ECON526/lectures/lectures/dynamics.html), [Jupyter](lectures/lectures/dynamics.ipynb), [PDF](lectures/lectures/dynamics.pdf)
   - **Self-study:**
     - Solow-Swan Growth Model Derivation: https://intro.quantecon.org/solow.html (skip 20.3)
     - Nonlinear Dynamics and Stability: https://intro.quantecon.org/scalar_dynam.html
     - Review [taylor series](https://en.wikipedia.org/wiki/Linearization#Multivariable_functions), just to first order
   - **(Optional) Extra Material**:
     - More on the Solow Model and Python: https://python-programming.quantecon.org/python_oop.html#example-the-solow-growth-model

- **September 25**: Finished Dynamics and Started Probability, Randomness, and Independence
   - **Topics:** Axioms of probability, LLN and CLT, and Conditional Independence
   - **Material:**
     - [Probability, Conditioning, and Independence](https://ubcecon.github.io/ECON526/lectures/lectures/probability.html), [Jupyter](lectures/lectures/probability.ipynb), [PDF](lectures/lectures/probability.pdf)
   - **Self-study:**
     - https://datascience.quantecon.org/scientific/randomness.html
     - https://intro.quantecon.org/prob_dist.html
   - **(Optional) Extra Material**:
     - https://python.quantecon.org/lln_clt.html
     - https://python.quantecon.org/prob_meaning.html
     - https://python.quantecon.org/prob_matrix.html

-  **September 30 (Statutory holiday)**

- **October 2nd**: Continue Probability, Randomness, and Independence
   - **Topics:** Axioms of probability, LLN and CLT, and Conditional Independence
   - **Material:**
     - [Probability, Conditioning, and Independence](https://ubcecon.github.io/ECON526/lectures/lectures/probability.html), [Jupyter](lectures/lectures/probability.ipynb), [PDF](lectures/lectures/probability.pdf)
   - **Self-study:**
     - https://datascience.quantecon.org/scientific/randomness.html
     - https://intro.quantecon.org/prob_dist.html
   - **(Optional) Extra Material**:
     - https://python.quantecon.org/lln_clt.html
     - https://python.quantecon.org/prob_meaning.html
     - https://python.quantecon.org/prob_matrix.html


-  **October 7**: Stochastic Processes and Forecasts
   - **Topics:** Conditional expectations, Bayes' rule, Law of Iterated Expectations, stochastic processes
    - **Material:**
      - Finish [Probability, Conditioning, and Independence](https://ubcecon.github.io/ECON526/lectures/lectures/probability.html)
      - [Stochastic Processes](https://ubcecon.github.io/ECON526/lectures/lectures/stochastic_processes.html), [Jupyter](lectures/lectures/stochastic_processes.ipynb), [PDF](lectures/lectures/stochastic_processes.pdf)
   - **(Optional) Extra Material**:
     - https://python.quantecon.org/finite_markov.html for more on Markov Chains
     - https://python.quantecon.org/ar1_processes.html for more on AR(1) processes
     - https://datascience.quantecon.org/scientific/randomness.html#loan-states for a simple Markov Chain example


-  **October 9**: Markov Chains and Maybe Start Causality
   - **Topics:** Finish stochastic processes and Markov Chains and briefly setup causality and counterfactuals if time permits
   - **Material:**
     - Finish [Stochastic Processes](https://ubcecon.github.io/ECON526/lectures/lectures/stochastic_processes.html)
      - [Introduction to Causality and Randomized Experiments](https://ubcecon.github.io/ECON526/lectures/lectures/introduction_to_causality.html)
   - **Self-Study:**
     - https://matheusfacure.github.io/python-causality-handbook/01-Introduction-To-Causality.html


-  **October 14 (Statutory holiday)**
<!-- 
-  **October 16** Stats Review: Quantifying Uncertainty in Causal Inference + Midterm Logistics Review
    - **Material:**
      - [Stats Review: Quantifying Uncertainty in Applied Economics](https://ubcecon.github.io/ECON526/lectures/lectures/uncertainty_bias_variance.html)
    - **Self-study:**
      - https://matheusfacure.github.io/python-causality-handbook/03-Stats-Review-The-Most-Dangerous-Equation.html
-->

-   **October 16** Introduction to Causality and Counterfactuals + Midterm Logistics Review
    - **Material:**
      - [Introduction to Causality and Randomized Experiments](https://ubcecon.github.io/ECON526/lectures/lectures/introduction_to_causality.html)
    - **Self-study:**
      - https://matheusfacure.github.io/python-causality-handbook/01-Introduction-To-Causality.html
      - https://matheusfacure.github.io/python-causality-handbook/02-Randomised-Experiments.html
       
-  **October 21 (IN CLASS MIDTERM)**

### Paul

[HTML Slides](https://ubcecon.github.io/ECON526/paul/), [source](https://github.com/ubcecon/526)

-   **October 23** Uncertainty Quantification II
    - **Material:**
      - Finish [Stats Review: Quantifying Uncertainty in Applied Economics](https://ubcecon.github.io/ECON526/lectures/lectures/uncertainty_bias_variance.html)

-   **October 28** Causal Graphical Models
    - **Material:**
      - [Causal Graphical Models](https://ubcecon.github.io/ECON526/lectures/lectures/causal_graphical_models.html#/title-slide)
      - https://matheusfacure.github.io/python-causality-handbook/04-Graphical-Causal-Models.html
    - **Self-study:**
      - https://theeffectbook.net/ch-DrawingCausalDiagrams.html

-   **October 30** Regression, Confounders
    - **Material:**
      - https://matheusfacure.github.io/python-causality-handbook/05-The-Unreasonable-Effectiveness-of-Linear-Regression.html
      - https://matheusfacure.github.io/python-causality-handbook/06-Grouped-and-Dummy-Regression.html
      - https://matheusfacure.github.io/python-causality-handbook/07-Beyond-Confounders.html

-   **November 4** Instrumental Variables, Noncompliance, LATE
    - **Material:**
      - https://matheusfacure.github.io/python-causality-handbook/08-Instrumental-Variables.html
      - https://matheusfacure.github.io/python-causality-handbook/09-Non-Compliance-and-LATE.html

-   **November 6**: Matching
    - **Material:**
      - https://matheusfacure.github.io/python-causality-handbook/10-Matching.html
      - https://matheusfacure.github.io/python-causality-handbook/11-Propensity-Score.html

-  **November 11 (Midterm Break)**
-  **November 13 (Midterm Break)**
-  **November 18**: [Matching](https://ubcecon.github.io/ECON526/paul/matching.html)
-  **November 20**: Predictive Models
    - https://matheusfacure.github.io/python-causality-handbook/17-Predictive-Models-101.html
    - https://datascience.quantecon.org/tools/regression.html
-  **November 25**:  Finish [Matching](https://ubcecon.github.io/ECON526/paul/matching.html), start [Difference in Differences](https://ubcecon.github.io/ECON526/paul/did.html)
    - https://matheusfacure.github.io/python-causality-handbook/13-Difference-in-Differences.html
-  **November 27**: [Panel Data and Fixed Effects](https://ubcecon.github.io/ECON526/paul/fe.html), [The Difference in Differences Saga](https://ubcecon.github.io/ECON526/paul/moredid.html)
    - https://matheusfacure.github.io/python-causality-handbook/14-Panel-Data-and-Fixed-Effects.html
    - https://matheusfacure.github.io/python-causality-handbook/24-The-Diff-in-Diff-Saga.html
-  **December 2nd**: [Synthetic Control](https://ubcecon.github.io/ECON526/paul/syntheticcontrol.html)
    - https://matheusfacure.github.io/python-causality-handbook/15-Synthetic-Control.html
    - https://matheusfacure.github.io/python-causality-handbook/25-Synthetic-Diff-in-Diff.html
-  **December 4th**: [Debiased/Orthogonal Machine Learning](https://ubcecon.github.io/ECON526/paul/doubleml.html)
    - https://datascience.quantecon.org/applications/ml_in_economics.html#estimation-of-nuisance-functions
- **time-permitting**: [Treatment Heterogeneity and Conditional Effects](https://ubcecon.github.io/ECON526/paul/conditionaleffect.html)
    - https://datascience.quantecon.org/applications/heterogeneity.html
- **time-permitting**: 8. [Neural Networks](https://ubcecon.github.io/ECON526/paul/neuralnets.html)
   - Reading: [QuantEcon Datascience: Regression - Neural Networks](https://datascience.quantecon.org/tools/regression.html#neural-networks)
- **December 15**
    - **PROJECT DUE**
