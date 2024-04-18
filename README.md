# Approximate-Image-Processing-Datasets
This repository contains datasets for image addition and grayscale filtering. Their area of use was intended for approximate computing. They consist of classic example images with 8-bit depth for the grayscale images and 3x8-bit depth for the colored images.
We choose a wide variety of sources so that the image processing applications can be tested more generally.

## Image Addition
For addition all images were resized to 256x256, so that they can be added together, and a grayscale filter was applied via open-cv in python.
This datasets consists of 21 entries which are shown with the corresponding sources.
+ boat.tiff [1]
+ cameraman.tiff [2]
+ circuit.tiff [2]
+ clock.tiff [1]
+ coins.png [2]
+ house.tiff [1]
+ jellybeans.tiff [1]
+ jetplane.tiff [3]
+ lake.tiff [3]
+ lena.tiff [3]
+ liftingbody.png [2]
+ livingroom.tiff [3]
+ mandril.tiff [1]
+ peppers.tiff [1]
+ pirate.tiff [3]
+ pout.tiff [2]
+ rice.png [2]
+ tree.tiff [1]
+ walkbridge.tiff [3]
+ woman_blonde.tiff [3]
+ woman_darkhair.tiff [3]

## Grayscale Filtering
For the grayscale filtering we also took classics from different image processing applications.
Since each image is processed seperatly from each other they vary in size.
This dataset also consists of 21 entries which are shown with their corresponding sources.
+ airplane.tiff [1]
+ boat_on_lake.tiff [1]
+ cablecar.bmp [4]
+ cornfield.bmp [4]
+ female_ntsc.tiff [1]
+ flamingos.jpg [2]
+ fruits.png [4]
+ girl.bmp [4]
+ indiancorn.jpg [2]
+ lena_color.tiff [3]
+ llama.jpg [2] 
+ mandril_color.tif [1]
+ monarch.bmp [3]
+ peacock.jpg [2]
+ pens.bmp [4]
+ peppers.tiff [1]
+ sherlock.jpg [2]
+ toysnoflash.png [2]
+ trailer.jpg [2]
+ tulips.png [3]
+yacht.bmp [4]

[1] SIPI Image Database - https://sipi.usc.edu/database/database.php <br />
[2] MATLAB Example Data Sets - Images <br />
[3] https://github.com/mohammadimtiazz/standard-test-images-for-Image-Processing/tree/master/standard_test_images <br />
[4] https://www.kaggle.com/datasets/saeedehkamjoo/standard-test-images?select=STI <br />
