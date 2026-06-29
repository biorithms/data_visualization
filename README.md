# Data Visualization Fundamental: From Data to Story

<img src="../images/dv_banner.png">

This repository was designed for anyone interested in learning how to communicate insights through data visualization. A visualization is not successful because it looks beautiful; it is successful because it helps someone understand something they did not understand before. Start with the story, then choose the visualization.

---
## Questions to ask before you start plotting
While many tutorial focueses on how to create a one off plot, few explain why we would want to use a particular chart and what is the *story* that the visualization is trying to convey. Before you start writing a single line of code or creating a plot, ask yourself:

### What story am I trying to tell?
Data visualization is not just about making plots and charts. It is about communicating information to your audience and this story is what determines the type of visualization you will want to use. Additionally, who your audience is will also influence what type of visualization you want to use.

Examples:
* Is there a relationship between two variables?
* Are there outliers that deserve attention?
* How do groups or categories compare against one another?

### What is the primary message that you want to come across?
At a quick glance, what do you want your audience to learn or take away if they only spend 5 seconds looking at your plot? Are there any action you want your audience to take after they view your plot?

Examples:
* Treatment A outperformed Treatment B
* Sales revenue increased 30% this year

### What should be emphasized in your plot?
Not everything deserves equal visual weight. If you try to communicate every piece of data, this can be more confusing instead of clearer. There are some considerations you can take to make your plot more clear for your audience. Consider:
* Highlighting important categories
* Using color intentionally
* Annotating critical observations
* De-emphasizing background information

### Implementing Data-to-Ink Ratio in your plot

This is a concept popularized by Edward Tufte. The idea behind the data-to-ink ratio is to maximize the amount of ink dedicated to the essential information you want to convey and minimize the non-essential visual elements.

When you are designing your plot, consider:
* Clean labels (axes, title, legend, values on plot)
* Limiting colors and using color intentionally
* Focus on the essential data
* Avoid using excessive borders or gridlines
* Remove unnecessary background
* Avoid using decorative effects that can be distracting

---
## Types of visualization we will cover in this repository
This repository includes examples for:
### Comparison Charts
* Bar Charts
* Horizontal Bar Charts
* Grouped Bar Charts
* Stacked Bar Charts

### Relationship Charts
* Scatter Plots
* Bubble Charts
* Correlation Visualizations

### Distribution Charts
* Histograms
* Density Plots
* Box Plots
* Violin Plots

### Trend Charts
* Line Charts
* Multi-Line Charts
* Area Charts

### Advanced Interactive Visualizations
* Plotly Interactive Charts
* Hover Tooltips
* Interactive Dashboards

---
## Technologies Used and Requirements
We will mainly be using Python for data manipulation and visualization. We will additionally use Google Sheets for prototyping, collaboration, and reporting). To follow all examples, you should have:
* Python 3.10+
* Jupyter Notebook or Jupyter Lab
* Google Sheets
* Pandas (Python library to work with DataFrame)
* NumPy (Python library)
* Matplotlib (Python library use for static visualizations and produces publication-quality figures and scientific graphs)
* Plotly (Python library use to make interactive visualization framework useful for dashboard and interactive exploration)

### Install Python packages:
```bash
pip install pandas numpy matplotlib plotly jupyter
```

---
## Repository Structure

```text
├── Comparison Charts/
│   ├── bar_charts.ipynb
│   ├── horizontal-bar_charts.ipynb
│   └── grouped-stacked_charts.ipynb
│
├── Trend Charts/
│   ├── line_plots.ipynb
│   └── multiline_plots.ipynb
│
├── Relationship Charts/
│   ├── scatter_plots.ipynb
│   └── correlation_plots.ipynb
│
├── Distribution Charts/
│   ├── histogram_plots.ipynb
│   ├── density_plots.ipynb
│   ├── box_plots.ipynb
│   ├── violin_plots.ipynb
│   └── density_plots.ipynb
│
├── Advanced Interactive Visualizations
│   ├── plotly_plots.ipynb
│   └── interactive-dashboards.ipynb
│
├── Datasets/
│   ├── sample_sales.csv
│   ├── customer_data.csv
│   └── scientific_data.csv
│
├── images/
│   └── example_outputs/
│
└── README.md
```
