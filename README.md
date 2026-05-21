# Independent Component Analysis: Mathematical Derivation
A clean, step-by-step mathematical derivation of ICA for blind source separation, built from first principles.

## What's Covered
- The cocktail party problem and Blind Source Separation (BSS)
- Mixing model: observed signals as x = A·s, where A ∈ ℝⁿˣᵐ
- Unmixing model: recovering sources via y = Wᵀx
- Central Limit Theorem and why mixtures tend toward Gaussianity
- Measures of Non-Gaussianity: Kurtosis and Negentropy
- Preprocessing: centering and PCA whitening (VPCA = D^(-½)Eᵀ)
- FastICA algorithm: fixed-point iteration and convergence

## Files
| File | Description |
|------|-------------|
| `Independent_Component_Analysis_notes_by_me.pdf` | Compiled, readable document |
| `Independent_Component_Analysis_notes_by_me.tex` | LaTeX source file |
| `Cocktail_Party_Problem.png` | Figure used in the Mixing Model section |
| `Mixtures_Become_More_Gaussian.png` | Figure illustrating the Central Limit Theorem |

## How to Compile
Open the `.tex` file in any LaTeX editor (Overleaf, TeXShop, VS Code with LaTeX Workshop) and compile with `pdflatex`.

## Prerequisites
Basic knowledge of:
- Linear algebra (vectors, matrices, eigenvalues, orthogonality)
- Probability and statistics (distributions, expectation, variance)
- Calculus (partial derivatives, optimization)
