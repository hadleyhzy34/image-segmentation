# Image Segmentation

## Usage
``` 
python imagesegmentation.py filename
```

A new window will pop up showing your image. Use your cursor to mark object seeds, which would be shown in red. Once you're done, press `esc`. Then do the same to mark background seeds, which would be shown in green.

## Dependencies

- Python 2
- OpenCV 3.3
- NumPy

## Examples

1. `test1.jpg` 

Original, seeded, and segmented image

![test1.jpg](test1.jpg) 

![test1seeds.jpg](test1seeds.jpg) 

![test1cut.jpg](test1cut.jpg)

2. `test2.jpg`

Original, seeded, and segmented image

![test2.jpg](test2.jpg)

![test2seeds.jpg](test2seeds.jpg)

![test2cut.jpg](test2cut.jpg)

3. `test3.jpg`

Original, seeded, and segmented image

![test3.jpg](test3.jpg)

![test3seeds.jpg](test3seeds.jpg)

![test3cut.jpg](test3cut.jpg)


1. `baby.jpg`

Original, seeded, and segmented image

![baby.jpg](baby.jpg)

![babyseeds.jpg](babyseeds.jpg)

![babycut.jpg](babycut.jpg)

## To dos

- Add other graph cut algorithms
- Optimize it so it can run in reasonable time for small images (as of right now it can only work fast enough for 30 x 30 images)
- Stretch goal: make a web app
