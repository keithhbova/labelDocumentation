# Label Studio Documentation:

## How to install label studio:

### Note: You need Python 3.7 or later to be able to install label studio on either a windows computer or a Mac. 

### For windows users: 


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
