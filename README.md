# Titanic Survival Story: 6 Publication-Quality Visualizations

> Extended EDA with professional visualizations telling the story of who survived the Titanic and why

![Titanic](https://img.shields.io/badge/dataset-Titanic-blue)
![Python](https://img.shields.io/badge/python-3.9+-green)
![Visualizations](https://img.shields.io/badge/visualizations-6-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## 📋 Overview

This project extends the lesson-1 Titanic EDA by creating **6 publication-quality visualizations** that tell a compelling survival story. Each chart is professionally designed with clear titles, labelled axes, appropriate colors, and a one-sentence takeaway.

**The Story**: Who survived the Titanic and why? The visualizations reveal how gender, class, age, family size, and their interactions determined survival.

## 🎯 What This Project Does

- **Extends Lesson-1**: Builds upon the cleaned dataset from the first assignment
- **6 Publication-Quality Charts**: Professional visualizations ready for reports or presentations
- **Clear Storytelling**: Each chart has a one-line takeaway explaining its significance
- **Written Summary**: 200-word executive summary of findings
- **Reproducible**: Runs end-to-end with the same data cleaning as lesson-1

## 📊 The 6 Visualizations

| # | Chart Title | Key Finding |
|---|-------------|-------------|
| 1 | **Titanic Survival Distribution** | Only 38.4% survived - 549 lives lost |
| 2 | **Gender Disparity in Survival** | Women: 74.2% vs Men: 18.9% (4x difference) |
| 3 | **Survival by Passenger Class** | First: 62.9% vs Third: 24.2% (3x difference) |
| 4 | **Age Distribution with Survival** | Children under 12 had highest survival |
| 5 | **Impact of Family Size** | 1-3 members = 55-60% survival (optimal) |
| 6 | **Class × Gender Interaction** | First women: 96.7% vs Third men: 14.2% |

### Chart Previews

**Chart 2: Gender Disparity**
![Gender Chart](https://via.placeholder.com/400x250?text=Gender+Disparity+Chart)

**Chart 6: Class × Gender Interaction**
![Interaction Chart](https://via.placeholder.com/400x250?text=Class+Gender+Interaction)

## 🛠️ Technologies Used

- **Python 3.9+** - Core programming language
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical operations
- **Matplotlib** - Base plotting library
- **Seaborn** - Statistical visualizations
- **Jupyter Notebook** - Interactive development

### Quality Settings Applied

```python
plt.rcParams['figure.dpi'] = 300        # High resolution
plt.rcParams['savefig.dpi'] = 300       # Publication quality
plt.rcParams['font.size'] = 11          # Readable text
plt.rcParams['axes.labelsize'] = 12     # Clear axis labels
plt.rcParams['axes.titlesize'] = 14     # Bold titles
