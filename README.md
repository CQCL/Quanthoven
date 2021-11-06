# Code and resources for Quanthoven

This repository holds the code and the datasets for the paper:

- Miranda, Yeung, Pearson, Meichanetzidis, Coecke (2021). *A Quantum Natural Language Processing Approach to Musical Intelligence*

This paper pioneers a Quantum Natural Language Processing approach to classifying music. Using this quantum classifier we use a generate and test approach to generate quantum music. This is a proof of concept, but as quantum devices improve in size and fidelity we will be able to learn a quantum classifier that would be hard to simulate on a classical device.

# Contents

- `audio` contains computer-rendered recordings for the dataset.
- `compositions` contains the scores and professional recordings for selected compositions generated by the model.
- `datasets` contains the train / development / test set used for our experiment. The generation methodology is described in the paper.
- `experiment.ipynb` contains the pipeline described in Fig 9. of the paper, which is used used to learn the dataset.

## Code requirements

For running the code, you will need Python 3.7 or later. Further, the following packages must also be installed:

* `discopy` (v0.3.7.1)
* `lambeq` (v0.1.2)

## Links

For further help see: 

* for `discopy`: https://discopy.readthedocs.io/en/main/index.html
* for `lambeq`: https://cqcl.github.io/lambeq/
