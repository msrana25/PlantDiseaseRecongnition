# Plant Disease Classification Using Deep Learning

Academic research project from COMP 6721 - Concordia University (2023)

## Overview
Developed and evaluated three CNN architectures (MobileNet-v2, ShuffleNet, ResNet-18) for 
automated plant disease detection using image classification on 40,000+ labeled plant leaf images.

## My Contributions (Manpreet Singh Rana)
- **Model Development**: Trained 3 MobileNet-v2 models from scratch, achieving 94% accuracy 
  (Dataset 1) and 93% accuracy (Dataset 2)
- **Transfer Learning**: Implemented transfer learning techniques on MobileNet-v2 for Dataset 2 
  to improve convergence and performance
- **Dimensionality Reduction**: Conducted t-SNE analysis on both datasets to visualize feature 
  distributions and validate model learning
- **Documentation**: Authored primary sections of research report and coordinated team deliverables

## Technical Stack
- **Languages**: Python
- **Frameworks**: PyTorch, torchvision
- **Tools**: Google Colab (GPU), Kaggle datasets
- **Techniques**: CNN training, transfer learning, data augmentation, t-SNE visualization

## Datasets
- **Dataset 1**: 1,530 images (Healthy, Powdery, Rust) - 4000x2672 pixels
- **Dataset 2**: 15 classes (tomato, potato, pepper diseases) - 256x256 pixels
- **Dataset 3**: 40K images, 23 classes (augmented dataset)

## Results
| Model | Dataset 1 Accuracy | Dataset 2 Accuracy |
|-------|-------------------|-------------------|
| MobileNet-v2 | 94% | 93% |
| ShuffleNet | 92% | 90% |
| ResNet-18 | 99.95% | 96.4% |

## Key Learnings
- Addressed overfitting through hyperparameter tuning (reduced epochs from 25 to 12)
- Optimized training pipeline by migrating from local CPU to GPU-accelerated environment
- Balanced model complexity with computational efficiency for agricultural deployment scenarios

## Notebooks
- `MobileNet_Dataset1.ipynb` - Training on Dataset 1
- `MobileNet_Dataset2_TransferLearning.ipynb` - Transfer learning implementation
- `TSNE_Analysis.ipynb` - Dimensionality reduction visualizations

## Acknowledgments
Collaborative project completed as part of COMP 6721 coursework at Concordia University.

Original team repository: https://github.com/prvnsingh/PlantDiseaseRecongnition

## Contact
Manpreet Singh Rana - [LinkedIn] https://www.linkedin.com/in/manpreet-singh-rana-8990bb14b/ | [Email] rsingh.manpreet@gmail.com
```

--
