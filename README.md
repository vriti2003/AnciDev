# AnciDev
AnciDev: A Dataset for High-Accuracy Handwritten Text Recognition of Ancient Devanagari Manuscripts

[![Paper Status](https://img.shields.io/badge/Paper-Accepted_(_AACL_BHASHA_2026_)-success)](https://aclanthology.org/2025.bhasha-1.8.pdf)

## Dataset Link : [Google Drive Link](https://drive.google.com/drive/folders/1wOqHgSUPieIoBwQ1ACn6ixpOxBuVo3T6?usp=sharing)

## Code Setup
For training the CNN-RNN and Attention-OCR models, refer [here](https://github.com/ihdia/sanskrit-ocr)
## Citation

If you use this code or find our work helpful, please cite our paper:

```bibtex
@inproceedings{sharma-etal-2025-ancidev,
    title = "{A}nci{D}ev: A Dataset for High-Accuracy Handwritten Text Recognition of {A}ncient {D}evanagari Manuscripts",
    author = "Sharma, Vriti  and
      Verma, Rajat  and
      Saluja, Rohit",
    editor = "Bhattacharya, Arnab  and
      Goyal, Pawan  and
      Ghosh, Saptarshi  and
      Ghosh, Kripabandhu",
    booktitle = "Proceedings of the 1st Workshop on Benchmarks, Harmonization, Annotation, and Standardization for Human-Centric AI in Indian Languages (BHASHA 2025)",
    month = dec,
    year = "2025",
    address = "Mumbai, India",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.bhasha-1.8/",
    doi = "10.18653/v1/2025.bhasha-1.8",
    pages = "91--101",
    ISBN = "979-8-89176-313-5",
    abstract = "The digital preservation and accessibility of historical documents require accurate and scalable Handwritten Text Recognition (HTR). However, progress in this field is significantly hampered for low-resource scripts, such as ancient forms of the scripts used in historical manuscripts, due to the scarcity of high-quality, transcribed training data. We address this critical gap by introducing the \textbf{AnciDev} Dataset, a novel, publicly available resource comprising 3,000 transcribed text lines sourced from 500 pages of different ancient Devanagari manuscripts. To validate the utility of this new resource, we systematically evaluate and fine-tune several HTR models on the \textbf{AnciDev} Dataset. Our experiments demonstrate a significant performance uplift across all fine-tuned models, with the best-performing architecture achieving a substantial reduction in Character Error Rate (CER), confirming the dataset{'}s efficacy in addressing the unique complexities of ancient handwriting. This work not only provides a crucial, well-curated dataset to the research community but also sets a new, reproducible state-of-the-art for the HTR of historical Devanagari, advancing the effort to digitally preserve India{'}s documentary heritage."
}
```


