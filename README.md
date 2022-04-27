# Deep-Learning
The assignments for AIST4010 Foundation of Applied Deep Learning, which are Kaggle competitions on image, sequence and graph tasks.

## Tasks:
Table 1. Topic and competition result of different tasks

| Task     | Topic | Evaluation Metric | Public Result | Private Result |
| -----     | -----     | -----       | -----       | -----       |
| 0 | IRIS Classification | Mean F1-Score | 1.00000 | 1.00000 |
| 1 | Face Classification | Accuracy | 0.88440 | 0.89021 |
| 2 | Antibiotic Resistance Genes Prediction | Macro F1-Score | 0.99018 | 0.96393 |
| 3 | Graph Node Classification | Accuracy | 0.80386 | 0.78934 | 

## Packages Imported:
- To install package, type the following command in a terminal:
```bash
pip install <package_name>
```

### General Packages:
1. numpy: scientific computations
2. pandas: importing and exporting data from / to csv
3. matplotlib: graph plotting
4. sklearn: machine learning algorithms, data preprocessing, evaluation metrics
5. natsort: sorting of list data
6. torch: deep learning related algorithms

### Specific Packages for Task 1:
7. torchvision: dataset and data augmentation for images
8. facenet_pytorch: pre-trained Inception Resnet v1 model on face dataset

### Specific Packages for Task 2:
9. Bio: loading protein sequence data
10. transformers: pretrained BERT model on protein dataset and trainer

### Specific Packages for Task 3:
11. torch_geometric: graph neural network algorithms

## Files:
1. aist4010-asm\<N\>.ipynb
	- Code of the method used in Task N

2. AIST4010 Assignment \<N\>.pdf
	- Specification of Task N

## Output:
1. output.csv
	- Output file of the code

2. aist4010-spring2022-a\<N\>-publicleaderboard.csv
	- The public leaderboard used to select the best model for Task N

3. aist4010-spring2022-a\<N\>-privateleaderboard.csv
	- The private leaderboard used to determine the rank of Task N

## Achievement:
- 2nd place (out of 28 teams) in Task 1
- 1st place (out of 31 teams) in Task 2
- 2nd place (out of  8 teams) in Task 3

© 2022 Andes Kei
