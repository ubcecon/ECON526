# ECON526 - Fall 2025

This is a MA-level course in quantitative economics, data science, and causal inference in economics.


This course will have a combination of coding, theory, and development of mathematical background.  All coding is done in Python.


# Course materials
All materials will be on github, and canvas will be used to submit assignments/communication.

Course notes:
  - [Link to Jesse's Lecture Slides](https://jlperla.github.io/grad_econ_datascience/)
  - [Paul's HTML Slides](https://ubcecon.github.io/ECON526/lectures/paul/), [source](https://github.com/ubcecon/526)

There is no assigned physical textbook, but we will be using lecture notes from:
- [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)
- [QuantEcon Python and Data Science Lectures](https://quantecon.org/projects/#filter=lecture)

# Computing Environment

See [here](https://jlperla.github.io/grad_econ_datascience/pages/setup.html#quick-start) for instructions.  All course code will be done in python

- Get a [GitHub](www.github.com) ID and apply for the [Student Developer Pack](https://education.github.com/pack) to get further free features
- We strongly recommend using [VS Code](https://code.visualstudio.com/) as your primary code editor and [uv](https://github.com/astral-sh/uv) for your python and package management.
- After setup you can clone a variety of repositories onto your local machine using a terminal, using either git directly (e.g. in terminal go `git clone https://github.com/ubcecon/ECON526.git`), or [VS Code (recommended)](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#_clone-a-repository-locally).  See instructions and more other useful code repositories [here](https://jlperla.github.io/grad_econ_datascience/pages/setup.html#other-notebook-repositories)
    

## Syllabus
See [Syllabus](syllabus.md) for more details

## Problem Sets and Exams

The course has one midterm, weekly to bi-weekly problem sets, and a final data project due the last day of class.

1. **September 8th Midnight:** [Problem Set 0](problem_sets/problem_set_0.pdf) - covers Math Camp material, so you can get started right away.
2. **September 14th Midnight:** [Problem Set 1](problem_sets/problem_set_1.ipynb) - short assigment checking your installation of Jupyter.
3. **October 2 (LAB SESSION):** Midterm Logistics Practice <!-- and Review [Midterm Practice Problems](problem_sets/midterm_practice_1.ipynb) -->
4. **October 8:** IN CLASS MIDTERM
5. **End of Term (TBD):** Data Project Due

See the `/problem_sets` folder within this repository for the problem sets as jupyter notebooks.
- The `pyproject.toml` and `uv.lock` files provide the package setup.  Simple run `uv sync` (more details [here](https://jlperla.github.io/grad_econ_datascience/pages/setup.html))
- Problem Set 0 can be done on paper and scanned, but other problem sets must be submitted as `.ipynb` and exported `html` files.  See instructions [here](https://jlperla.github.io/grad_econ_datascience/pages/canvas_assignments.html)

## Lectures
The course is structured into two parts:

### Jesse

- **September 3**: [Linear Algebra Foundations](https://jlperla.github.io/grad_econ_datascience/slides/linear_algebra_foundations.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/linear_algebra_foundations.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/linear_algebra_foundations.html#extra-materials)

- **September 8**: [Linear Algebra Foundations](https://jlperla.github.io/grad_econ_datascience/slides/linear_algebra_foundations.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/linear_algebra_foundations.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/linear_algebra_foundations.html#extra-materials)

- **September 10**: [Least Squares, Uniqueness, and Regularization](https://jlperla.github.io/grad_econ_datascience/slides/least_squares.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/least_squares.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/least_squares.html#extra-materials)

- **September 15**: [Applications of Linear Algebra and Eigenvalues](https://jlperla.github.io/grad_econ_datascience/slides/eigenvalue_applications.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/eigenvalue_applications.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/eigenvalue_applications.html#extra-materials)

- **September 17**: [Latent Variables and Unsupervised Learning](https://jlperla.github.io/grad_econ_datascience/slides/latent_variables.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/latent_variables.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/latent_variables.html#extra-materials)

- **September 22**: [Latent Variables and Unsupervised Learning](https://jlperla.github.io/grad_econ_datascience/slides/latent_variables.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/latent_variables.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/latent_variables.html#extra-materials)
- **September 24**: [Linear and Nonlinear Dynamics](https://jlperla.github.io/grad_econ_datascience/slides/dynamics.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/dynamics.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/dynamics.html#extra-materials)
- **September 29**:  [Probability, Conditioning, and Independence](https://jlperla.github.io/grad_econ_datascience/slides/probability.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/probability.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/probability.html#extra-materials)
- **October 1**: [Probability, Conditioning, and Independence](https://jlperla.github.io/grad_econ_datascience/slides/probability.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/probability.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/probability.html#extra-materials)
-  **October 6**: [Stochastic Processes, Markov Chains, and Expectations](https://jlperla.github.io/grad_econ_datascience/slides/stochastic_processes.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/stochastic_processes.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/stochastic_processes.html#extra-materials)
-  **October 8 (IN CLASS MIDTERM)**
-  **October 13 (Statutory holiday)**
-  **October 15**: [Stochastic Processes, Markov Chains, and Expectations](https://jlperla.github.io/grad_econ_datascience/slides/stochastic_processes.html), [PDF](https://jlperla.github.io/grad_econ_datascience/slides/stochastic_processes.pdf), and [Extra and Self Study Materials](https://jlperla.github.io/grad_econ_datascience/slides/stochastic_processes.html#extra-materials)

<!-- More classes
- October 20
- October 22
- October 27
- October 29
- November 3
- November 5
- READING WEEK
- November 17
- November 18
- November 24
- November 26
- December 1
- December 3

-->
### Paul

[Go here](https://ubcecon.github.io/ECON526/lectures/paul/) for a list of topics, reading, and slides.

Here is the [source](https://github.com/ubcecon/526) for my slides.

See "Sources and Futher Reading" (2nd last slide) on each set of slides for additional reading.

#### Important Dates

<!-- - **October 23** [Introduction to Causality](https://ubcecon.github.io/ECON526/paul/causality_intro.html) -->

<!-- - **October 28** [Uncertainty Quantification](https://ubcecon.github.io/ECON526/paul/uncertainty.html) -->

<!-- - **October 30** [Causal Graphs](https://ubcecon.github.io/ECON526/paul/causal_graphs.html) -->

<!-- - **November 4** Regression -->
<!--     - **Material:** -->
<!--       - https://matheusfacure.github.io/python-causality-handbook/05-The-Unreasonable-Effectiveness-of-Linear-Regression.html -->
<!--       - https://matheusfacure.github.io/python-causality-handbook/06-Grouped-and-Dummy-Regression.html -->
<!--       - https://matheusfacure.github.io/python-causality-handbook/07-Beyond-Confounders.html -->

<!-- -  **November 6**: [Matching](https://ubcecon.github.io/ECON526/paul/matching.html) -->

-  **November 11 (Midterm Break)**
-  **November 13 (Midterm Break)**
<!-- -  **November 18**: Predictive Models -->
<!--     - https://matheusfacure.github.io/python-causality-handbook/17-Predictive-Models-101.html -->
<!--     - https://datascience.quantecon.org/tools/regression.html -->

<!-- -  **November 20** Instrumental Variables -->
<!--     - **Material:** -->
<!--       - https://matheusfacure.github.io/python-causality-handbook/08-Instrumental-Variables.html -->
<!--       - https://matheusfacure.github.io/python-causality-handbook/09-Non-Compliance-and-LATE.html -->
<!-- -  **November 25**:  [Difference in Differences](https://ubcecon.github.io/ECON526/paul/did.html) -->
<!--     - https://matheusfacure.github.io/python-causality-handbook/13-Difference-in-Differences.html -->
<!-- -  **November 27**: [Panel Data and Fixed Effects](https://ubcecon.github.io/ECON526/paul/fe.html), [The Difference in Differences Saga](https://ubcecon.github.io/ECON526/paul/moredid.html) -->
<!--     - https://matheusfacure.github.io/python-causality-handbook/14-Panel-Data-and-Fixed-Effects.html -->
<!--     - https://matheusfacure.github.io/python-causality-handbook/24-The-Diff-in-Diff-Saga.html -->
<!-- -  **December 2nd**: [Synthetic Control](https://ubcecon.github.io/ECON526/paul/syntheticcontrol.html) -->
<!--     - https://matheusfacure.github.io/python-causality-handbook/15-Synthetic-Control.html -->
<!--     - https://matheusfacure.github.io/python-causality-handbook/25-Synthetic-Diff-in-Diff.html -->
<!-- -  **December 4th**: [Debiased Machine Learning](https://ubcecon.github.io/ECON526/paul/doubleml.html) -->
<!--     - https://datascience.quantecon.org/applications/ml_in_economics.html#estimation-of-nuisance-functions -->
<!-- - **time-permitting**: [Treatment Heterogeneity and Conditional Effects](https://ubcecon.github.io/ECON526/paul/conditionaleffect.html) -->
<!--     - https://datascience.quantecon.org/applications/heterogeneity.html -->
<!-- - **time-permitting**: [Neural Networks](https://ubcecon.github.io/ECON526/paul/neuralnets.html) -->
<!--    - Reading: [QuantEcon Datascience: Regression - Neural Networks](https://datascience.quantecon.org/tools/regression.html#neural-networks) -->
- **December 15**
    - **PROJECT DUE**
