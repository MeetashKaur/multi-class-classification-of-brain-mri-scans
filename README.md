# multi-class-classification-of-brain-mri-scans
Objective : - To classify the brain mri scans into four different classes: - glioma tumor, meningioma tumor, pituitary tumor and no tumor class.
I have used transfer learning concept. To extract the relevant features from the MRI scans, I have applied pre-trained VGG16 model.
Fo the final classification, extracted features are given to random forest classifier.
Pre-processing steps performed: -
1. Resizing.
2. Intensity normalization.
3. Cropping of images.
4. Denoising using bilateral filter.
