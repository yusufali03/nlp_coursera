# Autocomplete Language Model

A pure-Python, NumPy-powered implementation of an n-gram language model for next-word prediction (autocomplete). This project demonstrates the theory and math behind language modeling—unigrams, bigrams, trigrams, smoothing, probability estimation, perplexity calculation, and word suggestion—using only Python and NumPy.

---

## Table of Contents

- [Features](#features)  
- [Getting Started](#getting-started)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Core Modules & Functions](#core-modules--functions)  
- [Examples](#examples)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features

- **Data Preprocessing**  
  - Tokenization  
  - Rare-word replacement (`<unk>`)
- **n-Gram Counting**  
  - Unigram, bigram, trigram extraction with start/end tokens  
- **Probability Estimation**  
  - Add-k (Laplace) smoothing  
- **Perplexity Calculation**  
  - Evaluate model fit on held-out data  
- **Autocomplete Suggestion**  
  - Suggest next word given a context  
  - Optional prefix filtering  
- **Pure NumPy & Python**  
  - No external ML libraries—just math, data structures, and NumPy for numeric ops  

---

## Getting Started

These instructions will help you run the notebook locally.

### Prerequisites

- Python 3.7+  
- NumPy 1.18+  

---

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/autocomplete-language-model.git
   cd autocomplete-language-model
