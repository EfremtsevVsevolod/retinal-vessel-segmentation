# Digital Breakthrough 2022. All-Russian championship
The championship task is to develop a semantic segmentation model of the human eye capillaries based on images from an ophthalmological slit lamp. This model should help in the vessel recognition of the eye. With its help, medical professionals will be able to concentrate as much as possible on the analysis of measurement results without wasting time on data processing.

**Place according to [championship results](https://hacks-ai.ru/championships/758465 ): `11 of 1556' 🏆 🏆 🏆 - [certificate](https://github.com/EfremtsevVsevolod/retinal-vessel-segmentation/blob/main/certificate.pdf)**

## Data
* Training dataset: https://lodmedia.hb.bizmrg.com/case_files/815459/train_dataset_mc.zip
* Test dataset: https://lodmedia.hb.bizmrg.com/case_files/815459/test_dataset_mc2.zip

## Brief description of the solution:
1. At the first step, perform preprocessing of the eye images to improve the prediction quality.
2. At the second step, perform capillary segmentation.
3. Based on the neural network predictions, determine whether each specific pixel is part of the capillary or not.

## Technical Features:
* Python, PyTorch, UNet, VGG16
* Computer vision, Image segmentation, Medical images, Retina vessel segmentation
