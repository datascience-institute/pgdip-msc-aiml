# PG Diploma / MSc in Computer Science (AI and ML): practice materials

This repository holds the hands-on materials for the Data Science Institute's PG Diploma / MSc in Computer Science (AI and ML):

- the practice notebook and datasets for each lesson;
- the input datasets for each module's case study, assignments and summative assessment.

Instructions for case studies, assignments and assessments are on the DSI platform, not here.

## Modules

- [M01 – Introduction to Python Programming](M01-introduction-to-python-programming/)
- [M02 – Applied Statistics](M02-applied-statistics/)
- [M03 – Mathematics for Computer Science](M03-mathematics-for-computer-science/)
- [M04 – Machine Learning Fundamentals](M04-machine-learning-fundamentals/)
- [M05 – High Dimensional Data Analysis](M05-high-dimensional-data-analysis/)
- [M06 – Advanced Machine Learning](M06-advanced-machine-learning/)
- [M07 – Introduction to Deep Learning](M07-introduction-to-deep-learning/)
- [M08 – Deep Learning for Computer Vision](M08-deep-learning-for-computer-vision/)
- [M09 – Deep Learning for NLP](M09-deep-learning-for-nlp/)
- [M10 – Productionization of ML Systems](M10-productionization-of-ml-systems/)

## How the folders are organised

```
M02-applied-statistics/
├── README.md                      module name and lesson list
├── L02-statistical-measures/      lesson practice notebook, its datasets and a ZIP of both
├── case-study/data/               case study datasets
├── assignments/A1/                A1.zip and data/ for Assignment 1
└── summative/                     summative.zip and data/ for the summative assessment
```

Some lessons have no practice files, and some assessments use data that the notebook downloads itself, so not every module has every folder.

## Downloading the materials

**From the DSI platform.** Use the download button on the lesson or assessment page. It downloads the ZIP for that lesson or assessment.

**From GitHub.** Open the lesson or assessment folder, click the `.zip` file, then click **Download raw file**. To download one file, open it and use the same button.

**Everything at once.** On the repository's front page, click **Code**, then **Download ZIP**. If you use Git, you can clone it instead:

```
git clone https://github.com/datascience-institute/pgdip-msc-aiml.git
```

## Running the notebooks

1. Unzip the download. Keep the notebook and its data files together in the same folder: the notebooks open the data by file name.
2. Open the notebook in Jupyter (JupyterLab or Jupyter Notebook) with Python 3, or upload the notebook and its data files to Google Colab.
3. If a library is missing, install it with `pip install <library-name>`. Each notebook imports the libraries it needs near the top.
4. Run the cells in order from the top.
