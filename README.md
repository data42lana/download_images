## Downloading images from Open Images using the FiftyOne tool
---
A Jupyter notebook, describing the selection, downloading, and saving of images from Open Images in a certain format using the FiftyOne tool.
### Overview:
---
The objective of the project is to download images of the required classes from Open Images and save them in the ImageClassificationDirectoryTree format using FiftyOne tool. It is suitable for those who want to get images from the Open Images Dataset in the following format:
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
For the project, we took images of two classes "Rabbit" and "Squirrel" from [Open Images Dataset V6 + Extensions](https://storage.googleapis.com/openimages/web/index.html)
### How can you help:
---
If you find any bugs, issues, or have any questions or recommendations for improvement this project, please write about it.
