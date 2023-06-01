## Downloading images from Open Images using the FiftyOne tool
---
> **Note** This repository has been archived.

A Jupyter notebook, describing the selection, downloading, and saving of images from **Open Images** in a certain format using the **FiftyOne** tool.
### Overview:
---
The objective is to download images of the required classes from Open Images and save them in the ImageClassificationDirectoryTree format (see below) using [FiftyOne](https://voxel51.com/docs/fiftyone/) tool:
```
image_store_dir/
    train/
        class1_name/
            image1.jpg
            image2.jpg
            ...
        class2_name/
            image3.jpg
            ...
    validation/
        ...
    test/
        ...
```
*The "validation" and "test" directories are organized in the same way as the "train" directory.*
### Setup:
---
The Jupyter notebook was created in Google Colaboratory, and the images were downloaded to Google Drive, so it's easier to open and run it there, but first, replace or recreate an image storage path.
### Versions of packages used:
---
python 3.7.10, fiftyone 0.9.3
### Data: 
---
Images of two classes "Rabbit" and "Squirrel" from [Open Images Dataset V6 + Extensions](https://storage.googleapis.com/openimages/web/index.html) licensed under a [Attribution 2.0 Generic (CC BY 2.0)](https://creativecommons.org/licenses/by/2.0/) license with a note (see the License section on the [Description page](https://storage.googleapis.com/openimages/web/factsfigures_v6.html) of the Dataset for more information).
