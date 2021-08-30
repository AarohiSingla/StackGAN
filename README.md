# StackGAN

# Synthesizing high-quality images from text descriptions

To understand the code, Check video: https://youtu.be/ye6pYwBQQL4

### Create 3 folders (test, weights,results_stage2) in your current working directory.
1. <b>weights </b> (your model weights will be saved here)
2. <b>test </b> (generated images from our stage I StackGAN)
3. <b>results_stage2 </b> will have the generated images from stage2 fo StackGAN

## About Dataset

#### Dataset Name: Caltech-UCSD Birds-200-2011

Download from : http://www.vision.caltech.edu/visipedia/CUB-200-2011.html

#### Text Embedding Model
Download char-CNN-RNN text embeddings for birds from : 

https://drive.google.com/file/d/0B3y_msrWZaXLT1BZdVdycDY5TEE/view?resourcekey=0-sZrhftoEfdvHq6MweAeCjA
or 
https://github.com/hanzhanggit/StackGAN

1. char-CNN-RNN-embeddings.pickle — Dataframe for the pre-trained embeddings of the text.
2.  filenames.pickle — Dataframe containing the filenames of the images.
3. class_info.pickle — Dataframe containing the info of classes for each image.
