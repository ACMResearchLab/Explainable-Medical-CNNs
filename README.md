# Utilizing Segment Anything Model for Assessing Localization of GRAD-CAM in Medical Imaging
The introduction of saliency map algorithms as an approach for assessing the interoperability of
images has allowed for a deeper understanding of current black-box models with Artificial Intelligence.
Their rise in popularity has led to these algorithms being applied in multiple fields, including medical
imaging. With a classification task as important as those in medical domain, a need for rigorous testing
of their capabilities arises. Current works examine capabilities through assessing the localization
of saliency maps upon medical abnormalities within an image, through comparisons with human
annotations. We propose utilizing Segment Anything Model (SAM) to both further the accuracy of
such existing metrics, while also generalizing beyond the need for human annotations. Our results
show both high degrees of similarity to existing metrics while also highlighting the capabilities of this
methodology to beyond human-annotation. Furthermore, we explore the applications (and challenges)
of SAM within the medical domain, including image pre-processing before segmenting,natural
language proposals to SAM in the form of CLIP-SAM, and SAM accuracy across multiple medical
imaging datasets.

![test](images/SAMAUCJuddDist.png)
