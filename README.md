Below is the complete README content in Markdown format. Simply copy and paste it into your GitHub README file. (I've replaced the contact email with a placeholder; feel free to update it as needed.)

```markdown
# ASD-DiagNet

This repository contains the implementation of the **ASD-DiagNet** algorithm—a hybrid learning approach for the detection of Autism Spectrum Disorder using fMRI data.

## Research Article

If you use our work, please cite our paper:

> **Taban Eslami, Fahad Saeed, Vahid Mirjalili, Alvis Fong, and Angela Laird (2019).**  
> *ASD-DiagNet: A Hybrid Learning Approach for Detection of Autism Spectrum Disorder Using fMRI Data.*  
> *Frontiers in Neuroinformatics, 13:70, 2019.*  
> [Paper Link](https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2019.00070/full)

## Environment Setup

### Hardware Requirements
- A server with a CUDA-enabled GPU (compute capability 3.5 or above).

### Software Requirements
- **Python:** 3.5 or above
- **PyTorch:** 0.4.1
- **CUDA:** 8.0 or above
- **Jupyter Notebook**

## Parameter Settings

Before running the notebook, set the following parameters in the first cell of the Jupyter Notebook:

- **Atlas Name:** Choose one of (`"cc200"`, `"aal"`, or `"dosenbach160"`)  
  *Example:*  
  ```python
  p_ROI = "cc200"
  ```

- **Number of Folds for Cross-Validation:**  
  *Example:*  
  ```python
  p_fold = 10
  ```

- **Classification Mode:** Choose either `"whole"` or `"percenter"`  
  *Example:*  
  ```python
  p_mode = "percenter"
  ```

- **Center Name:** (Only required if using per-center classification)  
  *Example:*  
  ```python
  p_center = "Stanford"
  ```

- **Classification Method:** Choose one of (`"ASD-DiagNet"`, `"rf"`, or `"SVM"`)  
  *Example:*  
  ```python
  p_Method = "ASD-DiagNet"
  ```

- **Data Augmentation:** (Applicable for ASD-DiagNet) Set to either `True` or `False`  
  *Example:*  
  ```python
  p_augmentation = False
  ```

---

For any questions or further information, please contact: [your_email@example.com](mailto:your_email@example.com)
```

Feel free to update the placeholder email with your actual contact information if needed.
