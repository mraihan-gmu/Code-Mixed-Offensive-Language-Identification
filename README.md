# Code-Mixed-Offensive-Language-Identification
This is a dataset for the offensive language detection task. It contains 100k code mixed data. The languages are Bangla-English-Hindi.

### Dataset Generation:

Initially, the labelling schema of OLID[^1] and SOLID[^2] serves as the seed data, from which we randomly select 100,000 data instances. The labels in this dataset are categorized as Non-Offensive and Offensive for the purpose of our task. We meticulously ensure an equal number of instances for both Non-Offensive and Offensive labels. To synthesize the Code-mixed dataset, we employ two distinct methodologies: the *Random Code-mixing Algorithm* by Krishnan et al. (2021)[^3] and *r-CM* by Santy et al. (2021)[^4].

### Class Distribution:

#### For train.csv:

| Label | Count | Percentage |
|-------|-------|------------|
| NOT   | 40018 | 66.70%     |
| OFF   | 19982 | 33.30%     |

#### For dev.csv:

| Label | Count | Percentage |
|-------|-------|------------|
| NOT   | 13339 | 66.70%     |
| OFF   | 6661  | 33.30%     |

#### For test.csv:

| Label | Count | Percentage |
|-------|-------|------------|
| NOT   | 13340 | 66.70%     |
| OFF   | 6660  | 33.30%     |

### Cite our Paper:

If you utilize this dataset, please cite our paper.

```bibtex
@article{raihan2023mixed,
  title={Mixed-Distil-BERT: Code-mixed Language Modeling for Bangla, English, and Hindi},
  author={Raihan, Md Nishat and Goswami, Dhiman and Mahmud, Antara},
  journal={arXiv preprint arXiv:2309.10272},
  year={2023}
}
```

### References

[^1]: Zampieri, M., Malmasi, S., Nakov, P., Rosenthal, S., Farra, N., & Kumar, R. (2019). SemEval-2019 Task 6: Identifying and Categorizing Offensive Language in Social Media (OffensEval). In Proceedings of the 13th International Workshop on Semantic Evaluation (pp. 75–86). [https://aclanthology.org/S19-2010](https://aclanthology.org/S19-2010)

[^2]: Rosenthal, S., Atanasova, P., Karadzhov, G., Zampieri, M., & Nakov, P. (2021). SOLID: A Large-Scale Semi-Supervised Dataset for Offensive Language Identification. In Findings of the Association for Computational Linguistics: ACL-IJCNLP 2021 (pp. 915–928). [https://aclanthology.org/2021.findings-acl.80](https://aclanthology.org/2021.findings-acl.80)

[^3]: Krishnan, J., Anastasopoulos, A., Purohit, H., & Rangwala, H. (2021). Multilingual code-switching for zero-shot cross-lingual intent prediction and slot filling. arXiv preprint arXiv:2103.07792.

[^4]: Santy, S., Srinivasan, A., & Choudhury, M. (2021). BERTologiCoMix: How does code-mixing interact with multilingual BERT? In Proceedings of the Second Workshop on Domain Adaptation for NLP (pp. 111–121).

---
