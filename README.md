# Computational Physics in High Energy Physics

A comprehensive course repository for computational physics methods applied to modern high-energy physics research, featuring hands-on analysis with real Nobel Prize-winning datasets from LIGO gravitational-wave astronomy and LHC particle physics.

##  Overview

This repository contains the complete materials for a computational physics course focused on high-energy physics applications. The course bridges theoretical physics concepts with practical computational implementations using Python, Jupyter notebooks, and real experimental data. Students learn to analyze gravitational-wave signals from LIGO and particle physics data from the LHC, applying statistical methods to extract physics from noisy experimental data.

##  Learning Objectives

By working through these materials, you will:
- Master Jupyter notebooks for scientific computing and reproducible research
- Understand probability distributions and error propagation in experimental physics
- Implement data fitting techniques including linear/nonlinear regression and uncertainty quantification
- Learn confidence intervals, correlations, and matched filtering for signal detection
- Analyze real gravitational-wave data from LIGO open datasets
- Study jet physics in high-energy collisions and apply Bayesian statistics
- Conduct hypothesis testing using the Higgs boson discovery as a case study

##  Repository Structure

The course is organized into eight comprehensive chapters:

### **Chapter 1: Introduction and Jupyter Notebooks**
- Introduction to computational physics and Jupyter environment
- Python basics: NumPy arrays, Matplotlib visualization, functions
- Hands-on coding examples from basic arithmetic to matrix operations

### **Chapter 2: Probability, Distributions and Error Propagation**
- Basic probability concepts and statistical distributions
- Binomial, Poisson, and Gaussian distributions with simulations
- Error propagation techniques and Monte Carlo verification
- Central Limit Theorem demonstration

### **Chapter 3: Data Fitting and Uncertainty**
- Linear regression and analytical solutions
- Nonlinear curve fitting (exponential decay, Gaussian peaks)
- Goodness of fit and chi-square analysis
- Advanced examples with confidence intervals

### **Chapter 4: Confidence, Correlations, and Matched Filtering**
- Confidence intervals for parameters and regression
- Pearson correlation and Fisher transform
- Autocorrelation, power spectra, and Wiener-Khinchin theorem
- Matched filtering for signal detection (theory and implementation)

### **Chapter 5: Gravitational-Wave Data Analysis (LIGO Open Data)**
- Working with real LIGO gravitational-wave data
- Signal visualization and frequency analysis (FFT)
- Filtering and noise reduction techniques
- Practical analysis of astrophysical signals

### **Chapter 6: Jet Physics, Bayesian Statistics, and Likelihood**
- Jet formation in high-energy collisions
- Jet clustering algorithms (anti-kT) and observables
- Likelihood-based statistical inference in HEP
- Bayesian methods and Markov Chain Monte Carlo (MCMC)
- Applications to jet energy calibration and mass fits

### **Chapter 7: Hypothesis Testing I - Higgs Search Foundations**
- General structure of particle physics searches
- Invariant mass reconstruction (γγ and 4l channels)
- Signal and background modeling
- Profile likelihood ratio and Wilks' theorem
- Local significance computation

### **Chapter 8: Hypothesis Testing II - Advanced Statistical Methods**
- Local vs. global significance and Look-Elsewhere Effect
- Confidence levels and exclusion limits (CLs method)
- Asymptotic formulae vs. Monte Carlo approaches
- Statistical combination of multiple channels
- Higgs discovery combination methodology

## 🛠️ Prerequisites and Installation

### Required Skills
- Basic knowledge of Python programming
- Understanding of calculus and linear algebra
- Familiarity with fundamental physics concepts

### Python Environment Setup

1. **Install Python 3.8+** from [python.org](https://www.python.org/)

2. **Install required packages**:
```bash
pip install numpy scipy matplotlib jupyter notebook
pip install pandas sympy astropy corner emcee
```

3. **For gravitational-wave analysis** (Chapter 5):
```bash
pip install gwpy ligo.skymap
```

4. **For Bayesian statistics** (Chapter 6):
```bash
pip install pymc3 arviz
```

### Launching the Materials
```bash
# Clone the repository
git clone https://github.com/Hazem-74/Computational-Physics.git
cd Computational-Physics

# Start Jupyter Notebook
jupyter notebook

# Or use JupyterLab for enhanced features
jupyter lab
```

##  How to Use This Repository

### For Students
1. Start with Chapter 1 to set up your computational environment
2. Proceed sequentially through chapters, running all code examples
3. Complete the exercises at the end of each chapter
4. Apply techniques to the provided datasets or your own data

### For Enahancing
1. Use the structured chapters as weekly modules
2. Assign exercises for homework or in-class activities
3. Modify examples to suit specific course needs
4. Extend with additional datasets or analysis problems

### Self-Study Approach
- Follow the chapter sequence for systematic learning
- Experiment with modifying code parameters to deepen understanding
- Apply methods to your own research problems
- Join study groups to discuss challenging concepts

##  Key Features

### Real Experimental Data
- **LIGO Gravitational-Wave Data**: Analyze real signals from black hole mergers
- **LHC-inspired Datasets**: Work with Higgs boson search simulations
- **Open Science Principles**: Use publicly available experimental data

### Practical Code Examples
- Every concept includes executable Python code
- Gradual complexity progression from basics to advanced applications
- Emphasis on reproducible research practices

### Physics-Driven Learning
- Mathematical derivations alongside computational implementations
- Physical interpretation of statistical results
- Connection between theory, experiment, and computation

##  Applications in Modern Physics Research

The skills developed in this course directly apply to:
- Gravitational-wave astronomy data analysis
- High-energy physics experiments (ATLAS, CMS, LHCb)
- Astrophysical signal processing
- Statistical inference in experimental physics
- Computational modeling of physical systems

##  Exercises and Assessment

Each chapter includes:
- **Conceptual problems** testing theoretical understanding
- **Coding challenges** implementing computational methods
- **Data analysis tasks** applying techniques to real datasets
- **Extension problems** for advanced students

Solutions to selected problems are available to instructors upon request.

##  Contributing

This is an educational resource. Suggestions for improvements, additional examples, or corrections are welcome. Please:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request with clear documentation

##  License

Educational use - see specific licensing details in the repository.

##  Acknowledgments

- Prepared by Ahmed Ali Abdelalim, Fall 2025
- Based on materials developed for Zewail City computational physics courses
- Uses open data from LIGO Scientific Collaboration and inspired by LHC experiments
- Incorporates pedagogical approaches from modern physics education research

---
