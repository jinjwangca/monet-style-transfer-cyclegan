**Dataset link:**
- [https://www.kaggle.com/c/histopathologic-cancer-detection/data](https://www.kaggle.com/competitions/gan-getting-started/data)

**Dataset Overview:**

The dataset includes both JPEG and TFRecord formats and is structured as follows:

- monet_jpg: 300 Monet-style paintings in JPEG format
- monet_tfrec: 300 Monet-style paintings in TFRecord format
- photo_jpg: 7,028 real-world landscape photos in JPEG format
- photo_tfrec: 7,028 real-world landscape photos in TFRecord format

Each image is 256x256 pixels. The dataset is unpaired, meaning there are no direct Monet-photo image pairs. For this implementation, I use the JPEG images due to their accessibility and ease of visualization.
