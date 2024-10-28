# Genetic Algorithm for Recipe Generation

## Prerequisites

Before running the script, ensure that you have the following Python packages installed:

- `json`: For handling JSON files.
- `numpy`: For numerical operations and handling arrays.
- `geneticalgorithm`: A Python library for implementing genetic algorithms.
- `fractions`: For handling fractional ingredient quantities.

You can install the required packages using pip:

```bash
pip install numpy geneticalgorithm
```

Additionally, ensure you have a JSON file named `base.json` in the same directory as the script. This file should contain the knowledge base of recipes, structured with ingredients and steps.

## How to Run the Script

1. **Prepare the Knowledge Base**: Ensure you have a `base.json` file with the necessary recipe data. The file should be structured as a list of recipes, each containing `ingredients` and `steps`.

2. **Run the Script**: Execute main.ipynb:


3. **Output**: The script will output the best recipe found, listing the ingredients with their quantities in grams and the cooking steps in a logical order.

