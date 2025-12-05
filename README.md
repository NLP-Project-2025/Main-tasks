<div align="center">
<h1 align="center">
Final Project for 50.040 Natural Language Processing
</h1>
<br>
<p>Mohammad Saif Zia | Rose Evangeline Anne Dagman Destor | Joel Lim | Tania Koh Tze Ern</p>
</div>

## Default project brief
*Refer to `Project brief.pdf`*

## Directory structure
```shell
Root
├── config.py
├── utils.py
├── optimizer_test.npy
├── Task 1 and 2.ipynb
├── Task 3 per langauge.ipynb
├── Task 3 all langauge.ipynb
├── pretrain.txt
├── XNLI-1.0/
├── XNLI-MT-1.0/
└── README.md
```

## Reproducibility
1. Git clone this project
`git clone https://github.com/NLP-Project-2025/Main-tasks.git`

2. Install dependencies
`pip install -r requirements.txt`

3. For inference, download our weights from [Google Drive](https://drive.google.com/drive/folders/1hfwmchlaXzY2vMPwKn73n9PWvMt8ATxW?usp=sharing) and store the corresponding weights (`.pt`)
in folder `best_model`.

4. For training and testing, download XNLI dataset (monolingual) from
- https://dl.fbaipublicfiles.com/XNLI/XNLI-1.0.zip
- https://dl.fbaipublicfiles.com/XNLI/XNLI-MT-1.0.zip

    You can also download our custom dataset (code-switched) from [Google Drive](https://drive.google.com/drive/folders/1WSNE6j6XWwDucAy8UyIUhui8nsJQh1Yw?usp=sharing). See [repo](https://github.com/NLP-Project-2025/code-switching-pipeline) for implementation.

5. How to run:
- `task1_2.ipynb` → Custom GPT-2 implementation + English NLI fine-tuning
- `task3_per_lang.ipynb` → Zero-shot multilingual evaluation + Per-language fine-tuning
- `task3_all_lang.ipynb` → All-language fine-tuning
- Extended task is found in this [repo](https://github.com/NLP-Project-2025/Extended-Task)


## Results
To-DO: add Full report

To-Do: include the table