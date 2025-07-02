# Efficient Hate Speech Detection in Code-Mixed Languages via Full-Model Fine-Tuning and RAG

This repository provides resources for detecting hate speech in code-mixed languages using modern transformer models and full-model fine-tuning. The files in this repository include datasets, experimental notebooks for various models, and supporting documentation.

---

## Repository Structure

- **DATASET.csv**  
  The main dataset used for training and evaluating hate speech detection models. It typically contains code-mixed text samples labeled for hate speech classification.

- **TEST.csv**  
  A separate test dataset for evaluating model performance after training.

- **INDICBert.ipynb**  
  Jupyter Notebook implementing hate speech detection using the IndicBERT model. Contains code for loading data, preprocessing, training, and evaluating IndicBERT on the provided dataset.

- **Muril.ipynb**  
  Jupyter Notebook that demonstrates the use of the MuRIL (Multilingual Representations for Indian Languages) model for hate speech detection. Includes steps for data handling, model training, and evaluation.

- **hateBERT.ipynb**  
  Jupyter Notebook using the HateBERT model, which is specifically trained on hate speech and offensive language, adapted here for code-mixed language detection tasks.

- **XLM_Roberta.ipynb**  
  Jupyter Notebook for experimentation with the XLM-RoBERTa model, a multilingual transformer model, applied to code-mixed hate speech detection.

- **LICENSE**  
  The license file for this repository. This project is released under the MIT License.

- **README.md**  
  This file. Provides an overview of the repository and describes the contents and usage.

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shaazdaud/Efficient-Hate-Speech-Detection-in-Code-Mixed-Languages-via-Full-Model-Fine-Tuning-and-RAG.git
   cd Efficient-Hate-Speech-Detection-in-Code-Mixed-Languages-via-Full-Model-Fine-Tuning-and-RAG
   ```

2. **Open a Notebook:**
   - Choose one of the model notebooks (`INDICBert.ipynb`, `Muril.ipynb`, `hateBERT.ipynb`, `XLM_Roberta.ipynb`) and open it in Jupyter Notebook or Google Colab.
   - Follow the instructions in the notebook to run experiments. Make sure you have the required dependencies installed (often specified at the top of each notebook).

3. **Datasets:**
   - The main dataset is provided as `DATASET.csv`.
   - Use `TEST.csv` for final evaluation.

---

## Notes

- Each notebook is independent and demonstrates how to use a specific transformer model for the hate speech detection task.
- You may need to adjust paths or install additional Python packages as indicated in each notebook's instructions.
- For custom experiments, you can modify the datasets or extend the provided notebooks.

---

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Citation

If you use this repository or its contents in your work, please consider citing or referencing it in your project documentation.

---

For questions or contributions, please open an issue or pull request on the GitHub repository.
