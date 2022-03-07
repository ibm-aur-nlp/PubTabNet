# ICDAR 2021 Challenge task b test set

1. `final_eval.zip` contains the images of the tables
2. `final_eval.json` contains the ground truth used in the evaluation of the challenge. The ground truth did not include `b` tags that typically highlight text in bold. This was considered during the evaluation of the challenge. If you use the TEDS tools to evaluate your output, please consider the option `ignore_nodes` as in the following example `teds = TEDS(n_jobs=args.threads, ignore_nodes='b')`.

ICDAR 2021 Challenge journal article:

`
@inproceedings{jimeno2021icdar,
  title={ICDAR 2021 Competition on Scientific Literature Parsing},
  author={Jimeno Yepes, Antonio and Zhong, Peter and Burdick, Douglas},
  booktitle={International Conference on Document Analysis and Recognition},
  pages={605--617},
  year={2021},
  organization={Springer}
}
`

PubTabNet article
`
@inproceedings{zhong2020image,
  title={Image-based table recognition: data, model, and evaluation},
  author={Zhong, Xu and ShafieiBavani, Elaheh and Jimeno Yepes, Antonio},
  booktitle={European Conference on Computer Vision},
  pages={564--580},
  year={2020},
  organization={Springer}
}
`
