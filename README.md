# EUFCC-CIR: A Composed Image Retrieval Dataset for GLAM Collections

**Authors**: Francesc Net, Lluis Gomez  
**Institution**: Computer Vision Center, Universitat Autònoma de Barcelona  

## Introduction

The **EUFCC-CIR** dataset is a novel resource designed for Composed Image Retrieval (CIR) within Galleries, Libraries, Archives, and Museums (GLAM) collections. This dataset expands upon the existing **EUFCC-340K** image labeling dataset and provides over 180K annotated CIR triplets. Each triplet consists of an image query and a short text description that indicates the desired modification, paired with a relevant target image. The dataset is especially useful for advancing research in digital humanities, offering a powerful tool for retrieving and interacting with cultural heritage items.

**Paper link:** [EUFCC-CIR Paper](#)  
**Related dataset:** [EUFCC-340K](#https://github.com/cesc47/EUFCC-340K/tree/main)

## Dataset Structure

The dataset is provided in the `data/` folder, containing the following files:
- `db_processed.txt`: Contains a list of images with their respective partition (training, validation, test).
- `cir_db.csv`: Contains detailed information about the image-text pairs and corresponding target images.

In the next figure it can be seen the structure of one of the examples formed:

![](fig/example.png)

## Installation

To use the dataset in your project, you can clone this repository and download the necessary image files from EUFCC-340K.

```bash
git clone https://github.com/your-username/eufcc-cir-dataset.git
cd eufcc-cir-dataset/data
# Download dataset files
