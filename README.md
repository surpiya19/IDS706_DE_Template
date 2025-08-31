# IDS706_DE_Template
![Build Status](https://github.com/surpiya19/IDS706_DE_Template/actions/workflows/main.yml/badge.svg?branch=main)

A **starter template for any project**.  

This repo sets up a Python project with:
- Automated installs via **Makefile**
- **Linting** for clean code
- **Dockerfile** for containerization
- **GitHub Actions** for CI/CD

---

## Quick Start  

```bash
# Clone the repo
git clone https://github.com/surpiya19/IDS706_DE_Template.git
cd IDS706_DE_Template

# Install dependencies
make install

# Run the app
python main.py

# Run tests
make test

# Lint the code
make lint
```
---

## Functions

### `say_hello`

**Purpose:**  
Provides a greeting to students in the IDS class.

**Usage:**
```python
from hello import say_hello

message = say_hello("Annie")
print(message)
# Output: Hello, Annie, welcome to Data Engineering Systems (IDS 706)!



