# Fishnet

## Ideas

Overall Project
 - Shark Identification from video of rays in irish seas
 - Development of Shark Model once identified using morphable models
  
CURRENT TASK:
    - Why is labelled video slow?
    - Why is labelled video wrong color?
    - Why is the labelling so wrong?
    - Develop model with 0.8 accuracy (Relabel, more label and other features)
    - Segment Sharks with Mask CNN
    - Track each Shark in video for morphable model
    - Setup Jupyter Notebook for Creating Morphable Models
  
TODO:
 - Develop it for many species
 - Build Morphable Model
 - Create Shark model based on video which it is identified in
 - Build UI for application in a website

Ideas:

Use Mask R-CNN to trace shark in image
TARGET: 53,345 Images of Sharks 
        219 Species of Shark
        47 species pertaining to 26 genera

        DATA GATHERING: Images sourced from:
        - Instagram with 91% accuracy (Data Mining)
        - BRUVs

DONE
- Setup Virtual Environment with Tenserflow
- Setup Jupyter Notebook
- Setup Jupyter Notebook for Installation
- Setup Jupyter Notebook for Image Collection
- Collect Images of Sharks for 20 species
- Setup Jupyter Notebook for Training and Shark Detection
- Do Postamble for shark videos (identify shark for each frame code) on training data (3 videos) + test data (1 video) for 3 species of shark

## Installation Process

## Running the code

1. Open Terminal 
2. cd to Shark-Species-Identifier folder
3. Activate virtual environment ```.\identificationSystem\Scripts\activate```
4. Start jupyter notebooks ```jupyter notebook```