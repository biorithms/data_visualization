# Data Visualization Fundamental: From Data to Story

This repository was designed for anyone interested in learning how to communicate insights through data visualization. 

---
## Questions to ask before you start plotting
While many tutorial focueses on how to create a one off plot, few explain why we would want to use a particular chart and what is the *story* that the visualization is trying to convey. Before you start writing a single line of code or creating a plot, ask yourself:
* What story am I trying to tell?
* Who is the audience?
* What action do I want my audience to take?
* What should be emphasized?
* What is the Data-to-Ink Ratio?


### What story am I trying to tell?
Data visualization is not just about making plots and charts. It is about communicating information to your audience and this story is what determines the type of visualization you will want to use. Additionally, who your audience is will also influence what type of visualization you want to use.

Examples:
* Is there a relationship between two variables?
* Are there outliers that deserve attention?
* How do groups or categories compare against one another?

---
### What is the primary message that you want to come across?
At a quick glance, what do you want your audience to learn or take away if they only spend 5 seconds looking at your plot?

Examples:
* Treatment A outperformed Treatment B
* Sales revenue increased 30% this year

---

### What should be emphasized in your plot?
Not everything deserves equal visual weight. If you try to communicate every piece of data, this can be more confusing instead of clearer.

Consider:

* Highlighting important categories
* Using color intentionally
* Annotating critical observations
* De-emphasizing background information

---

## 5. What is the Data-to-Ink Ratio?

A concept popularized by Edward Tufte.

The idea:

> Maximize the amount of ink dedicated to actual information and minimize non-essential visual elements.

Good examples:

✅ Clean labels

✅ Minimal gridlines

✅ Limited colors

✅ Focus on the data

Avoid:

❌ Excessive borders

❌ Unnecessary backgrounds

❌ Decorative effects

❌ Chart junk

---

# Choosing Colors Intentionally

Color should communicate meaning.

Questions to consider:

### Sequential Data

Use gradients when values move from low to high.

Examples:

* Population
* Revenue
* Temperature

### Diverging Data

Use contrasting colors around a midpoint.

Examples:

* Profit vs Loss
* Above vs Below Average

### Categorical Data

Use distinct colors for separate groups.

Examples:

* Product categories
* Species
* Regions

### Highlighting

Use one strong color to draw attention while keeping everything else neutral.

---

# Visualization Types Covered

This repository includes examples for:

## Comparison Charts

* Bar Charts
* Horizontal Bar Charts
* Grouped Bar Charts
* Stacked Bar Charts

## Trend Charts

* Line Charts
* Multi-Line Charts
* Area Charts

## Relationship Charts

* Scatter Plots
* Bubble Charts
* Correlation Visualizations

## Distribution Charts

* Histograms
* Density Plots
* Box Plots
* Violin Plots

## Part-to-Whole Charts

* Pie Charts
* Donut Charts
* Treemaps

## Advanced Interactive Visualizations

* Plotly Interactive Charts
* Hover Tooltips
* Interactive Dashboards

---

# Technologies Used

## Python

Used for data manipulation and visualization.

Libraries include:

* pandas
* numpy
* matplotlib
* plotly

---

## Matplotlib

Industry-standard plotting library for static visualizations.

Best for:

* Publication-quality figures
* Scientific graphics
* Full customization

---

## Plotly

Interactive visualization framework.

Best for:

* Dashboards
* Interactive exploration
* Web-ready graphics

---

## Google Sheets

Great for:

* Rapid prototyping
* Basic business reporting
* Collaboration

Examples include:

* Charts directly from Sheets
* Dashboard-style reporting
* Conditional formatting techniques

---

# Repository Structure

```text
├── notebooks/
│   ├── line_plots.ipynb
│   ├── bar_charts.ipynb
│   ├── scatter_plots.ipynb
│   ├── histograms.ipynb
│   └── plotly_examples.ipynb
│
├── datasets/
│   ├── sample_sales.csv
│   ├── customer_data.csv
│   └── scientific_data.csv
│
├── images/
│   └── example_outputs/
│
└── README.md
```

---

# Requirements

Install Python packages:

```bash
pip install pandas numpy matplotlib plotly jupyter
```

---

This repository is to provide a practical collection of examples demonstrating how to create effective visualizations using multiple tools, including:
* Google Sheets
* Python and Jupyter Notebooks (`.ipynb`)
* Matplotlib
* Plotly

# Prerequisites

To follow all examples, you should have:

* Python 3.10+
* Jupyter Notebook or Jupyter Lab
* Matplotlib
* Plotly
* Pandas
* NumPy
* Access to Google Sheets

---

# Learning Goals

By working through this repository, you will learn:

* How to choose the right visualization
* How to build visualizations using multiple tools
* How to create publication-quality graphics
* How to create interactive dashboards
* How to use color effectively
* How to improve the data-to-ink ratio
* How to communicate insights clearly through visual storytelling

---

# Remember

A visualization is not successful because it looks beautiful.

A visualization is successful because it helps someone understand something they did not understand before.

Start with the story.

Then choose the visualization.

This README positions the repository as a visualization and storytelling resource rather than just a collection of plotting code, which will make it more valuable for learners and recruiters reviewing your GitHub profile.
