# HoloViz Tutorial

## **Authors**
- Sophia Yang, Anaconda
- Marc Skov Madsen, datamodelsanalytics.com
- James A. Bednar, Anaconda
- Philipp Rudiger, Anaconda
- Jean-Luc Stevens, Anaconda
- Maxime Liquet, Anaconda

## **Abstract**
This tutorial will show you how to do visualization and build interactive dashboards using HoloViz, which is an open-source visualization ecosystem comprising seven packages. You will learn how to turn nearly any notebook into a deployable dashboard, how to build visualizations easily even for big, streaming, and multidimensional data, how to build interactive drill-down exploratory tools for your data and models without having to run a web-technology software development project, and finally how to deploy your dashboard.

## **Outline**
| **Outline** | **Colab** |
| - | - |
| **Overview** <br /> Python visualization ecosystem <br /> Python dashboarding ecosystem <br /> Seven packages in HoloViz | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_KDD2022/blob/main/01_Overview.ipynb) |
| **Plotting** <br /> Basic plotting with `hvplot` <br /> Grouping <br /> Combine plots <br /> Interlinked plots|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_KDD2022/blob/main/02_Plotting.ipynb)|
| **Big Data Visualization**  <br /> Considerations with big data analytics <br /> Big data visualization with `Datashader` and `hvplot` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_KDD2022/blob/main/03_Big_Data_Visualization.ipynb) |
| **Dashboard**  <br /> Turn Pandas pipelines into a dashboard using `hvPlot .interactive`| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_KDD2022/blob/main/04_Dashboard.ipynb) |
| **Real Time Dashboard** <br /> Create streaming dataframe with `streamz` <br /> Create databoard with `pn.bind` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_KDD2022/blob/main/05_Real_Time_Dashboard.ipynb) |
| **Deployment** <br /> Local deployment <br /> Save to .html files <br /> Cloud deployment <br /> PyScript | [Slides](https://sophiamyang.github.io/HoloViz_KDD2022/06_Deployment.html) |

## **Set up**
You can run the tutorials through the links above. To run this tutorial locally, you will need to do the following steps:
- Download Anaconda or Miniconda
- Git clone this repository and navigate to the folder
```
git clone git@github.com:sophiamyang/HoloViz_KDD2022.git
cd HoloViz_KDD2022
```
- Create a new Conda enviornment with needed packages and activate this enviornment
```
conda create --name holoviz -c conda-forge hvplot panel pandas jupyterlab streamz
conda activate holoviz
```
- Start Jupyter Notebook `jupyter notebook` or Jupyter Lab `jupyterlab`



## **References**
https://holoviz.org <br />
https://hvplot.holoviz.org <br />
https://datashader.org <br />
https://panel.holoviz.org <br />
Tutorial <a href="https://www.youtube.com/watch?v=xlFMLQKZi3I">Easily build interactive plots and apps with hvPlot</a> by Philipp Rudiger and Maxime Liquet
<br>
Tutorial <a href="https://anaconda.cloud/easy-plotting-for-streaming-data">Easy Plotting for Streaming Data</a> by James A. Bednar
<br>
Blog post <a href="https://sophiamyang.medium.com/python-dashboarding-ecosystem-and-landscape-cc055b50c668?sk=08add22d8399b2b78b70af599b52fd12">Python Dashboarding Ecosystem and Landscape: Plotly Dash, Panel, Voila, and Streamlit</a> by Sophia Yang
<br>
Blog post <a href="https://sophiamyang.medium.com/the-easiest-way-to-create-an-interactive-dashboard-in-python-77440f2511d1?sk=e1ea8c40c090cdbe7689333267f73b25">The Easiest Way to Create an Interactive Dashboard in Python Visualization: Turn Pandas pipelines into a dashboard using hvPlot .interactive</a> 
by Sophia Yang and Marc Skov Madsen
<br>
Blog post <a href="https://towardsdatascience.com/big-data-visualization-using-datashader-in-python-c3fd00b9b6fc?sk=2e619dad70084fbf69d26cff55930f84">Big Data Visualization Using Datashader in Python</a> by Sophia Yang







