# Homework 2

This is the template repository for Homework 2 for [BEE 6940, Climate Risk Analysis](https://viveks.me/climate-risk-analysis) at Cornell University, Spring 2023. The goal of this homework is to continue to calibrate a sea-level rise model and look at the impact of climate uncertainties on sea-level rise.

**If you are registered in the class, DO NOT CLONE THIS REPOSITORY.** Instead, use the GitHub Classroom link from Ed Discussion to create your own repository.

## Learning Objectives

After completing Homework 2, you should be able to:
  * load and work with tabular data (such as `.csv` files);
  * find best-fit estimates for parameters by optimizing;
  * propagate uncertainty through a model chain;
  * assess the relative impacts of parametric and scenario uncertainties.

## Repository Overview

The repository consists of the following files and folders:
- `hw2.ipynb`: Jupyter Notebook for the homework assignment. Students should create code or Markdown blocks as necessary to answer questions. **This is the only file you should need to edit.**
- `Project.toml`: Julia environment files. These should just work, but feel free to add other packages as needed using the `Pkg` package manager. **This is the only other file that you might end up making changes to, though you should do this using `Pkg`, not directly.**
- `hw2.jl`: Source file for Jupyter notebook generation. You shouldn't need to or want to touch this; everything is in the `.ipynb` file.
- `LICENSE`: This material is licensed using the MIT license. You can ignore this for working on the problem set.
- `README.md`: This file. You shouldn't need to touch this.
- `.gitignore`: This tells `git` what files to ignore. You shouldn't need to touch this.
- `data/`: folder containing data files corresponding to RCP forcings and emissions and historical global mean temperatures and sea-levels.
- `params/`: folder holding a file with `MimiSNEASY` calibrated parameters;
- `src/`: folder containing a file with auxiliary `MimiSNEASY` functions.