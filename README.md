# CityscapesSemSegSanFranciscoLombard
Training in Cityscapes dataset, implement semantic segmentation to detect objects like trees, buildings, roads, sky, cars, pedestrians, bicycles, stop signs, and traffic lights. 

In semantic segmentation, each object is painted with tiny pixels that make up a computer image that belong to that classes of object. Each class of object has a unique color identification. For example, pedestrians are painted red, sky is painted light blue, cars are painted navy blue, sidewalk is painted pink, buildings are painted gray, roads are painted purple, and trees are painted green.

Just finished generating semantic segmentation videos for the first time, but I will improve on the training of the dataset.

I generated semantic segmentation images in segmented_imgs directory.  They look like paintings from a postcard.
Notice the road has been classified in LomardSegmentedImg11.JPG, LomardSegmentedImg12.JPG, LomardSegmentedImg13.JPG, LomardSegmentedImg14.JPG, LomardSegmentedImg4.JPG, and LomardSegmentedImg5.JPG.

From my observation, the road is being classified best when the road is tilted on one side and the road is bumpy with surface texture.
It also do well when the car is making a turn. It does very poor on roads with flat surface. On my next video recording, I will try to point the camera more downward to focus on the road surface more. I think my camera is pointing too much at an upward angle. Therefore, it is hard for road classification.

Another observation is that as I calibrate the camera images and undistort each video frame. There is a huge performance improvement in road classification. More areas of the road is painted purple than before.

I will train the dataset more until the entropy loss is going down a little more.

Here are the youtube links:
https://youtu.be/8KuIyKnmlqk

https://youtu.be/CA_SIvk1efI

https://youtu.be/54X9Sa3pjEE
