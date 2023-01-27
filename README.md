# puns_analogies
The current repository contains the data, code and results of Puns analogies project.
It was realised by the group punalogy [Maeva][Louis][Abir][Camille] for the 2022-2023 Software Project (UE905 EC1) at IDMC (Nancy), under the supervision of Esteban Marquer and Miguel Couceiro.

## Abstract
Punalogy is a generator of puns based on analogical templates. Punalogy takes a word as input and generates a pun by substituting a part of the word with a homophone or a similar-sounding word. For example, given the input "mango," Punalogy might generate the pun "man is to mango as woman is to womango." In addition to generating the pun, Punalogy also creates a meme using a template and existing image generation models.

## Content
- [Install instructions](#install-instructions)
- [Usage instructions](#usage-instruction)
- [Repository structure](#repository-structure)

## Install instructions

This project was designed and tested using Python 3.10.
To setup the project, you have to:
1. clone the repository;
2. [install the Python dependencies](#python-dependencies);
3. [download the datasets](#).

### Python dependencies
It is recommended to use Anaconda to have a dedicated environment for the project.
You can also use Pip.

#### Anaconda setup
Follow the following steps to setup the project with Anaconda.
1. Install Anaconda.
2. Create the environement:
    ```bash
    conda create --name my-awesome-readme python==3.10 numpy jupyter
    ```
3. Install the necessary packages:
    ```bash
    conda install -y --name my-awesome-readme .............
    ```

Any command mentionned further in this file will assume that you have activated the Anaconda environment using `conda activate punalogy-readme`.

#### Pip setup
Follow the following steps to setup the project with Pip.
1. Install Python 3.10.
2. Install the necessary packages:
    ```bash
    pip install numpy jupyter .............
    ```

### Dataset
Download the shortjokes data on Kaggle, available here : https://www.kaggle.com/datasets/abhinavmoudgil95/short-jokes

## Usage instructions
### Basic usage
To run this project using the existing models, run the following after replacing `[file to process.txt]` by the name of your file:
```bash
python main.py [file to process.txt]
```

## Repository structure
- [`README-example.md`](/README-example.md): this file.
- [`main.py`](/main.py): Python script for training the models.
- [`experiment1.py`](/experiment1.py): Python script to run the experiment on the synthetic data, mentionned in section 4.2. of the report.
- [`presentations/`](/presentations/): Intermediate presentations as PDF. Each file is labled using the template `[date]-Presentation_[presentation number]'
- [`results/`](/results/): Results generated during the project.
- [`articles/`](/articles/): Articles read or mentioned in the report, as PDFs. Each file is labeled using the template `[article topic]-[publication year]-[authors' last names].pdf`.
