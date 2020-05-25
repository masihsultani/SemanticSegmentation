# SemanticSegmentation

A quick project on semantic segmentation with Flower Dataset. We build and traina UNet model, and with only 80 images per flower, we achieve mIOU of 0.88. Looking at the loss graph, training has not converged after 100 epochs so theres potential for increasing learning rate or training for longer. Next steps are to apply the model to Cityscapes dataset or Pascal Voc dataset
