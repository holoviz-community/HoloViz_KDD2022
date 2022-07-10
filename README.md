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
| **Overview** <br /> Python visualization ecosystem <br /> Python dashboarding ecosystem <br /> Seven packages in HoloViz | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_tutorial2022/blob/main/01_Overview.ipynb) |
| **Plotting** <br /> Basic plotting with `hvplot` <br /> Grouping <br /> Combine plots <br /> Interlinked plots|  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_tutorial2022/blob/main/02_Plotting.ipynb)|
| **Big Data Visualization**  <br /> Considerations with big data analytics <br /> Big data visualization with `Datashader` and `hvplot` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_tutorial2022/blob/main/03_Big_Data_Visualization.ipynb) |
| **Dashboard**  <br /> Turn Pandas pipelines into a dashboard using `hvPlot .interactive`| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_tutorial2022/blob/main/04_Dashboard.ipynb) |
| **Real Time Dashboard** <br /> Create streaming dataframe with `streamz` <br /> Create databoard with `pn.bind` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sophiamyang/HoloViz_tutorial2022/blob/main/05_Real_Time_Dashboard.ipynb) |
| **Deployment** <br /> Local deployment <br /> Save to .html files <br /> Cloud deployment <br /> PyScript | [Slides](https://sophiamyang.github.io/HoloViz_tutorial2022/06_Deployment.html) |

## **Set up**
You can run the tutorials through the links above. To run this tutorial locally, you will need to do the following steps:
- Download Anaconda or Miniconda
- Git clone this repository and navigate to the folder
```
git clone git@github.com:sophiamyang/HoloViz_tutorial2022.git
cd HoloViz_tutorial2022
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
https://panel.holoviz.org






