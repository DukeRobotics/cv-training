# cv-training
Scripts to train computer vision models.

## Dependencies
Ensure that you have a CUDA-enabled GPU. Only Ubuntu 22.04 LTS is officially supported.

To create the `cv-train` [conda](https://docs.conda.io/projects/miniconda/en/latest/) environment, run:
```bash
conda create --name cv-train python=3.11
```
Select the `cv-train` kernel when executing any Jupyter Notebooks in this repository.

## Training
Use the [yolov7_tiny.ipynb](./yolov7_tiny.ipynb) Jupyter Notebook to train a YOLOv7-tiny model.

## CV Workflow
For a complete guide on our CV workflow, visit [Computer Vision Workflow](https://dukerobotics.github.io/wiki/#/computer_vision/workflow) on our wiki.