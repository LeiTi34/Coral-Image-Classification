# Healthy and Bleached Corals Image Classification

## Dataset

[The Dataset](https://www.kaggle.com/datasets/vencerlanz09/healthy-and-bleached-corals-image-classification/data), sourced from Kaggle, contains 923 images collected from Flickr of bleached (485 images) and healthy corals (438 images) and is curated to classify the images into healthy and bleached corals.

### Goal and Motivation

By creating accurate classification models, researchers and marine biologists can better understand the health and well-being of coral reefs, monitor changes in their environment, and contribute to the conservation and restoration of these vital ecosystems.

Conservation organizations can use the tool to regularly assess the health of coral reefs. By analyzing images from various locations, they can identify areas experiencing bleaching and prioritize conservation actions.

### SDG 14 - LIFE BELOW WATER

<div style="text-align: center;">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Sustainable_Development_Goal_14LifeBelowWater.svg" alt="SDG14" width="300">
    <img src="https://globalgoalscms.co.uk/wp-content/uploads/2021/09/globalgoals_636df7a3-ede0-49f2-8078-bc9bcdfa9f1b_goal_14.5_rgb_ng.svg" alt="SDG14" width="300">
</div>

## Project

The project consists of different jupyter notebooks, which are using different deep learning models to classify the images into healthy and bleached corals.

Used models:

- [MobileNetV2](./MobileNet-Coral-Image-Classification.ipynb)
- [VGG16](./VGG16-BN-Corals-Image-Classification.ipynb)
- [ResNet50](./ResNet50.ipynb)
- [InceptionV3](./InceptionV3.ipynb)

The reports for MobileNetV2 are included in the notebook itself, ResNet50 and InceptionV3 are in separate PDF files.

- [MobileNetV2](./MobileNet-Coral-Image-Classification.ipynb)
- [VGG16](./VGG16-BN-Corals-Image-Classification.ipynb)
- [ResNet50](<./ResNet50 Report.pdf>)
- [InceptionV3](<./ResNet50 Report.pdf>)

### Running the Notebooks

To run the notebooks use a jupyter environment of your choice.
MobileNetV2 and VGG16 are trained using the jupyter server in the [docker-compose.yml](./docker-compose.yml) file, ResNet50 and InceptionV3 are trained using [GPU Hub](https://gpuhub.labservices.ch).
