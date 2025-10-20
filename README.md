# Semantic Segmentation Using Deep Learning for Wildlife Detection
# Dataset
We used the Animal Kingdom dataset, which includes photos and videos of animals. This dataset is divided into three parts; for our custom dataset, we utilized the section containing photos. Initially, we processed these images with the Segment Anything Model (SAM) to generate masks for each image. We then used CVAT.ai to annotate the 10,000 images. In conclusion, we have 10,000 images with their corresponding masks and have generated 10,000 newly annotated masks.
Additionally, a customized dataset was created and prepared for further use.

Download it from here : https://sutdcv.github.io/Animal-Kingdom

For our customized dataset is not available for everyone.

# Models
We used three models: the Segment Anything Model (SAM), SegFormer, and U-Net. These models were fine-tuned using our custom dataset.

# Code

## For SAM:
- Provide the path to your finalized images, which must be in the format `(num_images, height, width, num_channels)`.
- Provide the path to your finalized masks, which must be in the format `(num_images, height, width)`.

## For U-Net:
- Provide the path to your finalized images and masks.
