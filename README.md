
# Pfda-Assignments Repository
**by: Phumi Tshidi (phumitshidi@gmail.com)**

<img src="https://blog.enterprisedna.co/wp-content/uploads/2023/06/jase888_a_photo_of_a_panda_bear_programming_on_a_computer_moder_d6cde95e-4b74-40ed-be3b-98a3964a2537.png" width="700" height="400">

## Key Sections

- **Overview:** Summary of the notebooks.
- **Contents:** Describes the assignments and their purposes.
- **Requirements:** Lists dependencies required to run the notebook.
- **Usage Instructions:** Explains what the notebook does and how to interact with it.
- **Running the Jupyter Notebook:** Provides instructions for running the notebook using both Anaconda, Visual  Studio Code or Google Colab.
- **Conclusion**: Provides the reader with the outcome.

## Overview

This repository contains a collection of Jupyter notebooks that cover a variety of data analysis topics. Below is a brief description of each notebook, along with instructions on how to set up your environment and run the notebooks using Anaconda and Visual Studio Code.

## Contents

1. **Weather.ipynb**: This notebook visualizes temperature over time. The dataset contains temperature data, and the notebook generates a line plot to show the temperature trends over a specific period.

2. **Pie.ipynb**: This notebook creates a pie chart representing the distribution of people's email domains.

3. **Risk.ipynb**: This notebook simulates 1,000 individual battle rounds in the Risk board game, where 3 attackers face off against 2 defenders. The results are visualized using various plots to analyze the outcomes and probabilities.

4. **Weatherdata.ipynb**: This notebook focuses on analyzing weather data for Knock Airport. The analysis includes temperature and wind speed over a given period.

## Requirements

To run these notebooks, ensure that you have the following tools and dependencies installed:

- [**Anaconda**:](https://www.anaconda.com/products/distribution) A Python distribution that includes Jupyter Notebooks and a wide array of scientific libraries.

- [**Visual Studio Code**:](https://code.visualstudio.com/) A code editor that can be configured with Jupyter extensions to run notebooks interactively.

## Dependencies
The notebooks use several Python libraries, including:

- pandas
- matplotlib
- seaborn
- numpy
- jupyter

## Running the Notebooks in Visual Studio Code

[**1. Install Visual Studio Code:**](https://code.visualstudio.com/) Download and install Visual Studio Code if you don't have it already.

**2. Install Python and Jupyter Extensions:** Install the Python extension and the Jupyter extension for Visual Studio Code. These can be found in the Extensions Marketplace within VS Code.

**3. Open the Repository:** Open the pfda_assignments repository folder in Visual Studio Code.

**4. Select the Python Interpreter:** In the Command Palette (Ctrl+Shift+P), type "Python: Select Interpreter" and select the Conda environment you created earlier or your default Python environment.

**5. Run the Notebook:** You can now open any of the .ipynb files and run them interactively inside Visual Studio Code.

### Installing Anaconda

1. Download and install [Anaconda](https://www.anaconda.com/products/distribution) for your operating system.
2. During installation, make sure to add Anaconda to your system path.

### Running the Notebooks in Anaconda

**1. Create a Conda Environment** (Optional but recommended):
   Open Anaconda Prompt or your terminal and run the following commands:

   ```bash
   conda create -n pfda_assignments python=3.9
   conda activate pfda_assignments
   ```

**2. Install Required Libraries:** The following libraries are required to run the notebooks:

```bash
conda install jupyter matplotlib pandas
```

**3. Launch Jupyter Notebook:** Navigate to your project directory in the terminal and start Jupyter Notebook by running:

```bash
jupyter notebook
```

This will open the Jupyter Notebook interface in your default browser, where you can select and run the individual notebooks.

## Conclusion

Overall, the repository effectively combines data visualization, statistical analysis, and simulation to offer valuable insights into weather, user behavior, and game mechanics, showcasing the power of Jupyter notebooks for exploratory data analysis and simulation tasks.
