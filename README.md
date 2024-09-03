# Project Overview

This project involves the development of two Pix2Pix models designed to translate between infrared (IR) and visible light images. The primary objective was to explore the potential correlation between these two types of images, hypothesizing that certain visible characteristics (like bright spots or red shades) might correspond to thermal signatures in the IR spectrum.

## Hypothesis

The underlying hypothesis was that there exists a discernible pattern or fundamental rule connecting IR images with their visible counterparts. For example, it was speculated that areas of heat in IR images might directly correlate with specific color intensities or patterns in visible light images.

## Methodology

The dataset used for this experiment consists of approximately 12,000 paired images of IR and visible light spectrums, taken from the [LLVIP dataset](https://bupt-ai-cz.github.io/LLVIP/). Two separate Pix2Pix models were trained:
1. **IR to Visible Image Translation**
2. **Visible to IR Image Translation**

These models were expected to identify and learn any potential correlations between the two image types during the training process.

## Results and Conclusion

Upon evaluating the models' performance and analyzing the output, the results were significantly divergent from the expected correlations. The predicted images from both models did not align with their respective ground truths, indicating a lack of consistent patterns between the IR and visible datasets as hypothesized.

This outcome suggests that there is no straightforward or inherent rule that can predict the IR version of an image based solely on its visible spectrum representation, and vice versa. Therefore, the initial hypothesis that visible light features could directly inform or predict infrared characteristics was not supported by the experimental data.

## Dataset

The dataset used in this project is taken from the [LLVIP dataset](https://bupt-ai-cz.github.io/LLVIP/).
