# Setup Guide

## Step 1: Install Python

1. Go to [python.org](https://www.python.org/downloads/)
2. Download Python 3.8 or higher
3. Run the installer
4. ✅ **Important:** Check "Add Python to PATH"
5. Click "Install Now"

### Verify Installation

Open terminal/command prompt and type:
```bash
python --version
```

You should see: `Python 3.x.x`

---

## Step 2: Install Required Libraries

Open terminal/command prompt and run:

```bash
pip install jupyter pandas numpy matplotlib seaborn
```

This installs:
- **Jupyter** - Interactive notebooks
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Matplotlib** - Plotting
- **Seaborn** - Statistical visualization

---

## Step 3: Launch Jupyter Notebook

1. Open terminal/command prompt
2. Navigate to the course folder
3. Type:

```bash
jupyter notebook
```

4. Your browser will open to `http://localhost:8888`
5. Click on any `.ipynb` file to start coding!

---

## Step 4: Editor Setup (Optional)

### VS Code (Recommended)
1. Download from [code.visualstudio.com](https://code.visualstudio.com)
2. Install the "Python" extension
3. Open the course folder
4. Start coding!

### PyCharm
1. Download from [jetbrains.com/pycharm](https://www.jetbrains.com/pycharm/)
2. Choose Community Edition (free)
3. Open the course folder

---

## Troubleshooting

**Python not found?**
- Ensure you added Python to PATH during installation
- Restart your terminal after installing

**pip not working?**
- Try `pip3` instead of `pip`
- Or: `python -m pip install <package>`

**Jupyter not starting?**
- Make sure you're in the correct directory
- Try `python -m jupyter notebook`

---

## You're Ready! 🚀

Once everything is installed, head to **Module 1: Python Basics** to get started!
