# QRQA

Error analysis using question rewrites for conversational question answering. Supplementary materials for "A Wrong Answer or a Wrong Question?.." https://www.aclweb.org/anthology/2020.scai-1.2.pdf

## Requirements

* altair
* rouge_score

## Input

query_metrics file is generated from a TREC run file using:

`grep '^map\s\|recip_rank\|^P_1\|^P_3\|ndcg_cut_1\|ndcg_cut_3\|ndcg_cut_5' original.run | grep -v "all" > original_query_metrics.txt`

## Citation

Please cite our [paper](https://www.aclweb.org/anthology/2020.scai-1.2/) if you found these resources useful.

```bibtex
@inproceedings{vakulenko2020wrong,
  title={A Wrong Answer or a Wrong Question? An Intricate Relationship between Question Reformulation and Answer Selection in Conversational Question Answering},
  author={Vakulenko, Svitlana and Longpre, Shayne and Tu, Zhucheng and Anantha, Raviteja},
  booktitle={Proceedings of the 5th International Workshop on Search-Oriented Conversational AI (SCAI)},
  pages={7--16},
  year={2020}
}
```
