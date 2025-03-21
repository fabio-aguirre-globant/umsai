### 📝 What does this PR do?
<!-- Provide a clear and concise description of the changes in this PR -->
- [ ] Feature implementation
- [ ] Bug fix
- [ ] Refactoring
- [ ] Documentation update

### 📌 Why is this needed?
<!-- Explain why this PR is necessary and what issue it resolves -->

### 🛠️ How to test it?
```bash
# Clone the repository
git clone https://github.com/fabio-aguirre-globant/umsai.git
cd umsai

# Checkout to the branch
git checkout feature/new-functionality

# Run linters & formatters
pre-commit run --all-files

# Run unit tests
pytest tests/

# Run coverage report
pytest --cov=src --cov-report=html
