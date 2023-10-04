# JapaneseEmbeddingEval

## Spearman's rank correlation coefficient
Cosine similarity was used to calculate the similarity of sentence pairs.

| Model | JSTS valid-v1.1 | JSICK test |
| :---         |          ---:  |          ---: |
| [colorfulscoop/sbert-base-ja](https://huggingface.co/colorfulscoop/sbert-base-ja) | 0.7423     | 0.6573    |
| [MU-Kindai/SBERT-JSNLI-base](https://huggingface.co/MU-Kindai/SBERT-JSNLI-base) | 0.7652       | 0.6526      |
| [sonoisa/sentence-bert-base-ja-mean-tokens-v2](https://huggingface.co/sonoisa/sentence-bert-base-ja-mean-tokens-v2) | 0.8086       | 0.7680      |
| [oshizo/sbert-jsnli-luke-japanese-base-lite](https://huggingface.co/oshizo/sbert-jsnli-luke-japanese-base-lite) | 0.8109       | 0.7260      |
| [pkshatech/simcse-ja-bert-base-clcmlp](https://huggingface.co/pkshatech/simcse-ja-bert-base-clcmlp) | 0.8014       | 0.7345      |
| [universal-sentence-encoder-multilingual-large-3](https://tfhub.dev/google/universal-sentence-encoder-multilingual-large/3) | 0.8014       | 0.8232      |
| [universal-sentence-encoder-multilingual-3](https://tfhub.dev/google/universal-sentence-encoder-multilingual/3) | 0.7899       | 0.8003      |
| [text-embedding-ada-002](https://platform.openai.com/docs/guides/embeddings) | 0.7900 | 0.7894 |
| [intfloat/multilingual-e5-base](https://huggingface.co/intfloat/multilingual-e5-base) | 0.7964 | 0.8056 |
| [intfloat/multilingual-e5-large](https://huggingface.co/intfloat/multilingual-e5-large) | <ins>0.8185</ins> | 0.7939 |
| [pkshatech/GLuCoSE-base-ja](https://huggingface.co/pkshatech/GLuCoSE-base-ja) | 0.8176 | 0.7570 |
| [cl-nagoya/unsup-simcse-ja-base](https://huggingface.co/cl-nagoya/unsup-simcse-ja-base) | 0.7894 | 0.7900 |
| [cl-nagoya/unsup-simcse-ja-large](https://huggingface.co/cl-nagoya/unsup-simcse-ja-large) | 0.8140 | 0.7961 |
| [cl-nagoya/sup-simcse-ja-base](https://huggingface.co/cl-nagoya/sup-simcse-ja-base) | 0.8085 | <ins>0.8274</ins> |
| [cl-nagoya/sup-simcse-ja-large](https://huggingface.co/cl-nagoya/sup-simcse-ja-large) | **0.8307** | **0.8305** |

## Datasets

* JSTS valid-v1.1
    * https://github.com/yahoojapan/JGLUE
    * 1,457 sentence pairs

* JSICK test
    * https://github.com/verypluming/JSICK
    * 4,927 sentence pairs