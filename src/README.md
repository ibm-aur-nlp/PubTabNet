# Tree-Edit-Distance-based Similarity (TEDS)

Evaluation metric for table recognition. This metric measures both the structure similarity and the cell content similarity between the prediction and the ground truth. The score is normalized between 0 and 1, where 1 means perfect matching.

## How this metric works

Please see Section V in [our paper](https://arxiv.org/abs/1911.10683) for the principle of this metric.

## How to use the code

### Installation

`pip install -r requirements.txt`

### Run the code

Please see [this demo](demo.ipynb).

## Cite us

```
@article{zhong2019image,
  title={Image-based table recognition: data, model, and evaluation},
  author={Zhong, Xu and ShafieiBavani, Elaheh and Jimeno Yepes, Antonio},
  journal={arXiv preprint arXiv:1911.10683},
  year={2019}
}
```
