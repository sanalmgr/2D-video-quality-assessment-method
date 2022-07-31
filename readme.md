## CNN-based no-reference video quality assessment method using a spatiotemporal saliency patch selection procedure
We propose a yet lightweight no-reference (NR) video quality assessment (VQA) method, which uses a convolution neural network (CNN) architecture. The proposed method implements a spatiotemporal saliency patch selection procedure that crops the frame into small nonoverlapping blocks of images (patches) and selects the most perceptually relevant ones. The selected patches are then forwarded to the CNN. To determine which patches are the most relevant, spatial and temporal saliency features are computed for each frame. The proposed method does not require subjective scores to train the CNN. It uses objective quality scores as target quality scores for each video frame, which are computed using an NR image quality assessment method. Given the lack of large annotated video quality databases, this is an advantage of the proposed method. [Paper](https://www.spiedigitallibrary.org/journals/journal-of-electronic-imaging/volume-30/issue-6/063001/CNN-based-no-reference-video-quality-assessment-method-using-a/10.1117/1.JEI.30.6.063001.short?SSO=1)

## CNN Model: 
[VSBIQA Network](https://github.com/JayMarx/VSBIQA)

## Code to generate selected number of frames:
Downsampling:
[part 1](https://www.youtube.com/watch?v=C0sSA508zBc)
[part 2](https://www.youtube.com/watch?v=yuHxokzIh5U), and 
[part 3](https://www.youtube.com/watch?v=D6ROERxx25I)

## Requirements
- Python
- Chainer
