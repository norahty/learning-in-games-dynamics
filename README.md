# Geometric Structure of No-Regret Learning Dynamics

This repository contains the report and presentation slides for a research project studying the **trajectory-level behavior of no-regret learning algorithms in repeated games**.

The project focuses on understanding *how* learning dynamics evolve over time—not just whether time-averaged regret converges—and on identifying **algorithm-specific geometric structure** in the evolution of joint action distributions.

---

## Overview

Classical guarantees in online learning ensure low regret in repeated play, but they often say little about the **last-iterate behavior** of learning algorithms. In many games, standard no-regret dynamics do not converge pointwise and instead exhibit persistent cycling.

This project adopts a **geometric and dynamical perspective** on learning in games. Rather than analyzing time averages, it tracks the evolution of the **joint distribution over actions** and studies these trajectories using probability-respecting geometric embeddings. This reveals stable and reproducible structures—such as circular or polygonal orbits—that are characteristic of different learning rules.

---

## Contents

- `CIS_6200_Final_Report_NH.pdf/`  
  Final written report describing the motivation, methodology, experiments, and findings.

- `CIS_6200_Learning_In_Games_Presentation.pdf/`  
  Presentation slides used for research presentations and interviews.

---

## Main Findings

- Different no-regret learning algorithms exhibit **distinct and reproducible geometric trajectories** in repeated games.
- Multiplicative-update methods tend to produce smooth, circular or annular orbits.
- Projected gradient methods produce polygonal trajectories with sharp turning points.
- These structures are not visible under standard Euclidean embeddings or time-averaged analysis.
- Simple geometric diagnostics (e.g., radius stability and angular structure) help characterize learning behavior beyond regret bounds.

Overall, the results suggest that **learning rules encode structural information about the game in their trajectories**, even when classical convergence guarantees do not apply.

---

## Code and Demos

The simulation and analysis code used to generate the results is **not publicly released in this repository**.

A clean and reproducible version of the codebase, along with demos, is available **upon request for research and academic use**.

---

## Status and Future Work

This project is exploratory and foundational in nature. Possible directions for future work include:

- Formal characterization of trajectory geometry across broader classes of games
- Connections between geometric structure and exploitability or predictability
- Extensions to additional learning rules and interaction models

The work may be further developed into a workshop or theory-oriented publication.

---

## Contact

For questions, discussion, or requests for access to code and demos, please contact:

**Nora Han**  
norahty@seas.upenn.edu

---

## Citation

If you reference this work, please cite the accompanying report or contact the author for an updated citation.
