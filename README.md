# fxhash-generative
generative art for fxhash on tezos


Use this code to set up a generative, layered-image project on https://www.fxhash.xyz/

1) Download or clone the index.html file. 
2) Drop your images into the same folder as the index.html file. 
3) Change the image filenames in index to your actual file names. 
4) Delete or add layers as necessary.
5) Zip the index.html file and all of your images, and test that zip on the fxhash sandbox. 
6) If it passes the tests... mint it!! And let me know! @enuflark on twitter. :)

--


This project is designed to have four layers of images called randomly. 
Currently they are set up as Background, Border, Gesture, and Texture. 

The images are transparent PNG files which are all set to be 800 x 800 pixels. 
SVG support is currently tricky on fxhash, but that would make the project file an even smaller size.
Fxhash has a 15mb limit, and it is recommended to stay well under that.
