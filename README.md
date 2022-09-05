# master's thesis: Deep neural networks in structural health monitoring

In my work I compared deep learning models for image segmentation task (Unet, Attention-Unet,Transunet) in concrete crack detection, developed crack measurement algorithm and created public dataset for similar use case.


Crack measurement algorithm is based on image processing, it was tested on  SDNET2019 images and laboratory images of high resoultion 4000x6000.

Satisfactory results have been achieved, my work shows modern approach to SHM with use of deep learning methods

## Files
```python
src/transunet_model_train.ipynb
```
Shows the way models were trained, the same approach and metrics were used for Unet/Attention Unet training

```python
src/all_models_measurement.ipynb
```
Crack measurement comparision for all considered models

```python
src/crack_measurement_function_step_step_by_step.ipynb
```
Crack measurement function explained step-by-step

```python
src/measure_high_res_photos.ipynb
```
Crack detection and crack measurement for high resolution image

## Sample images

## Dataset
For dataset nagivate to https://www.kaggle.com/datasets/jakubniemiec/concrete-crack-images
