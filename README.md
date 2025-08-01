# CFNT5B-CP: Conservative Framework for Non-Trivial 5-Band Composite Perturbation

## Overview

The CFNT5B-CP (Core-Fibonacci-Number Theoretic-5 Banded-Complex Perturbations) operator framework achieves what previous attempts could not: simultaneous spectral accuracy and authentic random matrix statistics. This repository contains the complete implementation, data, and documentation for reproducing all results from our paper.

**Paper**: [010930
010930August_The_CFNT5B_CP_Operator_Empirical_Investigation.pdf](010930August_The_CFNT5B_CP_Operator_Empirical_Investigation.pdf) *(Draft Version - August 2025)*

## Repository Contents

### 📁 Code
- [`16JulyPublicationRefactor.ipynb`](16JulyPublicationRefactor.ipynb) - Complete computational framework with 14 analysis cells:
  - Cell A: Baseline matrix construction demonstration
  - Cell B: Perturbation framework (6+ hour runtime - pre-computed data provided)
  - Cell #1: **Conservative hybrid analysis (RUN THIS FIRST)**
  - Cells #2-12: Analysis modules generating all figures and results

### 📊 Data Files
- **Zeta Zeros**: 
  - `combined_zeros_1.txt` (10M zeros available, first 30K used in experiments)
  
- **Unperturbed Eigenvalues**: 
  - `eigenvals_N5000_comprehensive_20250609_150741.txt` (5K scale)
  - `eigenvals_N10000_comprehensive_20250609_151458.txt` (10K scale)
  - `eigenvals_N15000_comprehensive_20250609_153652.txt` (15K scale)
  - `eigenvals_N20000_comprehensive_20250609_162546.txt` (20K scale)
  - `eigenvals_N25000_N25K_comprehensive_20250609_185007.txt` (25K scale)
  
- **Perturbed Eigenvalues**:
  - `perturbed_eigenvals_5K_strength3.2.txt` (5K scale, strength 3.2)
  - `perturbed_eigenvals_10K_strength5.4.txt` (10K scale, strength 5.4)
  - `perturbed_eigenvals_15K_strength9.6.txt` (15K scale, strength 9.6)
  - `perturbed_eigenvals_20K_strength12.8.txt` (20K scale, strength 12.8)
  - `perturbed_eigenvals_25K_strength14.0.txt` (25K scale, strength 14.0)

## Quick Start

1. **Clone this repository**:
   ```bash
   git clone https://github.com/JohnNDvorak/CFNT5B-CP-Analysis.git
   cd CFNT5B-CP-Analysis
