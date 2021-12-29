# Activity Recognition from Egocentric Photo-Streams
Project to recognize human activities from egocentric perspective.  
Pre-trained models are exploited for the recognition.

Check [README.md](https://github.com/MorphSeur/EgocetricPhotostreams/tree/master/archive/README.md) located in archive for more details.

## Pre-trained Models
Download the folder with the pre-trained models from this [link](https://mega.nz/folder/I2xWRDqJ#dmJO1LfzCqAY20iO6yndMA).

## Requirements
Please refer to [requirements.txt](https://github.com/MorphSeur/EgocetricPhotostreams/blob/master/requirements.txt).

## Notebook
### 25122021.ipynb
- Cell splits the input video located in ./input/ to frames stored ./input/frame/.  
- Cell read frame by frame located in ./input/frame/, predict labels, put predicted labels in the dedicated frame as text.  
- Cell read the recognized frames located in ./input/frame/ and build video stored in ./output.

## Issues
Unable to find the correct tensorflow-gpu and keras versions.  
Some pre-trained models are not well trained.  
Maybe retrain the models.