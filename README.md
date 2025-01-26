 Dataset Description  

Dataset Name  
Rice Image Dataset  

 Source  
1. [Rice Image Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)  
2. [Rice Images Dataset](https://www.kaggle.com/datasets/shubhamcodez/rice-images-dataset)  

The datasets were sourced from Kaggle, an online platform that hosts diverse datasets for machine learning and deep learning projects. These datasets are publicly available for research and academic purposes and provide high-quality images of rice grains.  

Description  
The Rice Image Dataset is a comprehensive collection of high-resolution images of rice grains, carefully curated to aid in the development of machine learning models for classification, quality control, and defect detection. The dataset primarily focuses on five prominent rice varieties cultivated in Turkey:  

1. Arborio
2. Basmati  
3. Ipsala  
4. Jasmine  
5. Karacadag  

Additionally, the dataset includes three quality categories that highlight the condition of rice grains:  
- Full grains: Entire, intact rice grains.  
- Broken grains: Fractured or incomplete rice grains.  
- Mixed grains: A combination of full and broken grains.  

 Primary Dataset  
- Number of Images: 75,000  
- Classes: Five rice varieties (15,000 images per variety)  
- Purpose: Classification of rice varieties based on distinct visual characteristics like texture, color, and shape.  

Secondary Dataset  
- Number of Images: 4,237  
- Classes: Three categories (full, broken, mixed)  
- Purpose: Quality control and defect detection for applications in sorting and grading systems.  

The combination of these datasets ensures diversity and robustness, making them suitable for training sophisticated machine learning models.  

Data Structure  
The dataset is organized into separate folders for each category and subcategory. This structure ensures compatibility with standard image classification frameworks.  

 File Format  
- Image Format: JPG or PNG files, stored in high resolution.  

Preprocessing Steps  
To enhance model performance, the following preprocessing techniques were applied:  
1. Resizing: Images were resized to a uniform dimension of 224x224 pixels to meet the input requirements of deep learning models like EfficientNet.  
2. Normalization: Pixel values were normalized to the range [0, 1] to improve training stability and convergence.  
3. Data Augmentation: Techniques like random rotations, horizontal flips, zooming, and cropping were employed to artificially expand the dataset and improve the model's ability to generalize.  

Usage  
The dataset plays a critical role in building and validating machine learning models for rice grain classification and quality assessment. Its applications include:  
- Automated Quality Control: Ensures accurate sorting and grading of rice grains in agricultural and industrial settings.  
- Inventory Management: Helps in maintaining consistent quality standards across batches.  
- Fair Pricing: Aids in determining market value based on the variety and condition of rice grains.  
- Real-Time Applications: Can be integrated into automated sorting systems for real-time defect detection and classification.  

In this project, the dataset was used to train an EfficientNet-B0 model with PyTorch, leveraging transfer learning to achieve high performance. The model achieved over 99% accuracy on validation data, showcasing its effectiveness in handling high-dimensional image data.  

Licensing  
The dataset adheres to the licensing policies specified on Kaggle. Users are advised to review and comply with these terms before using the dataset for any commercial purposes. The dataset is primarily intended for research and educational use.  

 References  
1. [Rice Image Dataset on Kaggle](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)  
2. [Rice Images Dataset on Kaggle](https://www.kaggle.com/datasets/shubhamcodez/rice-images-dataset)  



