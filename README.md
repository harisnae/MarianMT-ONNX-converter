# MarianMT-ONNX-converter

A Colab notebook that installs the required dependencies, converts a MarianMT model to ONNX, (optionally) quantises it and pushes the result to the Hugging Face Hub.

## Run it in Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/harisnae/marianmt-onnx-converter/blob/main/marianmt_onnx_convertor.ipynb)

## Requirements (for reference)

```
huggingface_hub
streamlit
optimum==1.27.0
onnx==1.16.0
tqdm==4.67.1
onnxslim==0.1.48
numpy==2.2.6
sacremoses==0.0.53
sentencepiece==0.1.99
onnxruntime-gpu==1.20.0
onnxruntime-tools==1.7.0
transformers[torch]==4.49.0
```

## Quick local run

```bash
git clone https://github.com/harisnaeem/MarianMT-ONNX-converter.git
cd MarianMT-ONNX-converter
pip install -r requirements.txt   # optional, see notebook for exact versions
jupyter notebook MarianMT_to_ONNX_Convertor.ipynb

