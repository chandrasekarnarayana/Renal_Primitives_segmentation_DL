# Renal Histologic Primitives Segmentation

We considered Three histologic primitives
1.)Glomeruli unit
2.)Proximal Tubular
3.)Distal Tubular

Methodology of implementation 
1.	The data needed to train the model was selected from the NEPTUNE dataset. 
2.	The data under consideration is PAS stained slides with annotation of Three histologic primitives of consideration: Glomeruli unit, Proximal Tubules, Distal Tubules.
3.	Patch extraction was done and compiled into Training and Validation sets in PyTable format.
4.	Using the Dataloader class in the program the training and validation files were loaded along with data augmentation.
5.	Training and validation were performed on the loaded data for the said epoch of each model on the U-Net architecture.
6.	The model with highest accuracy was considered the best and save along with its parameters
7.	The save model was used to obtain the segmented output

The Dataset is avilable at http://haeckel.case.edu/data/KI_data/

