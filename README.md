![Project Logo][project_logo]
---

<h4 align="center">Analyzing & Visualizing Insurance Portfolio within Florida with <a href="https://en.wikipedia.org/wiki/Python_(programming_language)" target="_blank">Python</a> and <a href="https://en.wikipedia.org/wiki/Microsoft_Power_BI" target="_blank">Power BI</a></h4>

<p align='center'>
<img src="https://i.ibb.co/KxfMMsP/built-with-love.png" alt="built-with-love" border="0">
<img src="https://i.ibb.co/MBDK1Pk/powered-by-coffee.png" alt="powered-by-coffee" border="0">
<img src="https://i.ibb.co/CtGqhQH/cc-nc-sa.png" alt="cc-nc-sa" border="0">
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#demo">Demo</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

## Overview

This project focuses on analyzing and visualizing insurance portfolio of an anonymous company that implemented an aggressive growth plan in 2021 across the counties of Florida.

The dataset used is completely fictitious and solely made-up just for demonstrating a data analytics case study.

The repository directory structure is as follows:

Insurance-Portfolio-Analysis<br>
├─ 01_SOURCE<br>
├─ 02_ETL<br>
├─ 03_DATA<br>
├─ 04_ANALYSIS<br>
├─ 05_DASHBOARD<br>
├─ 06_RESOURCES<br>

The types of content present in the directories is as follows:

**01_SOURCE**

This directory contains the the received/downloaded raw data that needs to be cleaned and organized to ease out the data analysis and visualization process.

**02_ETL**

This directory contains the ETL script that takes the raw dataset as an input, transforms it and exports an analysis-ready dataset into the _03_DATA_ directory.

**03_DATA**

This directory contains the data that can be directly used for exploratory data analysis and data visualization purposes.

**04_ANALYSIS**

This directory contains the python notebooks that analyzes the clean dataset to generate insights.

For analyzing the data with Jupyter Notebook; we have used the clean dataset present in the SQLite database.

**05_DASHBOARD**

This directory contains the markdown file with an embedded Power BI report link that visualizes the data.

The Power BI dashboard contains slicers, cross-filtering and other advance capabilities that end user can play with to visualize a specific facet of the data or, to get additional insights.

**06_RESOURCES**

This directory contains images, icons, layouts, etc. that are used in this project.

## Prerequisites

The major skills that are required as prerequisite to fully understand this project are as follows:

- Basics of Python & Jupyter Notebook
- Basics of Power BI

In order to complete the project, I've used the following applications and libraries

- Python
- Python libraries mentioned in [requirements.txt][requirements] file
- Jupyter Notebook
- Visual Studio Code
- Microsoft Power BI

> The choice of applications & their installation might vary based on individual preferences & system settings.

## Architecture

The project architecture is quite straight forward and can be explained through the below image:

![Process Architecture][process_workflow]

As shown in the above workflow; we are first performing necessary cleaning and transformation in the received raw dataset using Python and exporting the clean dataset as a comma-separated flat file

Finally; we leverage the clean & analysis-ready dataset for exploratory data analysis (EDA) using Jupyter Notebook and creating an insightful report using Power BI.

## Demo

The interactive Power BI dashboard can be viewed here:

[![Power BI Dashboard][dashboard_image]][dashboard_link]

<!-- Image Links -->

[project_logo]: https://github.com/YashwanthNomula/nomulayashu/blob/main/Resources/Project_Image.png
[process_workflow]: https://github.com/YashwanthNomula/nomulayashu/blob/main/Resources/process_architecture.png
[dashboard_image]: https://github.com/YashwanthNomula/nomulayashu/blob/main/Resources/Dashboard_Image.png

<!-- Profile Links -->

[linkedin]: https://www.linkedin.com/in/yashwanth-nomula-/
[dashboard_link]: https://app.powerbi.com/groups/me/reports/614b586d-750c-4582-8837-ad5de4604030/c69073df57beb7031820?experience=power-bi&clientSideAuth=0
