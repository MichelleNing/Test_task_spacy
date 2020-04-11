# Test Task

It required to develop a procedure for evaluating an open-source machine learning system (spacy) in terms of its general performance and application to the target domain data. 

## Intrduction

The data science team is given the challenge to create a machine learning system that is able to recognize organization entities in email messages. In this task, analyze the spaCy model for organization detection on two datasets. 

## Instruction

1. cd into the project directory

2. Download anaconda or miniconda based on the instructions in the [anaconda website](https://docs.anaconda.com/anaconda/install/) and [miniconda website](https://docs.conda.io/projects/conda/en/latest/user-guide/install/).

3. Create a new conda environment:
conda create --name spacy_test python=3

4. Enter your new environment:
- Mac/Linux: `>> source activate spacy_test`
- Windows: `>> activate spacy_test`

5. Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:
`conda install -c conda-forge spacy`
`python -m spacy download en_core_web_sm`

6. Run the following to open up the notebook server:
`jupyter notebook`
