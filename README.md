# SUTD 50.038 Computational Data Science | Visual Question Answering Project
<!-- 
## [Report](AIReport.pdf) | [Slides](https://docs.google.com/presentation/d/1rFt7QGFVdLSPshTbRth7EsdzxvsI5NSsFlLf5Yv9fZA/edit?usp=sharing) | [GUI](https://dr-lazarus-ai-streamlit-frontend-main-wnbdru.streamlit.app/) + [GUI Repo](https://github.com/fauzxan/ai_streamlit_frontend) -->

## Group Name: Hadoop: Distributed Suffering (GPA-Reduce)

### By Bryan Tan (Chen Zhengyu), Christy Lau Jin Yun and Lek Jie Wei

![GUI](ImagesForDemo/gui_screenshot.png)

**Dataset Preprocessing**: We performed our preprocessing of the original [VQAv2 dataset](https://www.kaggle.com/datasets/rajatkumar794/visual-based-question-answering) using our [kaggle preprocessing notebook](https://www.kaggle.com/code/christylau/vqav2-preprocessing).
 
**Dataset**: Our preprocessed VQAv2 dataset can be [found on kaggle](https://www.kaggle.com/datasets/christylau/vqav2-annotations-preprocessed?select=VQAv2_answer_mapping.json).

**Device specifications**: Training and evaluation are performed with an Intel i5-13600k, 32GB of RAM and an RTX 3090 with 24GB VRAM on Ubuntu-22.04 via WSL.

### Important Notebooks (In order of recommended exploration)

1. **`Train_Notebook.ipynb`** contains the code necessary to train a fusion model and save its weights in the designated checkpoint folder. Adapted from [this Kaggle notebook](https://www.kaggle.com/code/bhavikardeshna/visual-question-answering-multimodal-transfomer).  

2. **`Train_CNN_LSTM_Baseline_Notebook.ipynb`** contains the code necessary to train a baseline CNN + LSTM model and save its weights in the designated checkpoint folder.

3. **`GUI_Demo.ipynb`** contains the code necessary to run a GUI for visualising the predictions of our best fusion model.

4. **`EvalAll_Notebook.ipynb`** contains the code necessary to evaluate all models and save the results as a `.csv` file and print the results in LaTeX.

5. **`Train_EvalViLT_Notebook.ipynb`** contains the code necessary to train and evaluate a ViLT model and save its weights. It also contains the code necessary to add ViLT's results to the previous evaluated results table and print them results inLaTeX.

