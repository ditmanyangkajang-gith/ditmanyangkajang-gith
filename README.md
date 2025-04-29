Name: Abraham Dit Manyang
Index: 18-CIT-001
Department: IT

Approach:

1. Data Loading and Preparation,
2. Image Augmentation using ImageDataGenerator,

For each type of animal (and in Step 4, a general example), a specific ImageDataGenerator is configured with different augmentation parameters:
Step 4 & 5 (Buffalo): Rotations (0-30 degrees), horizontal and vertical flips are applied.
Step 6 (Zebra): Width and height shifts (0.05-0.15) are used.
Step 7 (Rhino): Similar to Zebra but with width/height shifts of (0.1-0.15).
Step 8 (Elephant): Random brightness adjustments between 0.05 and 2.5 are applied.
The flow method of ImageDataGenerator is used to generate augmented images on the fly, one at a time.
3. Visualization



  Overall Strategy

In essence, my code uses a systematic approach to create diverse augmented images:

Load and prepare images.
Configure ImageDataGenerator with specific augmentation settings for each animal.
Generate and visualize the augmented images
<!---
ditmanyangkajang-gith/ditmanyangkajang-gith is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
