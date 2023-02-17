# Label Studio Documentation:

## How to install label studio:

### Note: You need Python 3.7 or later to be able to install label studio on either a windows computer or a Mac. 

### For Windows users: 

1. Download Anaconda Installer (https://docs.anaconda.com/anaconda/install/windows)
2. On your search menu, type anaconda and get the following prompt 

3. Creating a python environment. On the console: (this step is optional) 
    - conda create -- name label studio pip 
    - y to accept 
    - activate label studio (enter the environment) 
        -deactivate (for leaving) 
     
4. Getting label studio ( this will take a bit of time) 
    -pip install label-studio 
    
5. Launching label studio: 
label-studio start 
    -label-studio (this is going to open label studio on internet browser) 
    
### For Mac users: 

1. We will be installing label studio, so open your terminal and type the following: 
        pip install label-studio 
    
2. After you install label studio, start the server with the following command (this is going to open label studio on internet browser): 
        label-studio 
## Setting up a project with Semantic Segmentation, Using Label Studio:

### After creating a new project, go to labeling setup, and select "Semantic Segmentation With Polygons:"


<img src="/assets/polygon_image.png" alt="Alt text" title="Optional title">



### Insert these classes, and click add:

<img src="/assets/add_classes_image.png" alt="Alt text" title="Optional title">


## Labeling Instructions:

add instructions


## Exporting a project, using label studio for collaboration:

### When you export (unless you're immediately using your data for training), make sure to select "JSON", label studio's common format. We do this because it's easy to import back into label studio:

<img src="/assets/export_json_image.png" alt="Alt text" title="Optional title">


### This makes it easy to gather data from everyone--if everyone has an instance of label studio installed on their own machine. Whoever is training the model can gather all the json exports, import them back into label studio, and export as "COCO" for training:

<img src="/assets/export_coco_image.png" alt="Alt text" title="Optional title">
