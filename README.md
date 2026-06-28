# Surface-Material-Classification
This project builds a computer vision system to classify surface materials from images using deep learning. Two independent training pipelines are developed across two benchmark datasets, the Flickr Material Dataset and MINC-2500, comparing custom CNN architectures against transfer learning using ResNet50 and MobileNetV2.
Each pipeline covers the full workflow: data loading, augmentation with flipping, rotation, and zoom to improve generalisation, model training, and systematic hyperparameter tuning. The two pretrained architectures are evaluated side by side to measure the advantage of transfer learning over training from scratch on material recognition tasks.
Both ResNet50 and MobileNetV2 achieved approximately 87% classification accuracy across material categories, consistently matching or outperforming the custom CNN baseline. The project demonstrates that pretrained feature extractors generalise well to domain-specific visual classification tasks even without large amounts of task-specific data.


Built with Python, TensorFlow, Keras, and Google Colab.
