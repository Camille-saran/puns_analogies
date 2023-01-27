# puns_analogies
The current repository contains the data, code and results of Puns analogies project.
It was realised by the group punalogy [Maeva][Louis][Abir][Camille] for the 2022-2023 Software Project (UE905 EC1) at IDMC (Nancy), under the supervision of Esteban Marquer and Miguel Couceiro.
You can find our reddit account here : https://www.reddit.com/user/meme_pun

## Abstract
Punalogy is a generator of puns based on analogical templates. Punalogy takes a word as input and generates a pun by substituting a part of the word with a homophone or a similar-sounding word. For example, given the input "mango," Punalogy might generate the pun "man is to mango as woman is to womango." In addition to generating the pun, Punalogy also creates a meme using a template and existing image generation models.

## Content
- [Instructions](#install-instructions)
- [Usage instructions](#usage-instruction)
- [Repository structure](#repository-structure)

## Instructions

This project was designed and tested using Python 3.10 on Google Collab.
To setup the project, you have to:
1. Download program notebook;
2. Get a ID token for Hugging Face;
3. Download the dataset, and meme template.

### Dataset
Download the shortjokes data on Kaggle, available here : https://www.kaggle.com/datasets/abhinavmoudgil95/short-jokes

## Usage instructions
### Basic usage
To run this project just open the program into Google Colab. You will have to enter your own hugging face token and your own path to the shortjokes dataset.

## Repository structure
- [`README-example.md`](/README-example.md): this file.
- [`experiment1.py`](/experiment1.py): Python script to run the experiment on the synthetic data, mentionned in section 4.2. of the report.
- [`presentations/`](/presentations/): Intermediate presentations as PDF. Each file is labled using the template `[date]-Presentation_[presentation number]'
- [`results/`](/results/): Result of meme evaluation of human project.
- [`articles/`](/articles/): Articles read or mentioned in the report, as PDFs. Each file is labeled using the template `[article topic]-[publication year]-[authors' last names].pdf`.
