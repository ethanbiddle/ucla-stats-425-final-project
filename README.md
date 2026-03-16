# ucla-stats-425-final-project

This repository contains materials for UCLA's STATS425 final project analyzing pointwise mutual information (PMI) scoring for multiple-choice question answering using GPT-2-medium on CommonsenseQA.

## Contents

* `code/` : Python notebook for LM, PMI, and confidence analysis
* `report/` : Final conference-style written report
* `slides/` : Presentation slide deck
* `figures/` : Visualizations used in report and presentation

## Dataset

CommonsenseQA loaded using Hugging Face:

from datasets import load_dataset
dataset = load_dataset("commonsense_qa", split="train[:1000]")

## Main Results

* LM Accuracy: 30.5%
* PMI Accuracy: 36.5%
* UNC Accuracy: 20.5%
