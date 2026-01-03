# 🛢️ Reservoir Engineering Handbook (Python Edition)

**A Python implementation of the concepts, equations, and workflows found in "Reservoir Engineering Handbook" (5th Edition, 2019) by Tarek Ahmed.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 📖 Project Overview

This repository bridges the gap between classical reservoir engineering theory and modern data science. It translates the empirical correlations and analytical methods from Tarek Ahmed's textbook into reusable, vectorised Python code.

Each chapter is contained in a single Jupyter Notebook (`.ipynb`), complete with markdown explanations, latex equations, and interactive plots.

## 📂 Repository Structure

| Chapter | Notebook | Key Concepts Implemented |
| :--- | :--- | :--- |
| **01** | [Fluid Behavior](notebooks/01_fluid_behavior.ipynb) | Phase Diagrams (Black Oil vs Volatile Oil vs Retrograde Gas) |
| **02** | [Fluid Properties](notebooks/02_fluid_properties.ipynb) | Z-factor (DAK), Bubble Point (Vasquez-Beggs), Viscosity |
| **03** | [Lab Analysis (PVT)](notebooks/03_lab_analysis_pvt.ipynb) | QC & Smoothing of Lab Data using the **Y-Function** |
| **04** | [Rock Properties](notebooks/04_rock_properties.ipynb) | Permeability Averaging (Arithmetic, Harmonic, Geometric) |
| **05** | [Relative Permeability](notebooks/05_rel_perm.ipynb) | **Corey's Model** for Oil-Water Rel Perm Curves |
| **06** | [Fluid Flow Fundamentals](notebooks/06_fluid_flow_fundamentals.ipynb) | **Diffusivity Equation**, Ei-Function, Pressure Transients |
| **07** | [Oil Well Performance](notebooks/07_oil_well_performance.ipynb) | **IPR Curves** (Vogel & Fetkovich methods) |
| **08** | [Gas Well Performance](notebooks/08_gas_well_performance.ipynb) | Real Gas Pseudopressure **m(p)** Method |
| **09** | [Coning](notebooks/09_coning.ipynb) | Critical Rate Calculation (Meyer-Garder & Chaperon) |
| **10** | [Water Influx](notebooks/10_water_influx.ipynb) | **Van Everdingen-Hurst** (Unsteady State) & Carter-Tracy |
| **11** | [Material Balance (MBE)](notebooks/11_recovery_mech_mbe.ipynb) | **Havlena-Odeh** Straight Line Plot (OOIP estimation) |
| **12** | [Predicting Performance](notebooks/12_predicting_oil_performance.ipynb) | **Tarner Method** for Solution Gas Drive prediction |
| **13** | [Gas Reservoirs](notebooks/13_gas_reservoirs.ipynb) | **p/z Plot** for Gas in Place (G) estimation |
| **14** | [Waterflooding](notebooks/14_waterflooding.ipynb) | **Buckley-Leverett** & Welge Tangent for Breakthrough |
| **15** | [Vapor-Liquid Equilibria](notebooks/15_vapor_liquid_equilibria.ipynb) | **Flash Calculation** using Rachford-Rice & Wilson K-values |
| **16** | [Decline Curve Analysis](notebooks/16_decline_curves.ipynb) | Auto-fitting **Arps Hyperbolic** parameters using `scipy` |
| **17** | [Fractured Reservoirs](notebooks/17_fractured_reservoirs.ipynb) | **Warren & Root** Dual-Porosity Model ($\omega$ and $\lambda$) |
| **18** | [Unconventional RTA](notebooks/18_modern_dca_unconventional.ipynb) | **Material Balance Time** & Log-Log Diagnostic Plots |
| **Capstone** | [Phoenix Field Study](notebooks/capstone_phoenix_field_study.ipynb) | **Integrated FDP:** From PVT to OOIP to Forecasting |

## 🚀 Getting Started

### Prerequisites
You need Python installed. We recommend using [Anaconda](https://www.anaconda.com/) to manage environments.

### Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/adeanggins/reservoir-engineering-handbook.git](https://github.com/adeanggins/reservoir-engineering-handbook.git)
