# VPPC 2024 Tutorial: Optimization of Electric Bus Charging

This repository contains the materials for the tutorial presented at the **2024 IEEE Vehicle Power and Propulsion Conference (VPPC)**. The tutorial covers optimization techniques applied to electric bus charging, with practical examples using **Pyomo** and a developed model.

## Overview

The tutorial is divided into two main parts:

1. **Introduction to Optimization for Electric Bus Charging**: 
   - Theoretical foundations of optimization techniques.
   - Key considerations for electric bus fleet operations, including charging schedules, battery degradation, energy consumption uncertainty, and time-of-use (TOU) tariffs.
   - Brief overview of Vehicle-to-Grid (V2G) interactions.
   
2. **Hands-On Programming with Pyomo**:
   - Step-by-step guide to building an optimization model for electric bus charging using Pyomo.
   - Implementation of constraints and objectives relevant to electric fleet management.
   - Execution of numerical experiments using real-world datasets.

## Prerequisites

To follow along with the tutorial, you will need the following:

- Python 3.8 or later
- Pyomo 6.0 or later
- A solver such as GLPK or CPLEX (instructions for installing solvers are provided below)
- Jupyter Notebook (recommended for interactive coding)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/jmanzolli/VPPC-2024-Tutorial.git
   cd VPPC-2024-Tutorial
   ```

2. Set up a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. Install a solver such as GLPK or CPLEX. For example, to install GLPK:

   - On Ubuntu:

     ```bash
     sudo apt-get install glpk-utils
     ```

   - On MacOS:

     ```bash
     brew install glpk
     ```

   - On Windows, follow [these instructions](https://www.gnu.org/software/glpk/).

## Tutorial Content

The repository includes the following:

- `notebooks/`: Jupyter notebooks used in the tutorial with step-by-step instructions and code examples.
- `data/`: Example datasets for testing and running the optimization models.
- `models/`: Pyomo models for electric bus charging optimization.
- `slides/`: PDF of the tutorial presentation slides.

### Notebooks

- **1_Introduction_to_Optimization.ipynb**: Overview of optimization concepts in the context of electric bus charging.
- **2_Building_a_Pyomo_Model.ipynb**: Step-by-step guide to building an optimization model using Pyomo.
- **3_Advanced_Topics_V2G_and_Battery_Degradation.ipynb**: Advanced topics, including V2G technology and battery ageing considerations.

## Usage

To run the notebooks, launch Jupyter:

```bash
jupyter notebook
```

Then open the notebooks in the `notebooks/` directory and follow along with the tutorial.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or further information, feel free to reach out via email or open an issue in this repository.

---

Let me know if you'd like to make any adjustments!
