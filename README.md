# Team 6 - AI Semester Project

## Project Overview

This repository contains the work for the AI semester project, focusing on **dataset exploration and selection** for the Madaraka Estate project.

The purpose of this stage is to explore possible datasets, identify an appropriate output (target) variable, and select a dataset that can support the development of a machine learning solution for community service reporting.

## Team Members

| Name                     | Admission Number       |
| ------------------------ | ---------------------- |
| **Emma Ogwayo** | **189923** |
| **Tiffany Maina** | **189592** |
| **Eniola Fabunmi** | **167925** |

## Selected Dataset

### NYC 311 Service Requests

The selected dataset is the **NYC 311 Service Requests from 2020 to Present** dataset.

It contains service requests made by residents concerning different municipal issues. The dataset was selected because the types of reported issues are relevant to the Madaraka Estate project, including community service issues such as water, electricity, waste, and other problems.

The expected output (target) variable is:

```text
Problem (formerly Complaint Type)
```

This variable can be used as the target for a classification model to predict the type of issue being reported based on information contained in a resident's service request.

### Dataset Source

**NYC Open Data:**
https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2020-to-Present/erm2-nwe9

## Other Datasets Considered

Before selecting the NYC 311 dataset, the following datasets were also considered:

1. **Chicago 311 Service Requests**

   * Expected output: `SR_TYPE`
   * Source: City of Chicago Data Portal
   * https://data.cityofchicago.org/Service-Requests/311-Service-Requests/v6vf-nfxy

2. **Kaggle Civic Issue Reports**

   * Expected output: `Priority_Level`
   * Source: Kaggle
   * https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fwajahattaj%2Fcivic-and-municipality-complaint-system-dataset

The datasets were compared based on their relevance to the Madaraka Estate project and the availability of a suitable output variable.

## Repository Contents

```text
SemProject_MLEngine/
│
├── NYC311_Exploration.ipynb
└── README.md
```

### `NYC311_Exploration.ipynb`

This notebook contains the dataset exploration work, including:

* Dataset loading
* Number of rows and columns
* Data types
* Completeness and missing-value analysis
* Sample records from the dataset
* Dataset selection and justification

## Technologies and Tools

* Python
* Pandas
* Jupyter Notebook / Google Colab
* GitHub

## Project Context

This work forms part of the AI semester project for the **Madaraka Estate Web Reporting and Dispatch System**. The broader project aims to support the reporting and management of community service issues such as water, electricity, and waste-related problems.

---

**Course:** ICS 3202 – Artificial Intelligence
**Institution:** Strathmore University
**Academic Year:** 2026
