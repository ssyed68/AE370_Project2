# AE370_Project2

## Overview
This repository contains code, data, and documentation for Project 2 in AE 370: “Mathematical and Numerical Modeling of a Dynamic‐Stall Initial–Boundary Value Problem (IBVP).” We implement and analyze a partitioned fluid–structure IBVP for a 2D pitch-and-plunge foil undergoing dynamic stall, using the Beddoes–Leishman unsteady‐aerodynamics model coupled to rigid‐body plunge–pitch equations.

## Problem Statement
We study the coupled unsteady aerodynamics and rigid‐body motion of a 2D foil subject to prescribed plunge and pitch excitations.  
- **Why it matters:** Dynamic stall underlies rotorcraft loads, wind‐turbine performance, and high‐angle‐of‐attack flight. Modeling this IBVP reveals how unsteady lift and moment histories interact with plunge–pitch kinematics.  
- **Key questions:**  
  1. How does temporal discretization (Newmark vs. explicit Euler) affect solution stability and accuracy?  
  2. How does spatial resolution (grid points $N$) influence convergence of attached-lift and vortex-lift state variables?

# Repository Structure

```plaintext
AE370-Project-2/
├── docs/            # LaTeX technical report and supporting documentation
├── code/            # Code documents with implementation
├── .gitignore       # Specifies files and directories to be ignored by Git
├── LICENSE          # Licensing information (MIT License)
├── README.md        # This file: Project overview, setup instructions, etc.
