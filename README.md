
# Image Captioning using Deep Learning

## Idea for the project: 
Generating captions using the model, which can then be converted into speech with a text-to-speech library, aids visually impaired individuals in comprehending the content of an image through auditory means.

## Tech Stack: 
- Tensorflow
- Tkinter
- pandas
- numpy
- pickle
- PIL

## Dataset used:
Flickr_30k: https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset

## Implementation:
1. Preparing the data
2. Preprocessing data
3. Building vocabulary
4. Build and train the model
5. Generating captions using beam search and greedy search
6. Calculating the bleu score

## How to run this project?
1. Clone the entire repository in a new folder. 

2. Download and save the flickr_30k dataset onto the data folder with the image folder named as Images and the captions data stored as results.csv

3. Run the **_flickr_30k_image_captioning.ipynb** file.

4. **_datasets_dict.pickle_** stores the image name with corresponding captions.
And **_captions_data.pickle_** stores all the captions for later use.

5. Once the training stage is reached, the same code can be run more times depending upon the number of epochs you want to train your data on. 

**NOTE:** This step could take some time depending upon the machine where your are running this. 
Taking about 10 minutes per epoch running on a GPU. 

6. To use the gui for this, run the **_GUI code.ipynb_** file and use the trained weights here to generate captions for the image and convert these into speech. 


