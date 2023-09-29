# Deep neural networks in structural health monitoring

In my work I compared deep learning models for image segmentation task (Unet, Attention-Unet,Transunet) in concrete crack detection, developed crack measurement algorithm and created public dataset for similar use case.

Crack measurement algorithm is based on image processing, it was tested on  SDNET2019 images and laboratory images of high resoultion 4000x6000.

Satisfactory results have been achieved, my work shows modern approach to SHM with use of deep learning methods
<p align="center">
<img src="https://user-images.githubusercontent.com/37275864/188509212-1f366011-7884-48df-ac56-633b8386bd93.PNG" alt="lab-img-1" width="800"/>
</p>

Measuring crack in real units is done by palcing reference object which dimentions are known - here checkboard 9x13 with size of one check 20mm was used.
Points of checkboard are localized in the image, horizontal distance between two nearest points are calculated in pixels, then px/mm ratio is calculated by obtaining mean value from measurements

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

## Dataset
For dataset nagivate to https://www.kaggle.com/datasets/jakubniemiec/concrete-crack-images

## Sample images
<p align="center">
<img src="https://user-images.githubusercontent.com/37275864/188509208-44dd8b9d-59bb-47cc-8eff-e4fdee49b6d9.png" alt="sample-measurement" width="600"/>
</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/37275864/188509209-216d35cb-17c9-4866-9b18-b49c2c56a847.png" alt="segmentation-results" width="600"/>
</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/37275864/188509217-e116d151-e834-4dd9-982a-2512423137d6.png" alt="lab-img-2" width="800"/>
</p>
