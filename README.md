# MEC4131Z Energy Systems Modelling Environment

This repository contains the environment setup for the MEC4131Z energy systems modelling course, including tools for simulation, analysis, and visualization using PyPSA and related Python libraries.

---

## 📦 Environment Overview

The environment includes:

- `Python 3.12`
- `PyPSA` with Excel support
- `NumPy`, `Pandas`, `Plotly`, `Matplotlib`
- `HiGHS` solver
- JupyterLab and IPyWidgets
- Excel I/O via `openpyxl` and `pypsa[excel]`

---

## 🛠️ Installation Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### 2. Create the Conda Environment

```bash
conda env create -f mec4131z_env.yml
```

Or, if the environment already exists and you want to update it:

```bash
conda env update -f mec4131z_env.yml --prune
```

### 3. Activate the Environment

```bash
conda activate mec4131z-env
```

---

## 🧪 Testing the Setup

Run JupyterLab:

```bash
jupyter lab
```

Then try importing the core packages in a notebook:

```python
import pypsa
import pandas as pd
import plotly
```

---

## 💡 Notes

- The environment installs `pypsa[excel]` via pip to enable Excel file I/O.
- If you encounter solver issues, ensure that `highs` is available and correctly linked.

---

## 📄 License

This repository is shared under the MIT License. See the LICENSE file for more details.

