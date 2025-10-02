# IPL Auction Prediction

IPL Player Auction Price Prediction using Machine Learning

## Project Overview

This project uses machine learning techniques to predict IPL (Indian Premier League) player auction prices based on various player statistics and features.

## Documentation

This project includes automated documentation generation and deployment using GitHub Actions.

### Documentation Workflow

The documentation is automatically built and deployed to GitHub Pages when changes are pushed to the `main` branch.

The workflow:
1. Checks out the code
2. Sets up Python environment
3. Installs dependencies from `requirements.txt`
4. Generates documentation using Doxygen
5. Deploys the generated documentation to GitHub Pages

### Building Documentation Locally

#### Using Doxygen

To build the documentation locally using Doxygen:

```bash
# Install Doxygen
sudo apt-get install doxygen  # On Ubuntu/Debian
# or
brew install doxygen  # On macOS

# Generate documentation
doxygen Doxyfile

# View the documentation
# Open html/index.html in your browser
```

#### Using Sphinx (Alternative)

If you prefer to use Sphinx for Python documentation:

```bash
# Install dependencies
pip install -r requirements.txt

# Initialize Sphinx (first time only)
sphinx-quickstart docs

# Build documentation
cd docs
make html

# View the documentation
# Open _build/html/index.html in your browser
```

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

For documentation generation:
- Doxygen (for Doxygen-based documentation)
- Sphinx >= 7.0.0 (for Sphinx-based documentation)
- sphinx-rtd-theme >= 2.0.0

See `requirements.txt` for complete list of dependencies.

## Usage

1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook IPL.ipynb
   ```

## Contributing

Contributions are welcome! Please ensure your code is well-documented and includes appropriate tests.

## License

This project is open source and available under the MIT License.
