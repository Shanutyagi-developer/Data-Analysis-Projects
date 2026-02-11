# Data Analysis Projects

A collection of data analysis projects demonstrating the use of Python for extracting insights and creating visualizations using popular libraries like pandas, numpy, matplotlib, plotly, and seaborn.

## 📋 Table of Contents

- [About](#about)
- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About

This repository includes projects that showcase the usage of Python in finding insights using various data analysis and visualization libraries. Each project demonstrates different aspects of data analysis, from data cleaning and preprocessing to advanced visualization techniques.

## 📊 Projects

### 1. E-commerce Sales Analysis
Analysis of e-commerce sales data to uncover trends, patterns, and actionable insights for business decision-making.

**Key Features:**
- Sales performance analysis
- Customer behavior patterns
- Product category insights
- Time-series trends
- Revenue optimization strategies

### 2. Zomato Data Analysis
Comprehensive analysis of Zomato restaurant data to explore dining trends, customer preferences, and restaurant performance metrics.

**Key Features:**
- Restaurant ratings and reviews analysis
- Cuisine type distribution
- Location-based insights
- Price range analysis
- Popular dining trends

## 🛠️ Technologies Used

- **Python 3.8+**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Static visualizations
- **seaborn** - Statistical data visualization
- **plotly** - Interactive visualizations
- **Jupyter Notebook** - Interactive development environment

## 💻 Installation

### Prerequisites

Ensure you have Python 3.8 or higher installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Step 1: Clone the Repository

```bash
git clone https://github.com/Shanutyagi-developer/Data-Analysis-Projects.git
cd Data-Analysis-Projects
```

### Step 2: Create a Virtual Environment (Recommended)

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, install the libraries manually:

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

## 🚀 How to Use

### Method 1: Using Jupyter Notebook (Recommended)

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Navigate to the project folder:**
   - Open your browser (Jupyter should open automatically at `http://localhost:8888`)
   - Choose either:
     - `E-commerce sales analysis` folder
     - `Zomato Data Analysis` folder

3. **Open and run the analysis notebook:**
   
   **For E-commerce Analysis:**
   - Click on `E-Commerce Analysis using Python.ipynb`
   - Uses the `Sample - Superstore.csv` dataset
   
   **For Zomato Analysis:**
   - Click on `Zomato Data Analysis.ipynb`
   - Uses the `Zomato_data.csv` dataset
   
   - Run cells sequentially by pressing `Shift + Enter`
   - Or run all cells: `Cell → Run All`

### Method 2: Quick Start Commands

```bash
# Clone the repository
git clone https://github.com/Shanutyagi-developer/Data-Analysis-Projects.git

# Navigate to project directory
cd Data-Analysis-Projects

# Install required libraries
pip install pandas numpy matplotlib seaborn plotly jupyter

# Launch Jupyter Notebook
jupyter notebook

# Navigate to desired project folder and open the .ipynb file
```

### Method 3: Using JupyterLab (Alternative)

```bash
pip install jupyterlab
jupyter lab
```

Then navigate to:
- `E-commerce sales analysis/E-Commerce Analysis using Python.ipynb`, or
- `Zomato Data Analysis/Zomato Data Analysis.ipynb`

## 📁 Project Structure

```
Data-Analysis-Projects/
│
├── E-commerce sales analysis/
│   ├── E-Commerce Analysis using Python.ipynb    # Main analysis notebook
│   └── Sample - Superstore.csv                   # E-commerce dataset
│
├── Zomato Data Analysis/
│   ├── Zomato Data Analysis.ipynb                # Zomato analysis notebook
│   └── Zomato_data.csv                           # Zomato dataset
│
├── LICENSE                                       # MIT License
└── README.md                                     # Main documentation (this file)
```

## 📦 Requirements

Create a `requirements.txt` file with the following content:

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
plotly>=5.0.0
jupyter>=1.0.0
notebook>=6.4.0
openpyxl>=3.0.0
xlrd>=2.0.0
```

## 🔧 Common Issues and Solutions

### Issue: ModuleNotFoundError

**Solution:** Make sure all required libraries are installed:
```bash
pip install pandas numpy matplotlib seaborn plotly
```

### Issue: Jupyter Notebook not opening

**Solution:** 
```bash
pip install --upgrade jupyter notebook
jupyter notebook --generate-config
```

### Issue: Permission errors on Windows

**Solution:** Run command prompt as Administrator

### Issue: Kernel errors in Jupyter

**Solution:** 
```bash
python -m ipykernel install --user
```

## 📊 Working with Data

### Dataset Information

This repository contains two main datasets:

1. **Sample - Superstore.csv** - Located in `E-commerce sales analysis` folder
2. **Zomato_data.csv** - Located in `Zomato Data Analysis` folder

### Loading the Datasets

**E-commerce Data:**
```python
import pandas as pd

# Load the Superstore dataset
df = pd.read_csv('Sample - Superstore.csv')

# Display first few rows
print(df.head())

# Get basic information
print(df.info())
```

**Zomato Data:**
```python
import pandas as pd

# Load the Zomato dataset
df = pd.read_csv('Zomato_data.csv')

# Display first few rows
print(df.head())

# Statistical summary
print(df.describe())
```

### Typical Dataset Structures

**Superstore Dataset includes:**
- Order ID, Order Date
- Customer information
- Product details (Category, Sub-Category)
- Sales, Quantity, Profit
- Region, State, City
- Shipping details

**Zomato Dataset includes:**
- Restaurant names and IDs
- Location and address
- Cuisines offered
- Average cost for two
- Ratings and votes
- Online ordering and table booking availability

## 🤝 Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Shanutyagi-developer**

- GitHub: [@Shanutyagi-developer](https://github.com/Shanutyagi-developer)
- Repository: [Data-Analysis-Projects](https://github.com/Shanutyagi-developer/Data-Analysis-Projects)

## 🌟 Show Your Support

If you find this project helpful, please consider giving it a ⭐ on GitHub!

## 📚 Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Plotly Documentation](https://plotly.com/python/)
- [NumPy Documentation](https://numpy.org/doc/)

## 🔄 Updates

- **Latest Update:** February 2026
- **Status:** Active Development
- **Version:** 1.0.0

---

**Happy Analyzing! 📊✨**
