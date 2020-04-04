# Solving complex and intervened captcha by using CNN algorithm
The main problems in this captcha is:

1. complex background.
2. intervened items.

This is an example of the captcha image: the problem is that it has very complex background. there is a must to remove the back ground first by using cv2 processes and then slicing the letters and numbers by specific rules.


![Screenshot from 2020-04-04 19-24-41](https://user-images.githubusercontent.com/40704091/78457385-08a88080-76aa-11ea-8b5b-ba0eb9743601.png)


#### Tips:
  check versions compatability
#### Output Accuracy : 85 % 
#### Recommendations for further improvement:
  
  1.Slicing can be improved to separate the letters and numbers clearly.
  
  2.Image segmentation using CNN instead of slicing.
  
  3.Background removal using another algo.
