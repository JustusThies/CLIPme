# CLIPme if you can!

[CLIP](https://openai.com/blog/clip/) is a powerful tool to match images to text descriptions.
It can be used for classification of ImageNet classes as shown in the original paper, but it can also be used to assign names of (famous) people to images.

This code assumes that we have an image and a list of names of people in the image as input.
It then assigns the names to the faces detected in the image based on CLIP similarity.

Obviously, I had to try it with an image of myself and it turns out that it can also annotate my face:
<img src="samples/berlin_annotations.jpg" alt="Face Annotations" style="width:600px;height:450px;">
