=================================
Dataset
=================================

### **Dataset**


Different stages rely on different types of training data. A high-quality training dataset will affect the capacity of the trained MFFMs. This part will discuss each stage's dataset construction and characteristics.

- **Pre-training dataset.** As the first stage, pre-training data aims to provide multimodal financial knowledge for models and enable the model to align the different modalities. During this stage, different models curate their unique training corpora. A representative training dataset is BloombergGPT's FinPile. It comprises a total of 345 billion tokens from public data and 363 billion tokens from proprietary data.
    

- **Instruction-tuning dataset.** This stage aims to teach models to better understand the instructions from the demanded tasks to boost zero-shot capacity. 

  - **OpenFinLLaVA** first assembled a comprehensive multimodal dataset, subsequently utilizing GPT-4o to extract financial content selectively. Ultimately, OpenFinLLaVA created an extensive collection of 662k multimodal pre-trained datasets, comprising images, charts, and tables. 
  - **FinVis-GPT** utilized historical daily data from Chinese A-share stocks to create visualizations, distributing the output into 80\% candlestick and 20\% line charts. 
  - **FinTral** utilizes several datasets to build a visual pretraining dataset. Additionally, the Llava Instruct dataset is employed to enhance instruction understanding in the multimodal LLMs, resulting in the creation of the instruction tuning dataset, FinVis-IT.
