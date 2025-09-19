# DSPy Extraction Working Notebooks

A collection of Jupyter notebooks and configuration files for medical data extraction using DSPy 3.0.3 framework, specifically focused on dental and medical research data processing.

## 📋 Project Overview

This repository contains working notebooks and optimized configurations for extracting structured dichotomous outcomes from medical research papers in markdown format. The project leverages DSPy 3.0.3 to create robust data extraction pipelines for dental and medical research applications.

## 📁 Repository Structure

### 🔧 Core Notebooks

- **`co_medical_extraction.ipynb`** - Main medical data extraction pipeline using DSPy 3.0.3
- **`do_medical_extraction.ipynb`** - Alternative medical extraction implementation
- **`do_medical_extraction_async.ipynb`** - Asynchronous version of medical extraction
- **`extraction_evalutor.ipynb`** - Evaluation framework for extraction performance
- **`test.ipynb`** - Testing and experimentation notebook

### ⚙️ Configuration Files

- **`optimized.json`** - Optimized DSPy model configuration with training examples
- **`optimized_qa.json`** - Question-answering specific optimizations
- **`state_only.json`** - State-only model configuration

### 🛡️ Project Files

- **`.gitignore`** - Git ignore rules (excludes `.env` files and sensitive data)
- **`README.md`** - This documentation file

## 🚀 Getting Started

### Prerequisites

- Python 3.11+
- Jupyter Notebook or JupyterLab
- DSPy 3.0.3

### Installation

```bash
# Install required dependencies
pip install dspy-ai==3.0.3 openai pandas numpy scikit-learn matplotlib seaborn sentence-transformers
```

### Usage

1. **Start with the main extraction notebook:**

   ```bash
   jupyter notebook co_medical_extraction.ipynb
   ```

2. **For asynchronous processing:**

   ```bash
   jupyter notebook do_medical_extraction_async.ipynb
   ```

3. **To evaluate extraction performance:**

   ```bash
   jupyter notebook extraction_evalutor.ipynb
   ```

## 🎯 Key Features

- **Medical Data Extraction**: Extract structured dichotomous outcomes from medical research papers
- **DSPy 3.0.3 Integration**: Leverages the latest DSPy framework capabilities
- **Optimized Configurations**: Pre-configured models for various extraction tasks
- **Asynchronous Processing**: Support for high-throughput data processing
- **Evaluation Framework**: Built-in tools to assess extraction accuracy and performance

## 📊 Data Processing Pipeline

1. **Input**: Medical research papers in markdown format
2. **Processing**: DSPy-powered extraction of structured data
3. **Output**: Structured dichotomous outcomes in JSON format
4. **Evaluation**: Performance metrics and quality assessment

## 🔧 Configuration Files

### optimized.json

Contains optimized DSPy model parameters with training examples for mathematical reasoning and problem-solving tasks.

### optimized_qa.json

Specialized configuration for question-answering scenarios in medical data extraction.

### state_only.json

Lightweight configuration focusing on state management and core extraction functionality.

## 🏥 Medical Domain Focus

This project is specifically designed for:

- Dental research data extraction
- Medical paper analysis
- Clinical outcome extraction
- Structured data generation from unstructured medical texts

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-extraction-method`)
3. Commit your changes (`git commit -am 'Add new extraction method'`)
4. Push to the branch (`git push origin feature/new-extraction-method`)
5. Open a Pull Request

## 📄 License

This project is part of the Penn Dental research initiative. Please contact the repository maintainers for licensing information.

## 📞 Support

For questions, issues, or collaboration opportunities, please:

- Open an issue in this repository
- Contact the Penn Dental research team
- Review the notebook documentation for implementation details

## 🔄 Version History

- **Current**: DSPy 3.0.3 integration with optimized medical extraction
- Focus on dental and medical research applications
- Asynchronous processing capabilities
- Comprehensive evaluation framework

---

*Part of the Penn Dental research initiative for advancing medical data extraction and analysis.*



