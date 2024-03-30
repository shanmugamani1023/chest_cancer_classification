# chest_cancer_classification using MLflow,DVC
Chest cancer classification involves categorizing abnormalities in the chest, typically the lungs, based on imaging tests and biopsies to determine if they are cancerous and, if so, what type of cancer it is.

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml

## Here we are using VGG16 Architechture
![alt text](images/conv-layers-vgg16.jpg)



MLFLOW_TRACKING_URI=https://dagshub.com/shanmugamani1023/chest_cancer_classification.mlflow \
MLFLOW_TRACKING_USERNAME=shanmugamani1023 \
MLFLOW_TRACKING_PASSWORD=ebcdc7e28d18cdbe20cf5ca02e147e06d360e06c \
python script.py




