Here’s the updated README with your GitHub profile name included and a license section added:

---

```markdown
# ASD-DiagNet: A Hybrid Learning Approach for Autism Spectrum Disorder Detection Using fMRI Data

This repository contains the implementation of **ASD-DiagNet**, a hybrid learning approach for detecting Autism Spectrum Disorder (ASD) using functional Magnetic Resonance Imaging (fMRI) data. The algorithm is based on the methodology presented in the research paper by Taban Eslami et al. (2019).

---

## 📄 Research Article

If you use this repository in your research, please cite the following article:

**Taban Eslami, Fahad Saeed, Vahid Mirjalili, Alvis Fong, and Angela Laird (2019).**  
*"ASD-DiagNet: A Hybrid Learning Approach for Detection of Autism Spectrum Disorder Using fMRI Data."*  
Published in *Frontiers in Neuroinformatics, 13:70 (2019)*  
[Read the Full Article](https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2019.00070/full)

---

## 🔧 Environment Setup

### Hardware Requirements
- A server with a CUDA-enabled GPU (compute capability 3.5 or higher)

### Software Requirements
- **Python** (version 3.5 or higher)  
- **PyTorch** (version 0.4.1)  
- **CUDA** (version 8.0 or higher)  
- **Jupyter Notebook**

---

## ⚙️ Parameter Configuration

Before running the notebook, please configure the following parameters in the first cell:

- **Atlas Name**: Select one of the following options: `"cc200"`, `"aal"`, or `"dosenbach160"`  
  *Example:*  
  ```python
  p_ROI = "cc200"
  ```

- **Number of Folds for Cross-Validation**: Integer value specifying the number of folds  
  *Example:*  
  ```python
  p_fold = 10
  ```

- **Classification Mode**: Specify `"whole"` or `"percenter"` for the desired classification strategy  
  *Example:*  
  ```python
  p_mode = "percenter"
  ```

- **Center Name**: Required only for per-center classification  
  *Example:*  
  ```python
  p_center = "Stanford"
  ```

- **Classification Method**: Choose one of the following: `"ASD-DiagNet"`, `"rf"`, or `"SVM"`  
  *Example:*  
  ```python
  p_Method = "ASD-DiagNet"
  ```

- **Data Augmentation**: Specify `True` or `False` to enable or disable data augmentation (applicable only for ASD-DiagNet)  
  *Example:*  
  ```python
  p_augmentation = False
  ```
  
---

## 🛡️ License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/DiogoLepri/ASD2_Project/blob/main/LICENSE) file for details.

---

## Acknowledgment

We extend our gratitude to the research community and collaborators who contributed to the development of this project.

---

Thank you for your interest in **ASD-DiagNet**. We welcome feedback and contributions. If you encounter any issues, please submit them via the [Issues](https://github.com/DiogoLepri/ASD2_Project/issues) section.
```

---

### Summary of Changes:
1. **Updated Contact and Profile Information**: Replaced the placeholder email and GitHub links with references to your profile (`DiogoLepri`).  
2. **Added a License Section**: Included the MIT License with a link to the `LICENSE` file in the repository.  
3. **Formal Language and Structure**: Maintained a professional and clear tone throughout.

Let me know if you want to specify a different license type or adjust the contact details!
