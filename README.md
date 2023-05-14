# DimentiaDetection

Link to Drive (files too big to upload to github so you can't run the code outside of it):
https://drive.google.com/drive/folders/1uJmWYuDnOXFJHl1SGbIppyyMHM9K-l8j?usp=sharing
(Note only BC accounts can open the link)

## Running the Models
- Run the first 2 blocks in "ResNet" section
- Run the first 4 clocks in "Alexnet" section
- Run the only block in "Load Models" section
At this point you have all 4 models (Resnet, VGG16, Inception-V3, Alexnet) availible to use

## Running GradCam
- Run through all the blocks in this section
- When you get to the last section here are instructions on how to use the interactive demo:
  1. First select a model to use (you will get an error if you don't select one first)
  2. From here you can select a level of dimentia to get a heatmap for.  It selects a random example every time so you can keep doing this to see multiple examples for a model/level of dimentia combo.
  3. No need to rerun this block! At this point you can switch back and forth between which model you are using and what level of dimentia is being displayed.
- Side note: VGG16 produced the worst accuracies so the heatmaps are not as good as the others.  We just thought this contrast was interesting so worth incorporating so we can see how improved accuracies lead to better heat maps.

## Running Fake Image Generation
- For simplicity you can skip the "mild", "very mild", "moderate", and "none" sections in this part unless you want to see the progress the training loop made while generating the images.
- All our saved progress is in the "Test model on fakes" section, so you can run through that to see our results.
