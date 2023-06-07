# Dataset for Internal Portofolio of Company


## Datasets
- internal-datasets: https://github.com/Marbyun/datasets-huggingface/raw/master/internal-data/internal-datasets.zip

You can also load this dataset directly in 🤗 HuggingFace transformers using:

```
from datasets import load_dataset
dataset = load_dataset("Marbyun/internal-datasets")
```

For further details, refer to the `README.md` files associated with each dataset. For any further technical details, kindly refer to the paper.


## Citation
If you use this work, please consider citing:

```
@inproceedings{bartolo-etal-2021-improving,
    title = "Improving Question Answering Model Robustness with Synthetic Adversarial Data Generation",
    author = "Bartolo, Max  and
      Thrush, Tristan  and
      Jia, Robin  and
      Riedel, Sebastian  and
      Stenetorp, Pontus  and
      Kiela, Douwe",
    booktitle = "Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2021",
    address = "Online and Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.emnlp-main.696",
    doi = "10.18653/v1/2021.emnlp-main.696",
    pages = "8830--8848",
    abstract = "Despite recent progress, state-of-the-art question answering models remain vulnerable to a variety of adversarial attacks. While dynamic adversarial data collection, in which a human annotator tries to write examples that fool a model-in-the-loop, can improve model robustness, this process is expensive which limits the scale of the collected data. In this work, we are the first to use synthetic adversarial data generation to make question answering models more robust to human adversaries. We develop a data generation pipeline that selects source passages, identifies candidate answers, generates questions, then finally filters or re-labels them to improve quality. Using this approach, we amplify a smaller human-written adversarial dataset to a much larger set of synthetic question-answer pairs. By incorporating our synthetic data, we improve the state-of-the-art on the AdversarialQA dataset by 3.7F1 and improve model generalisation on nine of the twelve MRQA datasets. We further conduct a novel human-in-the-loop evaluation and show that our models are considerably more robust to new human-written adversarial examples: crowdworkers can fool our model only 8.8{\%} of the time on average, compared to 17.6{\%} for a model trained without synthetic data.",
}
```

## License
This datasets are licensed under the MIT License (https://opensource.org/licenses/MIT). For details on model licensing, kindly refer to their respective model cards.
