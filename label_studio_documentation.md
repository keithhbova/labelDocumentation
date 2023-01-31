# Label Studio Documentation:



## Labeling Data With Semantic Segmentation, Using Label Studio:

After creating a new project, go to labeling setup, and select "Semantic Segmentation With Polygons:"






Insert these classes, and click add:





When you export (unless you're immediately using your data for training), make sure to select "JSON", label studio's common format. We do this because it's easy to import back into label studio:




This makes it easy to gather data from everyone--if everyone has an instance of label studio installed on their own machine. Whoever is training the model can gather all the json exports, import them back into label studio, and export as "COCO" for training:


