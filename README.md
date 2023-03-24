### How Data Scientists Review the Scholarly Literature

Repository accompanying paper: 

**Title**: "How Data Scientists Review the Scholarly Literature"

**Authors**: Sheshera Mysore, Mahmood Jasim, Haoru Song, Sarah Akbar, Andre Kenneth Chase Randall, Narges Mahyar at the University of Massachusetts Amherst, USA.

**Abstract**: Keeping up with the research literature plays an important role in the workflow of scientists - allowing them to understand a field, formulate the problems they focus on, and develop the solutions that they contribute, which in turn shape the nature of the discipline. In this paper, we examine the literature review practices of data scientists. Data science represents a field seeing an exponential rise in papers, and increasingly drawing on and being applied in numerous diverse disciplines. Recent efforts have seen the development of several tools intended to help data scientists cope with a deluge of research and coordinated efforts to develop AI tools intended to uncover the research frontier. Despite these trends indicative of the information overload faced by data scientists, no prior work has examined the specific practices and challenges faced by these scientists in an interdisciplinary field with evolving scholarly norms. In this paper, we close this gap through a set of semi-structured interviews and think-aloud protocols of industry and academic data scientists (N = 20). Our results while corroborating other knowledge workers' practices uncover several novel findings: individuals (1) are challenged in seeking and sensemaking of papers beyond their disciplinary bubbles, (2) struggle to understand papers in the face of missing details and mathematical content, (3) grapple with the deluge by leveraging the knowledge context in code, blogs, and talks, and (4) lean on their peers online and in-person. Furthermore, we outline future directions likely to help data scientists cope with the burgeoning research literature.

:page_facing_up: Arxiv pre-print: https://arxiv.org/abs/2301.03774

:memo: A twitter thread: https://twitter.com/MSheshera/status/1613388613126963203 

:blue_book: Paper as published by ACM: https://dl.acm.org/doi/10.1145/3576840.3578309 

### Repository Contents

```
├── README.md
├── codes-extended-quotes-themes.md
└── coding-iterations
    ├── README.md
    ├── round01-all-codes-annotated.md
    ├── round01-all-codes-sorted.txt
    ├── round02-all-codes-documented.md
    ├── round02-all-codes-sorted.txt
    └── round03-all-codes-sorted.txt
```

This repository contains the materials resulting from the qualitative analysis of 20 participant data scientists: codes resulting from 3 rounds of coding and quotes by participants organized into the themes reported in the paper:

- `codes-extended-quotes-themes.md`: Contains anonymized participant quotes beyond those possible to include in our paper - organized into the themes discussed in the paper.
- `coding-iterations/`: Contains documented codes from 3 rounds of qualitative coding.

### Citation

```bibtex
@inproceedings{mysore2023dslitreviews,
	author = {Mysore, Sheshera and Jasim, Mahmood and Song, Haoru and Akbar, Sarah and Randall, Andre Kenneth Chase and Mahyar, Narges},
	title = {How Data Scientists Review the Scholarly Literature},
	year = {2023},
	isbn = {9798400700354},
	publisher = {Association for Computing Machinery},
	address = {New York, NY, USA},
	url = {https://doi.org/10.1145/3576840.3578309},
	doi = {10.1145/3576840.3578309},
	pages = {137–152},
	numpages = {16},
	location = {Austin, TX, USA},
	series = {CHIIR '23}
}
```