# The Intelligence In the Loop

This repository contains open-source artifacts regarding the Ph.D. thesis "_The Intelligence in the Loop: Empirical Explorations and Reflections_" by Dr. [Changkun Ou](https://changkun.de).

For any queries regarding this artifact, please contact [research@changkun.de](mailto:research@changkun.de).

## Thesis Source

The [thesis](./thesis) source folder contains the source files of the thesis. The thesis is written in LaTeX.

## Supplementary Artifacts

### 1. Software

The [software](./software) folder contains the source code of the software developed in the thesis. The software is organized as follows:

a. services: the source code of the services developed in the thesis. They are used for conducting the studies in Chapters 5, 6, and 7.
b. backend.zip: the source code of the backend services developed in Chapters 5, 6, and 7 which are responsible for data collection and processing.
c. frontend.zip: the source code of the frontend of the web UI application developed in Chapters 5 and 7, which is responsible for the user interface and data visualization.

Additional third-party dependency requirements are listed in the requirements.txt file, and the instructions for setting up the software are documented in the `setup.md` file.

### 2. Datasets

The [datasets](./datasets) folder contains the datasets used in the thesis. The datasets are collected by the user studies conducted in chapters 5, 6, and 7, therefore organized per chapter via zip compressed files.

## 3. Analysis

All data analysis scripts are organized in the [analysis](./analysis) folder. The relevant scripts are organized per chapter via zip-compressed files.

For chapter 5, the `ch05-1.zip` includes analysis for text summarization studies, and the `ch05-2.zip` includes analysis for image color enhancement studies, `ch05-3.zip` includes analysis scripts for additional questionnaires.

For chapter 6, the file `ch06.zip` includes analysis scripts that reproduce the results in the chapter.

For chapter 7, the file ch07-1.zip includes an additional exploration of the data collected in the chapter, which uses causal analysis, and the ch07-2.zip includes actual finalized analysis scripts that reproduce the results in the chapter. Lastly, the ch07-3.zip includes analysis scripts for the entire intermediate analysis and processing steps, which are not included in the thesis.

### 4. Assets

The [assets](./assets) folder contains the source files for reproducing all figures that appeared in the thesis.

## License

The software is licensed under the [GNU GPL-v3 License](./software/LICENSE). The datasets are licensed under the [CC0 1.0 Universal License](./datasets/LICENSE). The analysis scripts are licensed under the [MIT License](./analysis/LICENSE). All materials, including assets, thesis source code, etc, are [**copyrighted** and **authored**](./LICENSE) by Dr. Changkun Ou.