# HSCDA

## Introduction  
This study introduces a novel method for predicting associations based on hypergraph convolution with hyperedge gating and semantic-enhanced graph convolutional network for circRNA-disease association prediction (HSCDA). 

## Catalogs  
- **/data**: Contains the dataset used in our model.
- **/code**: Contains the code implementation of HSCDA.
- **data_process.ipynb**: Processes the circRNA and disease similarities, associations, features, and adjacency matrices for traning and testing.
- **case_study_data_process.ipynb**: Processes the circRNA and disease similarities, associations, features, and adjacency matrices for case study.
- **main.ipynb**: Defines the model and trains the model.
- **case_study.ipynb**: Experiments for case study.

---
## Dataset  
- **circRNA_names.npy**: Contains the names of 834 circRNAs.  
- **disease_names.npy**: Contains the names of 138 diseases.  
- **miRNA_names.npy**: Contains the names of 555 miRNAs.  
- **disease_disease.npy**: Includes the similarities among the diseases.
- **circRNA_disease.npy**: Includes the associations between the circRNAs and diseases.
- **circRNA_miRNA.npy**: Includes the associations between the circRNAs and miRNAs.
- **Supplementary Table ST1.xlsx**: Lists the top 20 candidate circRNAs for each disease.


---
## Environment  
The MNCDA code has been implemented and tested in the following development environment: 

- Python == 3.8.18
- Matplotlib == 3.7.2
- PyTorch == 1.12.1
- NumPy == 1.24.3
- Scikit-learn == 1.3.0
- Scipy == 1.10.1
  
---
## How to Run the Model  
1. **Data preprocessing**: Constructs the adjacency matrices, features, and other inputs for training the model.  
    
    ```bash
    data_process.ipynb
    ```
    
2. **Train and test the model**.  
    
    ```bash
    main.ipynb
    ```

**Run this notebook**: simply run all the cells in these notebook.
