## Quantum theory helper

This project provides a model that can answer on questions and solve easy (or not) tests.
On data collected from assessments in uni model achieved accuracy score of 0.65.

For more details see the report [report](https://github.com/bivba/prikols/repo/report.pdf).

![image](https://github.com/user-attachments/assets/ad2ac9ba-1d25-4bf0-8acc-25996acb78e1)

Here is the link to the [huggingface repo](https://huggingface.co/bivba/quant_4bit) of this model.


## Setup

Visit the [notebooks](https://github.com/bivba/prikols/notebooks) to see the code for [training](https://github.com/bivba/prikols/notebooks/quanti.ipynb) and for [inference](https://github.com/bivba/prikols/notebooks/inference.ipynb).

To run these notebooks you most likely will need a Kaggle account.

To perform a training import notebook to Kaggle and run all the cells and then run DPO training or SFT training depending on what u need.

DPO training will not fit in the 16GB VRAM in kaggle if used with batch size more than 1.

After training u can push the model to your hugging face repo

Because of model size it will be problematic to use the model locally so for the inference you also need to import notebook to Kaggle and run cells up to the evaluating markdown.

